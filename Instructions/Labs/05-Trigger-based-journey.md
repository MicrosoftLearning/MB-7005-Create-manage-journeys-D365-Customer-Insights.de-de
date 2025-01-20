---
lab:
  title: 'Lab 4: Erstellen einer triggerbasierten Journey'
---

## Lab 4: Erstellen einer triggerbasierten Journey 

In diesem Lab lernen Sie Folgendes:
- Erstellen einer Journey basierend auf einem Trigger
- Definieren von Beendigungskriterien für das Segment 

### Aufgabe 1: Erstellen einer triggerbasierten Journey 
1. Navigieren Sie zum Arbeitsbereich **Echtzeitjourneys**.

1. Wählen Sie unter **Engagement** die Option **Journeys.**.

1. Klicken Sie in der Befehlsleiste auf **+ Neue Journey**.

1. Wählen Sie **Überspringen und ohne Vorlage erstellen** aus.

1. Geben Sie in **Journey benennen** den Namen **Welcome Journey** ein.

1. Wählen Sie unter **Journeytyp auswählen** die Option **Trigger-basiert**.

1. Suchen Sie unter **Trigger auswählen** nach **Kontakt erstellt**, und wählen Sie diese Option aus.

1. Klicken Sie auf **Erstellen**.

1. Wählen Sie in den Journeyeinstellungen auf der rechten Seite im Eintragsabschnitt **Bedingung hinzufügen** aus.

1. Wählen Sie im Dropdownmenü „Attribut“ die Option **Kontakt erstellt > Kontakt (Kontakt) > Konto (Konto) > Kontoname** aus.

1. Ändern Sie den Operator in **Ist nicht gleich**.

1. Legen Sie den Wert auf **Humongous Insurance** fest. Die Bedingung sollte **Kontoname Ist nicht gleich Humongous Insurance** lauten.

1. Konfigurieren Sie die restlichen Elemente im Eintragsabschnitt wie folgt:
    - Wählen Sie im Abschnitt **Wiederholen** die Option „Sofort“.
    - Im Abschnitt Zeitzone wählen Sie Ihre Zeitzone.
    - Wählen Sie in „Start“ die Option „15 Minuten ab jetzt“ aus.
    - Unter Ende, wählen Sie „morgen“ aus.

### Aufgabe 2: Definieren des Journeyziels
Als Nächstes können wir das spezifische Ziel der Customer Journey identifizieren.  Ziele helfen dabei, zu ermitteln, was der Endpunkt der Journey ist.  Dabei kann es sich um Dinge wie das Fördern eines Kaufs oder die Interaktion mit Kunden sein.  Durch die Angebe eines Ziels für die Journey wird sichergestellt, dass die Journey beendet wird, sobald Ihr Ziel erreicht wurde.    

Für diese Journey suchen wir nach einem bestimmten Prozentsatz von Personen, die wir zum Klicken auf einen Link auffordern, der in einer E-Mail enthalten ist, die wir ihnen senden.  

1.  Navigieren Sie in den Journeyeinstellungen auf der rechten Seite zum Abschnitt **Ziel**.

1.  In **Das Ziel dieser Journey ist**, wählen Sie **Eine allgemeine Benachrichtigung zu senden**.

1.  Wählen Sie in **Das Ziel ist erreicht, wenn** die Option **Mindestens eine Person auf einen Link geklickt hat** aus.

1.  In **Die Anzahl der benötigten Personen,** geben Sie **50** ein. Lassen Sie die Option **Prozent** ausgewählt. 

### Aufgabe 3: Definieren einer Häufigkeitsobergrenze für die Journey 
Contoso möchte sicherstellen, dass sie ihre Kunden nicht zu viele Werbenachrichten senden. Um sicherzustellen, dass dies nicht geschieht, möchten sie eine Häufigkeitsobergrenze auf diese Journey anwenden.   

1.  Navigieren Sie in den Journeyeinstellungen auf der rechten Seite zum Abschnitt **Andere Einstellungen**.

1.  Vergewissern Sie sich unter „Häufigkeitsobergrenze“, dass **Häufigkeitsobergrenze auf diese Journey anwenden – Werbenachrichten überspringen, wenn die Obergrenze erreicht ist** ausgewählt ist.  

1.  Wählen Sie unter „Maximale Häufigkeit für Journeys“ die Option **Zu den Einstellungen für Häufigkeitsobergrenzen wechseln** aus. Ein neues Fenster wird geöffnet.

