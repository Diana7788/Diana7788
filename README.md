```mermaid
graph TD;
    A[Start: Abberufung eines Taus] -->|Initiative durch Tau selbst| B1[TauDashboard öffnen]
    A -->|Initiative durch anderen Tau| B2[Prüfung der Mindestanzahl Taus]

    B2 -->|Mindestens zwei Taus vorhanden| C1[Abberufung möglich]
    B2 -->|Nicht genügend Taus vorhanden| C2[Ernennung eines neuen Taus oder Community-Löschung]

    C1 --> D[Tau wählt „Abberufung“ im TauDashboard]
    D --> E[System fordert Bestätigung]
    E -->|Bestätigung erteilt| F[Tau verliert Tau-Status]
    E -->|Bestätigung nicht erteilt| G[Abbruch der Abberufung]

    F --> H[Tau bleibt als Kappa und Gamma in der Community]
    H --> I[Prozess abgeschlossen]
