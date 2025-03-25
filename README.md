    A[Community vorhanden] -->|Prüfung durch Chaple| B{Löschungs-/Sperrungsgrund?}
    
    B -->|Falsche/fehlende Registrierung| C[Sperrung oder Löschung möglich]
    B -->|Schwerwiegender Verstoß| C
    B -->|12 Monate Inaktivität| C

    C -->|Ja| D[Information der Taus per Mail & ChapleChat]
    D -->|30 Tage Frist zur Stellungnahme| E{Antwort erhalten?}
    
    E -->|Ja, Vorwürfe ausgeräumt| F[Keine Sperrung/Löschung]
    E -->|Nein| G[Sperrung oder Löschung]

    G -->|Sofortige Sperrung (bei Verstoß nach 1 & 2)| H1[Sichtbarkeit in Suche entfernt]
    H1 --> I[Dashboards erreichbar, aber keine Änderungen möglich]

    G -->|Endgültige Löschung (nach 30 Tagen ohne Stellungnahme)| H2[Community & zugehörige Daten gelöscht]
    H2 --> J[Daten bleiben auf Chaple-Server gespeichert]