1.  Wählen Sie auf der Befehlsleiste **+Neue Einstellung** aus.

1.  Geben Sie in das Feld „Name“ den Namen **Contoso** ein.

1.  Legen Sie im Abschnitt „Maximale Häufigkeit pro Kontaktpunkt“ die Konfiguration basierend auf der folgenden Abbildung fest:

    ![Screenshot der Einstellungen für die Häufigkeitsobergrenze, wobei „E-Mail“ auf „Täglich 3“ und „Monatlich 10“ und „SMS“ auf „Täglich 1“, „Wöchentlich 2“ und „Monatlich 3“ festgelegt ist. Für Pushbenachrichtigungen ist nichts festgelegt.](../Labs/Media/frequency-cap.png)

1. Wählen Sie **Speichern und schließen** aus, um Ihre neuen Einstellungen für Häufigkeitsobergrenzen zu speichern und zu schließen.  

1.  Kehren Sie zum Fenster zurück, das Ihre Willkommens-Journey enthält. **Speichern** Sie die Journey, und aktualisieren Sie Ihren Browser.

1.  Navigieren Sie in den Journeyeinstellungen auf der rechten Seite erneut zum Abschnitt **Andere Einstellungen**.

1.  Beachten Sie, dass die Häufigkeitsobergrenze für Contoso jetzt auf diese Journey angewendet wird.  

### Aufgabe 4: Erstellen der triggerbasierten Journey 
Nachdem wir nun die erforderlichen Journeykriterien definiert haben, besteht der nächste Schritt darin, die tatsächlichen Schritte der Journey zu erstellen. 

1. Klicken Sie im Journey-Designer auf das **Plus-Symbol (+)** unter der Kachel „Kontakt erstellt“.

1. Wählen Sie **Attribut-Zweig (Zweig basiert auf einem bestimmten Wert)** aus.

1. Geben Sie in „Anzeigename“ auf der rechten Seite **New Business Customer** ein.

1. Wählen Sie **Verzweigung 1** aus, und suchen Sie dann in **Attribut auswählen** unter „Kontakt“ nach **Beschreibung (Beschreibung)**.

1. Ändern Sie den Wert von „Ist gleich“ in **Enthält**.

1. Geben Sie in „Wert“ den Wert **Business** ein.

1. Klicken Sie auf das **Plus-Symbol (+)** unter „Verzweigung 1“.

1. Wählen Sie **E-Mail: E-Mail senden** aus.

1. Wählen Sie in **E-Mail auswählen** die Option **Willkommens-E-Mail 1** aus.

1. Klicken Sie auf das **Plus-Symbol (+)** unter der Kachel „E-Mail senden“.

1. Wählen Sie **Auf Trigger warten** aus.

1. Um die Falls/dann-Verzweigung zu konfigurieren, wählen Sie im Bereich „Falls/dann“ auf der rechten Seite unter „Warten auf“ einen Verzweigungsbedingungstyp und die Option „Die vorherige Nachricht erhält eine Interaktion“ aus.

1. Wählen Sie unter **Interaktion auswählen** die Option **E-Mail-Link angeklickt**.

1. Geben Sie bei **Was ist das Zeitlimit?**, „10 Minuten“ ein.

1. Wählen Sie im Diagramm „Journey“ die Option **Verzweigungen erstellen** aus, um den Link anzugeben, auf den geklickt wurde.

1. Wählen Sie das Attribut **E-Mail-Link angeklickt** aus.

1. Wählen Sie in „Verzweigung 1“ die Schaltfläche „Handlungsaufruf“ aus der E-Mail aus.

1. Klicken Sie im Pfad „Ja“ auf das **Plussymbol (+)**.

1. Wählen Sie **E-Mail senden** aus.

1. Wählen Sie in „E-Mail auswählen“ die Option **Willkommens-E-Mail 2** aus.

1. Klicken Sie im entsprechenden Pfad „Nein“ auf das **Plussymbol (+)**.

1. Wählen Sie **E-Mail senden** aus.

1. Wählen Sie in „E-Mail auswählen“ die Option **Willkommens-E-Mail 3** aus.

1. Speichern Sie die Journey.

1. Überprüfen Sie die Journey. Nehmen Sie ggf. letzte Änderungen vor.

1. Klicken Sie auf **Veröffentlichen**. Warten Sie, bis die Journey veröffentlicht wurde.


