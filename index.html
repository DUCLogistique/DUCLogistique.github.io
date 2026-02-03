<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planning Hebdomadaire - Entrepôt Logistique</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9fafb;
            color: #333;
            padding: 20px;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        header {
            background: linear-gradient(135deg, #003c4b 0%, #004d5c 100%);
            color: white;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        h1 i {
            color: #35c28e;
        }
        
        .subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 30px;
        }
        
        .info-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
            border-left: 5px solid #003c4b;
        }
        
        .info-card h3 {
            color: #003c4b;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .info-card h3 i {
            color: #35c28e;
        }
        
        .disponibilites-list { list-style: none; padding-left: 0; }
        .disponibilites-list li {
            padding: 10px 0;
            border-bottom: 1px dashed #e5e7eb;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 8px;
        }
        .disponibilites-list li:last-child { border-bottom: none; }
        .disponibilites-day { font-weight: 600; color: #003c4b; }
        .disponibilites-stats { display: flex; gap: 12px; font-size: 0.95rem; }
        .disponibilites-pris { color: #dc2626; }
        .disponibilites-restant { color: #218c61; }
        
        .time-slots ul, .employees ul {
            list-style: none;
            padding-left: 10px;
        }
        
        .time-slots li, .employees li {
            padding: 8px 0;
            border-bottom: 1px dashed #e5e7eb;
            display: flex;
            justify-content: space-between;
        }
        
        .time-slots li:last-child, .employees li:last-child {
            border-bottom: none;
        }
        
        .time-slot {
            font-weight: 600;
            color: #003c4b;
        }
        
        .capacity {
            background-color: rgba(53, 194, 142, 0.15);
            color: #218c61;
            padding: 3px 8px;
            border-radius: 4px;
            font-size: 0.9rem;
        }
        
        .employee-name {
            font-weight: 600;
        }
        
        .employee-schedule {
            font-size: 0.9rem;
            color: #666;
        }
        
        .employee-name-colored { font-weight: 600; }
        
        .employee-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 10px;
            flex-wrap: wrap;
        }
        .employee-row .left { display: flex; align-items: center; gap: 10px; flex: 1; min-width: 0; }
        .employee-color-picker { width: 28px; height: 28px; border: 2px solid #d1d5db; border-radius: 6px; cursor: pointer; padding: 0; background: transparent; }
        .employee-color-picker:hover { border-color: #003c4b; }
        .btn-remove-employee { background: #dc2626; color: white; border: none; padding: 6px 10px; border-radius: 5px; cursor: pointer; font-size: 0.85rem; }
        .btn-remove-employee:hover { background: #b91c1c; }
        .btn-add-employee { background: #35c28e; color: white; border: none; padding: 10px 16px; border-radius: 5px; cursor: pointer; font-size: 0.9rem; margin-top: 10px; display: inline-flex; align-items: center; gap: 8px; }
        .btn-add-employee:hover { background: #2da876; }
        .btn-edit-schedule {
            background: #003c4b;
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.85rem;
            display: inline-flex;
            align-items: center;
            gap: 6px;
            transition: background 0.2s;
        }
        .btn-edit-schedule:hover { background: #004d5c; }
        
        .week-navigation {
            display: flex;
            flex-direction: column;
            gap: 14px;
            background: #f9fafb;
            padding: 15px 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        }
        
        .week-nav-main {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .week-range {
            font-size: 1.3rem;
            font-weight: 600;
            color: #003c4b;
        }
        
        .date-selector {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }
        
        .date-selector label { font-size: 0.95rem; color: #374151; font-weight: 500; }
        .date-selector select {
            padding: 8px 12px;
            border: 1px solid #d1d5db;
            border-radius: 6px;
            font-size: 0.95rem;
            background: white;
            color: #003c4b;
            cursor: pointer;
            min-width: 120px;
        }
        .date-selector select:focus { outline: none; border-color: #003c4b; }
        
        .nav-btn {
            background: #003c4b;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
            transition: background 0.3s;
        }
        
        .nav-btn:hover {
            background: #004d5c;
        }
        
        .weekdays {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 15px;
            margin-bottom: 30px;
        }
        
        .day-column {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        }
        
        .day-header {
            background: #003c4b;
            color: white;
            padding: 15px;
            text-align: center;
            font-weight: 600;
            font-size: 1.2rem;
        }
        
        .today .day-header {
            background: #35c28e;
        }
        
        .date {
            font-size: 0.9rem;
            opacity: 0.9;
            margin-top: 5px;
        }
        
        .time-slots-container {
            padding: 10px;
        }
        
        .time-slot-cell {
            border-bottom: 1px solid #e5e7eb;
            padding: 12px 10px;
        }
        
        .time-slot-cell:last-child {
            border-bottom: none;
        }
        
        .slot-time {
            font-weight: 600;
            color: #003c4b;
            margin-bottom: 10px;
            font-size: 0.95rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .slot-status {
            font-size: 0.8rem;
            padding: 2px 8px;
            border-radius: 10px;
            background-color: rgba(53, 194, 142, 0.15);
            color: #218c61;
        }
        
        .employees-slots {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        .employee-slot {
            padding: 8px;
            border-radius: 5px;
        }
        
        
        .employee-unavailable {
            opacity: 0.5;
            background-color: #f9fafb !important;
            border-left: 3px solid #d1d5db !important;
        }
        
        .slot-title {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
            font-size: 0.9rem;
        }
        
        .truck-slots {
            display: flex;
            gap: 5px;
        }
        
        .truck-slot {
            flex: 1;
            min-width: 0;
            height: 30px;
            border: 1px dashed #d1d5db;
            border-radius: 4px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.8rem;
            cursor: pointer;
            transition: all 0.2s;
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap;
            padding: 0 6px;
        }
        
        .truck-slot:hover {
            transform: scale(1.05);
        }
        
        .truck-slot.available {
            background-color: rgba(53, 194, 142, 0.15);
            border-color: #35c28e;
            color: #218c61;
        }
        
        .truck-slot.booked {
            background-color: #fef2f2;
            border-color: #dc2626;
            color: #b91c1c;
        }
        
        .truck-slot.booked-recurring {
            background-color: #fff7ed;
            border-color: #ea580c;
            color: #c2410c;
        }
        
        .truck-slot.unavailable {
            background-color: #f9fafb;
            border-color: #d1d5db;
            color: #9ca3af;
            cursor: not-allowed;
        }
        
        .truck-slot.slot-na {
            background-color: #f3f4f6;
            border-color: #9ca3af;
            color: #6b7280;
            cursor: pointer;
        }
        
        .legend {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
            flex-wrap: wrap;
        }
        #legend-employees { display: contents; }
        
        .legend-item {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.9rem;
        }
        
        .color-box {
            width: 20px;
            height: 20px;
            border-radius: 4px;
        }
        
        .color-available {
            background-color: rgba(53, 194, 142, 0.15);
            border: 1px dashed #35c28e;
        }
        
        .color-booked {
            background-color: #fef2f2;
            border: 1px dashed #dc2626;
        }
        
        .color-recurring {
            background-color: #fff7ed;
            border: 1px dashed #ea580c;
        }
        
        .color-unavailable {
            background-color: #f9fafb;
            border: 1px dashed #d1d5db;
        }
        
        .color-slot-na {
            background-color: #f3f4f6;
            border: 1px dashed #9ca3af;
        }
        
        .modal-overlay {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(0,0,0,0.4);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .modal-overlay.open { display: flex; }
        .modal-schedule {
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 40px rgba(0,0,0,0.2);
            max-width: 420px;
            width: 100%;
            max-height: 90vh;
            overflow-y: auto;
        }
        .modal-schedule .modal-header {
            background: #003c4b;
            color: white;
            padding: 16px 20px;
            border-radius: 10px 10px 0 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .modal-schedule .modal-header h3 { margin: 0; font-size: 1.2rem; }
        .modal-schedule .modal-close {
            background: transparent;
            border: none;
            color: white;
            cursor: pointer;
            font-size: 1.4rem;
            line-height: 1;
            padding: 0 4px;
        }
        .modal-schedule .modal-body { padding: 20px; }
        .schedule-plage {
            display: flex;
            gap: 10px;
            align-items: center;
            margin-bottom: 12px;
        }
        .schedule-plage span { color: #666; flex-shrink: 0; }
        .schedule-plage input {
            flex: 1;
            min-width: 70px;
            padding: 8px 10px;
            border: 1px solid #d1d5db;
            border-radius: 5px;
            font-size: 0.95rem;
        }
        .schedule-plage input:focus { outline: none; border-color: #003c4b; }
        .btn-remove-plage {
            background: #003c4b;
            color: white;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        .btn-remove-plage:hover { background: #004d5c; }
        .btn-add-plage {
            background: #35c28e;
            color: white;
            border: none;
            padding: 10px 16px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
            margin-bottom: 16px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        .btn-add-plage:hover { background: #2da876; }
        .modal-schedule .modal-actions {
            display: flex;
            gap: 10px;
            justify-content: flex-end;
            margin-top: 20px;
            padding-top: 16px;
            border-top: 1px solid #e5e7eb;
        }
        .modal-schedule .btn-cancel {
            background: #f9fafb;
            color: #374151;
            border: 1px solid #d1d5db;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .modal-schedule .btn-cancel:hover { background: #f3f4f6; }
        .modal-schedule .btn-save {
            background: #003c4b;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .modal-schedule .btn-save:hover { background: #004d5c; }
        .schedule-hint { font-size: 0.85rem; color: #666; margin-bottom: 12px; }

        .modal-booking { background: white; border-radius: 10px; box-shadow: 0 10px 40px rgba(0,0,0,0.2); max-width: 440px; width: 100%; max-height: 90vh; overflow-y: auto; }
        .modal-booking .modal-header { background: #003c4b; color: white; padding: 16px 20px; border-radius: 10px 10px 0 0; display: flex; justify-content: space-between; align-items: center; }
        .modal-booking .modal-header h3 { margin: 0; font-size: 1.2rem; }
        .modal-booking .modal-body { padding: 20px; }
        .booking-context { font-size: 0.95rem; color: #374151; margin-bottom: 16px; padding: 10px 12px; background: #f3f4f6; border-radius: 6px; }
        .booking-panel { margin-top: 8px; }
        .booking-type-choice { display: flex; gap: 10px; margin-bottom: 16px; }
        .btn-booking-type { flex: 1; padding: 12px 16px; border: 2px solid #d1d5db; border-radius: 8px; background: white; cursor: pointer; font-size: 1rem; font-weight: 500; color: #374151; display: flex; align-items: center; justify-content: center; gap: 8px; transition: all 0.2s; }
        .btn-booking-type:hover { border-color: #003c4b; color: #003c4b; background: rgba(0,60,75,0.05); }
        .btn-booking-type.active { border-color: #003c4b; background: rgba(0,60,75,0.1); color: #003c4b; }
        .btn-booking-type[data-type="na"]:hover { border-color: #6b7280; color: #4b5563; }
        .btn-booking-type[data-type="na"].active { border-color: #6b7280; background: #f3f4f6; color: #374151; }
        .booking-form-reserve label, #booking-panel-edit label { display: block; font-weight: 500; color: #374151; margin-bottom: 6px; font-size: 0.95rem; }
        .booking-form-reserve input[type="text"], #booking-client-edit { width: 100%; padding: 10px 12px; border: 1px solid #d1d5db; border-radius: 6px; font-size: 1rem; margin-bottom: 14px; box-sizing: border-box; }
        .booking-form-reserve input:focus, #booking-client-edit:focus { outline: none; border-color: #003c4b; }
        .muted { font-weight: 400; color: #6b7280; }
        .checkbox-label { display: flex !important; align-items: center; gap: 10px; margin-bottom: 0 !important; cursor: pointer; }
        .checkbox-label input { width: auto; margin: 0; }
        .booking-na-msg { margin: 0; padding: 12px; background: #fef3c7; border-radius: 6px; color: #92400e; }
        .modal-booking-actions { display: flex; flex-wrap: wrap; gap: 10px; justify-content: flex-end; padding: 16px 20px; border-top: 1px solid #e5e7eb; }
        .modal-booking .btn-cancel { background: #f9fafb; color: #374151; border: 1px solid #d1d5db; padding: 10px 18px; border-radius: 6px; cursor: pointer; font-weight: 500; }
        .modal-booking .btn-cancel:hover { background: #f3f4f6; }
        .modal-booking .btn-save { background: #003c4b; color: white; border: none; padding: 10px 18px; border-radius: 6px; cursor: pointer; font-weight: 500; display: inline-flex; align-items: center; gap: 8px; }
        .modal-booking .btn-save:hover { background: #004d5c; }
        .modal-booking .btn-danger { background: #dc2626; color: white; border: none; padding: 10px 18px; border-radius: 6px; cursor: pointer; font-weight: 500; display: inline-flex; align-items: center; gap: 8px; }
        .modal-booking .btn-danger:hover { background: #b91c1c; }
        .modal-booking .btn-secondary { background: #6b7280; color: white; border: none; padding: 10px 18px; border-radius: 6px; cursor: pointer; font-weight: 500; display: inline-flex; align-items: center; gap: 8px; }
        .modal-booking .btn-secondary:hover { background: #4b5563; }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #e5e7eb;
            color: #666;
            font-size: 0.9rem;
        }
        
        @media (max-width: 1200px) {
            .weekdays {
                grid-template-columns: repeat(3, 1fr);
            }
        }
        
        @media (max-width: 768px) {
            .weekdays {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .info-grid {
                grid-template-columns: 1fr;
            }
            
            .week-navigation {
                flex-direction: column;
                gap: 15px;
                text-align: center;
            }
        }
        
        @media (max-width: 480px) {
            .weekdays {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            body {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-calendar-alt"></i> DUC logistique</h1>
            <p class="subtitle">Gestion des rendez-vous de réception et d'expédition</p>
        </header>
        
        <div class="info-grid">
            <div class="info-card" id="disponibilites-card">
                <h3><i class="fas fa-chart-pie"></i> Disponibilités</h3>
                <div class="disponibilites-list" id="disponibilites-list">
                    <!-- Rempli dynamiquement par JavaScript -->
                </div>
            </div>
            
            <div class="info-card" id="employees-card">
                <h3><i class="fas fa-users"></i> Employés & Horaires</h3>
                <div class="employees">
                    <ul id="employees-list"></ul>
                    <button type="button" class="btn-add-employee" id="btn-add-employee"><i class="fas fa-user-plus"></i> Ajouter un employé</button>
                    <p style="margin-top: 15px; font-size: 0.9rem; color: #666;">
                        <i class="fas fa-info-circle"></i> Capacité : 2 camions par créneau et par employé
                    </p>
                </div>
            </div>
        </div>
        
        <div class="week-navigation">
            <div class="week-nav-main">
                <button class="nav-btn" id="prev-week">
                    <i class="fas fa-chevron-left"></i> Semaine précédente
                </button>
                <div class="week-range" id="week-range">17 - 21 Juin 2024</div>
                <button class="nav-btn" id="next-week">
                    Semaine suivante <i class="fas fa-chevron-right"></i>
                </button>
            </div>
            <div class="date-selector">
                <label for="select-month">Aller à :</label>
                <select id="select-month" aria-label="Mois"></select>
                <select id="select-year" aria-label="Année"></select>
            </div>
        </div>
        
        <div class="weekdays" id="weekdays-container">
            <!-- Les jours de la semaine seront générés par JavaScript -->
        </div>
        
        <div class="legend" id="legend-container">
            <div id="legend-employees"></div>
            <div class="legend-item">
                <div class="color-box color-available"></div>
                <span>Créneau disponible</span>
            </div>
            <div class="legend-item">
                <div class="color-box color-booked"></div>
                <span>Créneau réservé</span>
            </div>
            <div class="legend-item">
                <div class="color-box color-recurring"></div>
                <span>Navette quotidienne</span>
            </div>
            <div class="legend-item">
                <div class="color-box color-unavailable"></div>
                <span>Employé non-disponible</span>
            </div>
            <div class="legend-item">
                <div class="color-box color-slot-na"></div>
                <span>N/A (bloqué)</span>
            </div>
        </div>
        
        <footer>
            <p>DUC logistique • Gestion des rendez-vous de réception et d'expédition • 2024</p>
        </footer>

        <div class="modal-overlay" id="modal-schedule-overlay">
            <div class="modal-schedule">
                <div class="modal-header">
                    <h3 id="modal-schedule-title">Modifier les horaires</h3>
                    <button type="button" class="modal-close" id="modal-schedule-close" aria-label="Fermer">&times;</button>
                </div>
                <div class="modal-body">
                    <p class="schedule-hint">Format : 7h, 9h30, 12h, 15h30… Une plage par ligne (début – fin).</p>
                    <div id="modal-schedule-plages"></div>
                    <button type="button" class="btn-add-plage" id="modal-add-plage"><i class="fas fa-plus"></i> Ajouter une plage</button>
                </div>
                <div class="modal-actions">
                    <button type="button" class="btn-cancel" id="modal-schedule-cancel">Annuler</button>
                    <button type="button" class="btn-save" id="modal-schedule-save">Enregistrer</button>
                </div>
            </div>
        </div>

        <div class="modal-overlay" id="modal-booking-overlay">
            <div class="modal-booking">
                <div class="modal-header">
                    <h3 id="modal-booking-title">Réserver un créneau</h3>
                    <button type="button" class="modal-close" id="modal-booking-close" aria-label="Fermer">&times;</button>
                </div>
                <div class="modal-body">
                    <p class="booking-context" id="modal-booking-context"></p>
                    <div id="booking-panel-libre" class="booking-panel">
                        <div class="booking-type-choice">
                            <button type="button" class="btn-booking-type" data-type="reserve"><i class="fas fa-calendar-check"></i> Réserver</button>
                            <button type="button" class="btn-booking-type" data-type="na"><i class="fas fa-ban"></i> Marquer N/A</button>
                        </div>
                        <div class="booking-form-reserve">
                            <label for="booking-client">Nom du client <span class="muted">(optionnel)</span></label>
                            <input type="text" id="booking-client" placeholder="Ex. Transport Dupont" />
                            <label class="checkbox-label"><input type="checkbox" id="booking-navette" /> <i class="fas fa-sync-alt"></i> Navette quotidienne (récurrence sur la semaine)</label>
                        </div>
                    </div>
                    <div id="booking-panel-edit" class="booking-panel" style="display:none;">
                        <label for="booking-client-edit">Nom du client</label>
                        <input type="text" id="booking-client-edit" placeholder="Ex. Transport Dupont" />
                        <label class="checkbox-label"><input type="checkbox" id="booking-navette-edit" /> Navette quotidienne</label>
                    </div>
                    <div id="booking-panel-na" class="booking-panel" style="display:none;">
                        <p class="booking-na-msg"><i class="fas fa-info-circle"></i> Ce créneau est bloqué (N/A). Cliquez sur <strong>Réactiver</strong> pour le libérer.</p>
                    </div>
                </div>
                <div class="modal-booking-actions">
                    <button type="button" class="btn-cancel" id="modal-booking-cancel">Annuler</button>
                    <button type="button" class="btn-danger" id="modal-booking-release" style="display:none;"><i class="fas fa-times"></i> Libérer</button>
                    <button type="button" class="btn-secondary" id="modal-booking-reactivate" style="display:none;"><i class="fas fa-undo"></i> Réactiver</button>
                    <button type="button" class="btn-save" id="modal-booking-apply" style="display:none;"><i class="fas fa-check"></i> Appliquer</button>
                    <button type="button" class="btn-save" id="modal-booking-save" style="display:none;"><i class="fas fa-save"></i> Enregistrer</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Configuration des créneaux horaires
        const timeSlots = [
            { start: "7h", end: "9h", label: "7h - 9h" },
            { start: "9h", end: "11h", label: "9h - 11h" },
            { start: "11h", end: "13h", label: "11h - 13h" },
            { start: "13h", end: "15h", label: "13h - 15h" },
            { start: "15h", end: "17h", label: "15h - 17h" }
        ];

        const DEFAULT_EMPLOYEE_COLORS = ['#003c4b', '#7d5c98', '#35c28e', '#ea580c', '#2563eb'];
        let nextEmployeeId = 3;
        let employees = [
            { id: 1, name: "Employé 1", color: "#003c4b", schedule: [{ start: 7, end: 12 }, { start: 13, end: 15.5 }] },
            { id: 2, name: "Employé 2", color: "#7d5c98", schedule: [{ start: 9.5, end: 12.5 }, { start: 13.5, end: 17.5 }] }
        ];
        function hexToRgba(hex, alpha) {
            const m = hex.match(/^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i);
            if (!m) return `rgba(0,60,75,${alpha})`;
            const r = parseInt(m[1], 16), g = parseInt(m[2], 16), b = parseInt(m[3], 16);
            return `rgba(${r},${g},${b},${alpha})`;
        }

        function initSlotState(v) {
            if (typeof v === 'boolean') return { booked: v, client: '', recurring: false, na: false };
            const o = v && typeof v === 'object' ? v : {};
            return { booked: !!o.booked, client: o.client != null ? String(o.client) : '', recurring: !!o.recurring, na: !!o.na };
        }
        let bookings = {};
        ['2024-06-17','2024-06-18','2024-06-19','2024-06-20','2024-06-21'].forEach(k => {
            bookings[k] = {
                '7h - 9h': { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(false)] },
                '9h - 11h': { 1: [initSlotState(true), initSlotState(true)], 2: [initSlotState(true), initSlotState(false)] },
                '11h - 13h': { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(false), initSlotState(true)] },
                '13h - 15h': { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(false)] },
                '15h - 17h': { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(true), initSlotState(true)] }
            };
        });
        bookings['2024-06-18']['7h - 9h'] = { 1: [initSlotState(false), initSlotState(true)], 2: [initSlotState(false), initSlotState(false)] };
        bookings['2024-06-18']['9h - 11h'] = { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(true)] };
        bookings['2024-06-18']['11h - 13h'] = { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(true), initSlotState(false)] };
        bookings['2024-06-18']['13h - 15h'] = { 1: [initSlotState(true), initSlotState(true)], 2: [initSlotState(false), initSlotState(false)] };
        bookings['2024-06-18']['15h - 17h'] = { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(true), initSlotState(false)] };
        bookings['2024-06-19']['9h - 11h'] = { 1: [initSlotState(true), initSlotState(true)], 2: [initSlotState(true), initSlotState(true)] };
        bookings['2024-06-19']['13h - 15h'] = { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(true)] };
        bookings['2024-06-19']['15h - 17h'] = { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(true), initSlotState(false)] };
        bookings['2024-06-20']['7h - 9h'] = { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(false)] };
        bookings['2024-06-20']['9h - 11h'] = { 1: [initSlotState(false), initSlotState(true)], 2: [initSlotState(true), initSlotState(false)] };
        bookings['2024-06-20']['13h - 15h'] = { 1: [initSlotState(true), initSlotState(true)], 2: [initSlotState(false), initSlotState(false)] };
        bookings['2024-06-20']['15h - 17h'] = { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(false), initSlotState(true)] };
        bookings['2024-06-21']['9h - 11h'] = { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(true)] };
        bookings['2024-06-21']['11h - 13h'] = { 1: [initSlotState(false), initSlotState(true)], 2: [initSlotState(true), initSlotState(false)] };
        bookings['2024-06-21']['13h - 15h'] = { 1: [initSlotState(true), initSlotState(false)], 2: [initSlotState(false), initSlotState(false)] };
        bookings['2024-06-21']['15h - 17h'] = { 1: [initSlotState(false), initSlotState(false)], 2: [initSlotState(true), initSlotState(true)] };

        let currentDate = new Date(2024, 5, 17);
        const MONTHS_FR = ['Janvier','Février','Mars','Avril','Mai','Juin','Juillet','Août','Septembre','Octobre','Novembre','Décembre'];

        const STORAGE_KEY = 'duc-logistique-planning';
        function saveData() {
            try {
                localStorage.setItem(STORAGE_KEY, JSON.stringify({
                    bookings, employees, currentDate: currentDate.getTime(), nextEmployeeId
                }));
            } catch (e) {}
        }
        function loadData() {
            try {
                const raw = localStorage.getItem(STORAGE_KEY);
                if (!raw) return;
                const data = JSON.parse(raw);
                if (data.bookings && typeof data.bookings === 'object') {
                    for (const dateKey in data.bookings) {
                        for (const slotLabel in data.bookings[dateKey]) {
                            for (const empId in data.bookings[dateKey][slotLabel]) {
                                const arr = data.bookings[dateKey][slotLabel][empId];
                                if (Array.isArray(arr)) {
                                    data.bookings[dateKey][slotLabel][empId] = arr.map(s => initSlotState(s));
                                }
                            }
                        }
                    }
                    bookings = data.bookings;
                }
                if (data.employees && Array.isArray(data.employees) && data.employees.length > 0) {
                    employees = data.employees;
                }
                if (typeof data.nextEmployeeId === 'number') nextEmployeeId = data.nextEmployeeId;
                if (typeof data.currentDate === 'number') currentDate = new Date(data.currentDate);
            } catch (e) {}
        }
        loadData();

        function initDateSelects() {
            const monthSel = document.getElementById('select-month');
            const yearSel = document.getElementById('select-year');
            if (!monthSel || !yearSel) return;
            monthSel.innerHTML = '';
            for (let i = 0; i < 12; i++) { const o = document.createElement('option'); o.value = i; o.textContent = MONTHS_FR[i]; monthSel.appendChild(o); }
            const y0 = new Date().getFullYear();
            for (let y = y0 - 2; y <= y0 + 3; y++) { const o = document.createElement('option'); o.value = y; o.textContent = String(y); yearSel.appendChild(o); }
        }
        function updateDateSelectsFromWeek() {
            const weekDates = getWeekDates(currentDate);
            const m = weekDates[0].getMonth(), y = weekDates[0].getFullYear();
            const monthSel = document.getElementById('select-month'), yearSel = document.getElementById('select-year');
            if (!monthSel || !yearSel) return;
            monthSel.value = String(m);
            if (!yearSel.querySelector(`option[value="${y}"]`)) { const o = document.createElement('option'); o.value = y; o.textContent = String(y); yearSel.appendChild(o); }
            yearSel.value = String(y);
        }
        function goToMonthYear(month, year) {
            const d = new Date(year, month, 1);
            const day = d.getDay();
            const add = day === 0 ? 1 : day === 1 ? 0 : (8 - day);
            d.setDate(1 + add);
            currentDate.setTime(d.getTime());
            renderWeek();
        }

        function decimalToTimeStr(d) {
            const h = Math.floor(d), m = Math.round((d - h) * 60);
            return m ? `${h}h${String(m).padStart(2,'0')}` : `${h}h`;
        }
        function timeStrToDecimal(s) {
            if (!s || typeof s !== 'string') return NaN;
            const t = String(s).trim().replace(/\s/g,'');
            const m = t.match(/^(\d{1,2})h(\d{0,2})?$/i);
            if (!m) return NaN;
            const h = parseInt(m[1],10), min = m[2] ? parseInt(m[2],10) : 0;
            if (h < 0 || h > 23 || min < 0 || min > 59) return NaN;
            return h + min / 60;
        }
        function formatScheduleDisplay(schedule) {
            if (!schedule || !schedule.length) return '—';
            return schedule.map(p => `${decimalToTimeStr(p.start)} - ${decimalToTimeStr(p.end)}`).join(' & ');
        }
        function addEmployee() {
            const id = nextEmployeeId++;
            const colorIndex = (employees.length) % DEFAULT_EMPLOYEE_COLORS.length;
            employees.push({ id, name: `Employé ${employees.length + 1}`, color: DEFAULT_EMPLOYEE_COLORS[colorIndex], schedule: [{ start: 8, end: 12 }, { start: 14, end: 18 }] });
            renderEmployeesList();
            renderWeek();
        }
        function removeEmployee(empId) {
            if (employees.length <= 1) { alert('Il doit rester au moins un employé.'); return; }
            if (!confirm('Supprimer cet employé ? Les réservations associées seront perdues.')) return;
            employees = employees.filter(e => e.id !== empId);
            renderEmployeesList();
            renderWeek();
        }
        function updateEmployeeColor(empId, color) {
            const emp = employees.find(e => e.id === empId);
            if (emp) { emp.color = color; renderEmployeesList(); renderWeek(); }
        }
        function renderLegend() {
            const cont = document.getElementById('legend-employees');
            if (!cont) return;
            cont.innerHTML = employees.map(emp => {
                const c = emp.color || '#003c4b';
                return `<div class="legend-item"><div class="color-box" style="background-color:${hexToRgba(c,0.22)};border-left:3px solid ${c}"></div><span>${emp.name}</span></div>`;
            }).join('');
        }
        function renderEmployeesList() {
            const ul = document.getElementById('employees-list');
            if (!ul) return;
            ul.innerHTML = '';
            employees.forEach(emp => {
                const li = document.createElement('li');
                                const col = emp.color || '#003c4b';
                li.innerHTML = `<div class="employee-row"><div class="left"><input type="color" class="employee-color-picker" data-employee-id="${emp.id}" value="${col}" title="Choisir la couleur" /><span class="employee-name employee-name-colored" style="color:${col}">${emp.name}</span><span class="employee-schedule">${formatScheduleDisplay(emp.schedule)}</span></div><div><button type="button" class="btn-edit-schedule" data-employee-id="${emp.id}" title="Modifier les horaires"><i class="fas fa-edit"></i> Modifier</button><button type="button" class="btn-remove-employee" data-employee-id="${emp.id}" title="Supprimer l'employé"><i class="fas fa-trash-alt"></i></button></div></div>`;
                ul.appendChild(li);
            });
            ul.querySelectorAll('.btn-edit-schedule').forEach(btn => btn.addEventListener('click', () => openScheduleModal(parseInt(btn.dataset.employeeId, 10))));
            ul.querySelectorAll('.btn-remove-employee').forEach(btn => btn.addEventListener('click', () => removeEmployee(parseInt(btn.dataset.employeeId, 10))));
            ul.querySelectorAll('.employee-color-picker').forEach(input => input.addEventListener('input', (e) => updateEmployeeColor(parseInt(e.target.dataset.employeeId, 10), e.target.value)));
            renderLegend();
        }
        let editingEmployeeId = null;
        function openScheduleModal(employeeId) {
            const emp = employees.find(e => e.id === employeeId);
            if (!emp) return;
            editingEmployeeId = employeeId;
            document.getElementById('modal-schedule-title').textContent = `Modifier les horaires – ${emp.name}`;
            const container = document.getElementById('modal-schedule-plages');
            container.innerHTML = '';
            emp.schedule.forEach(p => addPlageRow(container, decimalToTimeStr(p.start), decimalToTimeStr(p.end)));
            if (!container.querySelector('.schedule-plage')) addPlageRow(container, '', '');
            document.getElementById('modal-schedule-overlay').classList.add('open');
        }
        function addPlageRow(container, startVal, endVal) {
            const div = document.createElement('div');
            div.className = 'schedule-plage';
            div.innerHTML = `<input type="text" class="plage-start" placeholder="7h" value="${startVal||''}" /><span>à</span><input type="text" class="plage-end" placeholder="12h" value="${endVal||''}" /><button type="button" class="btn-remove-plage" title="Supprimer"><i class="fas fa-trash-alt"></i></button>`;
            container.appendChild(div);
            div.querySelector('.btn-remove-plage').addEventListener('click', () => { div.remove(); if (!container.querySelectorAll('.schedule-plage').length) addPlageRow(container,'',''); });
        }
        function closeScheduleModal() { editingEmployeeId = null; document.getElementById('modal-schedule-overlay').classList.remove('open'); }
        function saveScheduleModal() {
            const emp = employees.find(e => e.id === editingEmployeeId);
            if (!emp) { closeScheduleModal(); return; }
            const container = document.getElementById('modal-schedule-plages');
            const schedule = [];
            container.querySelectorAll('.schedule-plage').forEach(row => {
                const start = timeStrToDecimal(row.querySelector('.plage-start').value);
                const end = timeStrToDecimal(row.querySelector('.plage-end').value);
                if (!isNaN(start) && !isNaN(end) && start < end) schedule.push({ start, end });
            });
            schedule.sort((a,b) => a.start - b.start);
            emp.schedule = schedule;
            closeScheduleModal();
            renderEmployeesList();
            renderWeek();
        }

        // Fonction pour obtenir les dates de la semaine
        function updateDisponibilites(weekDates) {
            const ul = document.getElementById('disponibilites-list');
            if (!ul) return;
            ul.innerHTML = '';
            weekDates.forEach(date => {
                const dateKey = getDateKey(date);
                let dayPris = 0, dayTaken = 0, dayTotal = 0;
                timeSlots.forEach(slot => {
                    employees.forEach(emp => {
                        if (isEmployeeAvailable(emp.id, slot)) {
                            dayTotal += 2;
                            const arr = bookings[dateKey]?.[slot.label]?.[emp.id];
                            if (arr) arr.forEach(s => {
                                const o = typeof s === 'object' && s ? s : { booked: !!s, na: false };
                                if (o.booked) dayPris++;
                                if (o.booked || o.na) dayTaken++;
                            });
                        }
                    });
                });
                const dayRemaining = Math.max(0, dayTotal - dayTaken);
                const dayLabel = formatDate(date);
                const li = document.createElement('li');
                li.innerHTML = `<span class="disponibilites-day">${dayLabel}</span><span class="disponibilites-stats"><span class="disponibilites-pris">${dayPris} pris</span><span class="disponibilites-restant">${dayRemaining} restantes</span></span>`;
                ul.appendChild(li);
            });
        }

        function getWeekDates(date) {
            const startDate = new Date(date);
            const dayOfWeek = startDate.getDay();
            const diff = startDate.getDate() - dayOfWeek + (dayOfWeek === 0 ? -6 : 1); // Ajuster pour lundi
            startDate.setDate(diff);
            
            const weekDates = [];
            for (let i = 0; i < 5; i++) { // Du lundi au vendredi
                const currentDate = new Date(startDate);
                currentDate.setDate(startDate.getDate() + i);
                weekDates.push(currentDate);
            }
            
            return weekDates;
        }

        // Fonction pour formater la date
        function formatDate(date) {
            const options = { weekday: 'long', day: 'numeric', month: 'long' };
            return date.toLocaleDateString('fr-FR', options);
        }

        // Fonction pour obtenir la clé de date au format YYYY-MM-DD
        function getDateKey(date) {
            return date.toISOString().split('T')[0];
        }

        function isEmployeeAvailable(employeeId, slot) {
            const employee = employees.find(e => e.id === employeeId);
            if (!employee) return false;
            const slotStart = timeStrToDecimal(slot.start), slotEnd = timeStrToDecimal(slot.end);
            if (isNaN(slotStart) || isNaN(slotEnd)) return false;
            for (const plage of employee.schedule) {
                if (plage.start < slotEnd && plage.end > slotStart) return true;
            }
            return false;
        }
        function ensureSlotStructure(dateKey, timeSlot) {
            if (!bookings[dateKey]) bookings[dateKey] = {};
            if (!bookings[dateKey][timeSlot]) bookings[dateKey][timeSlot] = {};
            employees.forEach(emp => {
                if (!bookings[dateKey][timeSlot][emp.id]) bookings[dateKey][timeSlot][emp.id] = [initSlotState(false), initSlotState(false)];
                else for (let i = 0; i < 2; i++) bookings[dateKey][timeSlot][emp.id][i] = initSlotState(bookings[dateKey][timeSlot][emp.id][i]);
            });
        }
        let bookingCtx = null;
        function openBookingModal(dateKey, timeSlot, employeeId, truckIndex, slotState, dateLabel, empName) {
            ensureSlotStructure(dateKey, timeSlot);
            bookingCtx = { dateKey, timeSlot, employeeId, truckIndex };
            const slotLabel = timeSlot;
            const camion = truckIndex + 1;
            document.getElementById('modal-booking-context').textContent = `${dateLabel} • ${slotLabel} • ${empName} • Camion ${camion}`;

            const panelLibre = document.getElementById('booking-panel-libre');
            const panelEdit = document.getElementById('booking-panel-edit');
            const panelNa = document.getElementById('booking-panel-na');
            const btnRelease = document.getElementById('modal-booking-release');
            const btnReactivate = document.getElementById('modal-booking-reactivate');
            const btnApply = document.getElementById('modal-booking-apply');
            const btnSave = document.getElementById('modal-booking-save');
            const btnCancel = document.getElementById('modal-booking-cancel');
            [panelLibre, panelEdit, panelNa].forEach(p => { p.style.display = 'none'; });
            [btnRelease, btnReactivate, btnApply, btnSave].forEach(b => { b.style.display = 'none'; });
            btnCancel.style.display = 'inline-flex';

            if (slotState.na) {
                document.getElementById('modal-booking-title').textContent = 'Créneau bloqué';
                panelNa.style.display = 'block';
                btnReactivate.style.display = 'inline-flex';
                document.getElementById('modal-booking-overlay').classList.add('open');
                return;
            }
            if (slotState.booked) {
                document.getElementById('modal-booking-title').textContent = 'Modifier la réservation';
                panelEdit.style.display = 'block';
                document.getElementById('booking-client-edit').value = slotState.client || '';
                document.getElementById('booking-navette-edit').checked = !!slotState.recurring;
                btnRelease.style.display = 'inline-flex';
                btnSave.style.display = 'inline-flex';
                document.getElementById('modal-booking-overlay').classList.add('open');
                return;
            }
            document.getElementById('modal-booking-title').textContent = 'Réserver un créneau';
            panelLibre.style.display = 'block';
            document.querySelectorAll('.btn-booking-type').forEach(b => b.classList.remove('active'));
            document.querySelector('.btn-booking-type[data-type="reserve"]').classList.add('active');
            document.getElementById('booking-client').value = '';
            document.getElementById('booking-navette').checked = false;
            document.querySelector('.booking-form-reserve').style.display = 'block';
            btnApply.style.display = 'inline-flex';
            document.getElementById('modal-booking-overlay').classList.add('open');
        }
        function closeBookingModal() { bookingCtx = null; document.getElementById('modal-booking-overlay').classList.remove('open'); }
        function submitBookingModal() {
            if (!bookingCtx) return;
            const { dateKey, timeSlot, employeeId, truckIndex } = bookingCtx;
            ensureSlotStructure(dateKey, timeSlot);
            const s = bookings[dateKey][timeSlot][employeeId][truckIndex];

            const panelEdit = document.getElementById('booking-panel-edit');
            const panelNa = document.getElementById('booking-panel-na');
            const panelLibre = document.getElementById('booking-panel-libre');

            if (panelNa.style.display !== 'none') {
                s.na = false;
                closeBookingModal();
                renderWeek();
                return;
            }
            if (panelEdit.style.display !== 'none') {
                s.client = (document.getElementById('booking-client-edit').value || '').trim();
                s.recurring = document.getElementById('booking-navette-edit').checked;
                closeBookingModal();
                renderWeek();
                return;
            }
            const typeReserve = document.querySelector('.btn-booking-type[data-type="reserve"]').classList.contains('active');
            if (!typeReserve) {
                s.na = true;
                closeBookingModal();
                renderWeek();
                return;
            }
            const name = (document.getElementById('booking-client').value || '').trim();
            const recur = document.getElementById('booking-navette').checked;
            s.booked = true;
            s.client = name;
            s.recurring = recur;
            s.na = false;
            if (recur) {
                getWeekDates(currentDate).map(d => getDateKey(d)).forEach(k => {
                    if (k === dateKey) return;
                    ensureSlotStructure(k, timeSlot);
                    const c = bookings[k][timeSlot][employeeId][truckIndex];
                    c.booked = true; c.client = name; c.recurring = true; c.na = false;
                });
            }
            closeBookingModal();
            renderWeek();
        }
        function releaseBookingModal() {
            if (!bookingCtx) return;
            const { dateKey, timeSlot, employeeId, truckIndex } = bookingCtx;
            ensureSlotStructure(dateKey, timeSlot);
            const s = bookings[dateKey][timeSlot][employeeId][truckIndex];
            s.booked = false; s.client = ''; s.recurring = false; s.na = false;
            closeBookingModal();
            renderWeek();
        }

        // Fonction pour afficher la semaine
        function renderWeek() {
            const weekDates = getWeekDates(currentDate);
            const weekdaysContainer = document.getElementById('weekdays-container');
            weekdaysContainer.innerHTML = '';
            
            // Mettre à jour l'affichage de la plage de dates
            const startDate = weekDates[0];
            const endDate = weekDates[4];
            const weekRangeText = `${startDate.getDate()} - ${endDate.getDate()} ${startDate.toLocaleDateString('fr-FR', { month: 'long' })} ${startDate.getFullYear()}`;
            document.getElementById('week-range').textContent = weekRangeText;
            updateDateSelectsFromWeek();
            updateDisponibilites(weekDates);

            // Créer une colonne pour chaque jour
            weekDates.forEach((date, index) => {
                const dateKey = getDateKey(date);
                const isToday = date.toDateString() === new Date().toDateString();
                
                const dayColumn = document.createElement('div');
                dayColumn.className = `day-column ${isToday ? 'today' : ''}`;
                
                // En-tête du jour
                const dayHeader = document.createElement('div');
                dayHeader.className = 'day-header';
                dayHeader.innerHTML = `
                    ${formatDate(date).split(' ')[0]} <!-- Jour de la semaine -->
                    <div class="date">${date.getDate()} ${date.toLocaleDateString('fr-FR', { month: 'long' })}</div>
                `;
                
                dayColumn.appendChild(dayHeader);
                
                // Conteneur des créneaux horaires
                const timeSlotsContainer = document.createElement('div');
                timeSlotsContainer.className = 'time-slots-container';
                
                // Ajouter chaque créneau horaire
                timeSlots.forEach(slot => {
                    const timeSlotCell = document.createElement('div');
                    timeSlotCell.className = 'time-slot-cell';
                    
                    // En-tête du créneau
                    const slotTime = document.createElement('div');
                    slotTime.className = 'slot-time';
                    
                    // Calculer le nombre de créneaux pris (réservés + N/A)
                    let takenCount = 0;
                    let totalAvailable = 0;
                    
                    if (bookings[dateKey] && bookings[dateKey][slot.label]) {
                        for (const empId in bookings[dateKey][slot.label]) {
                            if (!employees.find(e => e.id == empId)) continue;
                            const empSlots = bookings[dateKey][slot.label][empId];
                            empSlots.forEach(s => {
                                const o = typeof s === 'object' && s ? s : { booked: !!s, na: false };
                                if (o.booked || o.na) takenCount++;
                            });
                            if (isEmployeeAvailable(parseInt(empId), slot)) totalAvailable += 2;
                        }
                    } else {
                        employees.forEach(emp => { if (isEmployeeAvailable(emp.id, slot)) totalAvailable += 2; });
                    }
                    
                    slotTime.innerHTML = `
                        <span>${slot.label}</span>
                        <span class="slot-status">${takenCount}/${totalAvailable}</span>
                    `;
                    
                    timeSlotCell.appendChild(slotTime);
                    
                    // Conteneur des employés pour ce créneau
                    const employeesSlots = document.createElement('div');
                    employeesSlots.className = 'employees-slots';
                    
                    // Ajouter chaque employé
                    employees.forEach(employee => {
                        const employeeSlot = document.createElement('div');
                        const isAvailable = isEmployeeAvailable(employee.id, slot);
                        employeeSlot.className = `employee-slot ${!isAvailable ? 'employee-unavailable' : ''}`;
                        const c = employee.color || '#003c4b';
                        employeeSlot.style.backgroundColor = hexToRgba(c, 0.22);
                        employeeSlot.style.borderLeft = `4px solid ${c}`;
                        
                        const slotTitle = document.createElement('div');
                        slotTitle.className = 'slot-title';
                        slotTitle.innerHTML = `<span class="employee-name employee-name-colored" style="color:${c}">${employee.name}</span><span>${isAvailable ? 'Disponible' : 'Non-disponible'}</span>`;
                        employeeSlot.appendChild(slotTitle);
                        
                        const truckSlots = document.createElement('div');
                        truckSlots.className = 'truck-slots';
                        
                        for (let i = 0; i < 2; i++) {
                            const truckSlot = document.createElement('div');
                            truckSlot.className = 'truck-slot';
                            let slotState = { booked: false, client: '', recurring: false, na: false };
                            if (bookings[dateKey] && bookings[dateKey][slot.label] && bookings[dateKey][slot.label][employee.id]) {
                                slotState = initSlotState(bookings[dateKey][slot.label][employee.id][i]);
                            }
                            
                            if (!isAvailable) {
                                truckSlot.classList.add('unavailable');
                                truckSlot.textContent = 'N/A';
                            } else if (slotState.na) {
                                truckSlot.classList.add('slot-na');
                                truckSlot.textContent = 'N/A';
                                truckSlot.title = 'Cliquer pour libérer (réactiver le créneau)';
                            } else if (slotState.booked) {
                                if (slotState.recurring) truckSlot.classList.add('booked', 'booked-recurring');
                                else truckSlot.classList.add('booked');
                                truckSlot.textContent = slotState.client || (slotState.recurring ? 'Navette' : 'Réservé');
                                truckSlot.title = 'Cliquer pour modifier la réservation';
                            } else {
                                truckSlot.classList.add('available');
                                truckSlot.textContent = 'Libre';
                                truckSlot.title = 'Cliquer pour réserver ou marquer N/A';
                            }
                            
                            if (isAvailable) {
                                truckSlot.addEventListener('click', () => {
                                    const slotState = (bookings[dateKey] && bookings[dateKey][slot.label] && bookings[dateKey][slot.label][employee.id]) ? initSlotState(bookings[dateKey][slot.label][employee.id][i]) : { booked: false, client: '', recurring: false, na: false };
                                    const dateLabel = formatDate(date);
                                    openBookingModal(dateKey, slot.label, employee.id, i, slotState, dateLabel, employee.name);
                                });
                            }
                            truckSlots.appendChild(truckSlot);
                        }
                        employeeSlot.appendChild(truckSlots);
                        employeesSlots.appendChild(employeeSlot);
                    });
                    
                    timeSlotCell.appendChild(employeesSlots);
                    timeSlotsContainer.appendChild(timeSlotCell);
                });
                
                dayColumn.appendChild(timeSlotsContainer);
                weekdaysContainer.appendChild(dayColumn);
            });
            saveData();
        }

        document.getElementById('prev-week').addEventListener('click', () => { currentDate.setDate(currentDate.getDate() - 7); renderWeek(); });
        document.getElementById('next-week').addEventListener('click', () => { currentDate.setDate(currentDate.getDate() + 7); renderWeek(); });
        document.getElementById('select-month').addEventListener('change', () => { const m = parseInt(document.getElementById('select-month').value, 10); const y = parseInt(document.getElementById('select-year').value, 10); goToMonthYear(m, y); });
        document.getElementById('select-year').addEventListener('change', () => { const m = parseInt(document.getElementById('select-month').value, 10); const y = parseInt(document.getElementById('select-year').value, 10); goToMonthYear(m, y); });

        document.getElementById('modal-schedule-close').addEventListener('click', closeScheduleModal);
        document.getElementById('modal-schedule-cancel').addEventListener('click', closeScheduleModal);
        document.getElementById('modal-schedule-save').addEventListener('click', saveScheduleModal);
        document.getElementById('modal-add-plage').addEventListener('click', () => addPlageRow(document.getElementById('modal-schedule-plages'), '', ''));
        document.getElementById('modal-schedule-overlay').addEventListener('click', (e) => { if (e.target.id === 'modal-schedule-overlay') closeScheduleModal(); });

        document.getElementById('modal-booking-close').addEventListener('click', closeBookingModal);
        document.getElementById('modal-booking-cancel').addEventListener('click', closeBookingModal);
        document.getElementById('modal-booking-overlay').addEventListener('click', (e) => { if (e.target.id === 'modal-booking-overlay') closeBookingModal(); });
        document.getElementById('modal-booking-apply').addEventListener('click', submitBookingModal);
        document.getElementById('modal-booking-save').addEventListener('click', submitBookingModal);
        document.getElementById('modal-booking-release').addEventListener('click', releaseBookingModal);
        document.getElementById('modal-booking-reactivate').addEventListener('click', submitBookingModal);

        document.querySelectorAll('.btn-booking-type').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.btn-booking-type').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                const formReserve = document.querySelector('.booking-form-reserve');
                formReserve.style.display = btn.dataset.type === 'reserve' ? 'block' : 'none';
            });
        });

        document.getElementById('btn-add-employee').addEventListener('click', addEmployee);
        initDateSelects();
        renderEmployeesList();
        renderWeek();
    </script>
</body>
</html>
