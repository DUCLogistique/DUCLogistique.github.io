# Configuration Supabase - Setup Guide

## Problème : Les modifications ne s'enregistrent pas

La cause est probablement les **permissions RLS (Row Level Security)** qui bloquent les écritures publiques.

## Solution : Désactiver RLS pour la table `planning`

### Option 1 : Désactiver RLS complètement (Rapide & Simple)

1. Allez dans **Supabase Dashboard** → **Authentication** → **Policies**
2. Cherchez la table `planning`
3. Cliquez sur le toggle **RLS** pour la désactiver
4. Confirmez

✅ **C'est fait !** Les modifications devraient maintenant s'enregistrer.

### Option 2 : Configurer RLS avec des règles (Plus sécurisé)

Si vous avez désactivé RLS, vous pouvez aussi configurer des règles spécifiques :

1. **Réactiver RLS** sur la table `planning`
2. Créer une policy `Allow all` :
   ```sql
   -- Enable RLS
   ALTER TABLE planning ENABLE ROW LEVEL SECURITY;

   -- Create a policy that allows all operations
   CREATE POLICY "Allow all operations" ON planning
   FOR ALL USING (true)
   WITH CHECK (true);
   ```

## Vérifier que ça marche

### Depuis le terminal :
```bash
curl -X PATCH "https://YOUR_SUPABASE_URL/rest/v1/planning?id=eq.1" \
  -H "apikey: YOUR_SUPABASE_KEY" \
  -H "Authorization: Bearer YOUR_SUPABASE_KEY" \
  -H "Content-Type: application/json" \
  -d '{"bookings": {"test": "data"}, "updated_at": "2026-02-04T12:00:00Z"}'
```

Vous devriez recevoir une réponse HTTP 200.

### Depuis le site :
1. Ouvrez https://duclogistique.github.io
2. Ajoutez une réservation
3. Ouvrez le site dans un autre onglet/navigateur
4. La réservation doit s'afficher automatiquement ! 🎉

## Troubleshooting

### Les modifications ne s'enregistrent toujours pas ?

1. Ouvrez **F12** → **Console** dans votre navigateur
2. Cherchez les erreurs ou messages `console.warn`/`console.error`
3. Copiez-collez les erreurs ici pour diagnostiquer

### J'ai oublié mes identifiants Supabase

1. Allez sur https://app.supabase.com
2. Sélectionnez votre projet
3. Settings → API → Copiez `Project URL` et `anon public key`
4. Mettez à jour dans `index.html` (lignes 836-837)
