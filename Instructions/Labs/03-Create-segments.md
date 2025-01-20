---
lab:
  title: '2Lab: Erstellen von Segmenten'
---

## 2Lab: Erstellen von Segmenten 

In diesem Lab lernen Sie Folgendes:
- Aktualisieren von Informationen zu Kundendatensätzen
- Segment erstellen 

### Aufgabe 1: Aktualisieren der Stadt für verschiedene Kunden

Eine der Journeys richtet sich an Kunden, die in einer bestimmten Stadt leben. Um sicherzustellen, dass Sie Mitglieder in diesem Segment haben, müssen wir allen derzeit vorhandenen Kontakten eine Stadt hinzufügen.

1. Melden Sie sich bei **Dynamics 365 Customer Insights - Journeys** an. Vergewissern Sie sich, dass Sie sich im Bereich **Echtzeitjourneys** befinden.

1. Wählen Sie unter „Zielgruppe“ die Option **Kontakte** aus.

1. Wählen Sie den ersten 10 Kontakte in der Liste aus. 

1. Klicken Sie auf der Befehlsleiste auf **Bearbeiten**.

1. Geben Sie im Feld „Adresse 1: Ort“ die Stadt **Seattle** ein.

1. Wählen Sie die Schaltfläche **Speichern** aus.

1. Wählen Sie die nächsten 50 Kontakte in der Liste aus.

1. Klicken Sie auf der Befehlsleiste auf **Bearbeiten**.

1. Geben Sie im Feld „Adresse 1: Ort“ die Stadt **Portland** ein.

1. Wählen Sie die Schaltfläche **Speichern** aus.

1. Wählen Sie die nächsten 10 Kontakte in der Liste aus.

1. Klicken Sie auf der Befehlsleiste auf **Bearbeiten**.

1. Geben Sie im Feld „Adresse 1: Ort“ die Stadt **Boise** ein.

1. Wählen Sie die Schaltfläche **Speichern** aus.

1. Wählen Sie die nächsten 10 Kontakte in der Liste aus.

1. Klicken Sie auf der Befehlsleiste auf **Bearbeiten**.

1. Geben Sie im Feld „Adresse 1: Ort“ die Stadt **Seattle** ein.

1. Wechseln Sie zur Registerkarte **Details**. Geben Sie im Textfeld unter **Persönliche Notizen** das Wort **Business** ein.

1. Wählen Sie die Schaltfläche **Speichern** aus.

### Aufgabe 2: Erstellen eines Segments für Humongous Insurance-Kunden

1. Navigieren Sie unter der Gruppe „Zielgruppe“ zu **Segmente**.

1. Wählen Sie **+Neues Segment** aus.

1. Geben Sie im Feld **Segmentname** die Zeichenfolge **Humongous Insurance** ein. Wählen Sie **Kontakt** als Zielgruppe aus. Klicken Sie auf **Erstellen**.

1. Wählen Sie im Segment-Designer **Neue Gruppe hinzufügen** aus. Zuerst wählen wir eine **Attributgruppe** aus.

1. Erweitern Sie im Bereich „Attribute“ den Eintrag **Kontakt**, und wählen Sie **Konto** aus. Fügen Sie das Element zur vorhandenen Gruppe hinzu.

1. Wählen Sie in der Suche in Gruppe 1 **Humongous Insurance** aus. Die Bedingung „Gruppe 1“ lautet „Konto Ist Humongous Insurance“.

1. Wir möchten dem Segment eine weitere Bedingung hinzufügen. Wählen Sie **+Neu hinzufügen** aus, um eine neue Gruppe hinzuzufügen, und wählen Sie **Attributgruppe** aus.

1. Ändern Sie den Operator in **oder**.
    - Beginnen Sie im Bereich „Attribut“ mit der Eingabe von **E-Mail**. Erweitern Sie **Kontakt**. Klicken Sie auf die Schaltfläche **Plus** neben dem E-Mail-Feld, und fügen Sie es der Gruppe 2 hinzu.
    - Erstellen Sie die folgende Bedingung: **E-Mail enthält humongousinsurance**

1. Wählen Sie **Speichern**.

1. Wählen Sie auf der Symbolleiste **Sofort einsatzbereit** aus.

1. Wählen Sie die Registerkarte **Mitglieder und Erkenntnisse** aus. Überprüfen Sie, ob Kontakte mit einer Humongous Insurance-E-Mail-Adresse oder einem Humongous-Firmennamen angezeigt werden. Möglicherweise müssen Sie aktualisieren oder einige Minuten warten, bevor die Kontakte angezeigt werden.

### Aufgabe 3: Erstellen eines Geschäftskundensegments

1. Navigieren Sie unter der Gruppe „Zielgruppe“ zu **Segmente**.

1. Wählen Sie **+Neues Segment** aus.

1. Benennen Sie das Segment **Business Customers**. Lassen Sie **Kontakt** als Zielgruppe ausgewählt. Klicken Sie auf **Erstellen**.

1. Erweitern Sie im Bereich **Attribute** den Eintrag **Kontakt**, und wählen Sie **Konto** aus. Fügen Sie das Element zur vorhandenen Gruppe hinzu.

1. Wählen Sie in der Suche in Gruppe 1 **Contoso, Ltd.** aus.

1. Klicken Sie auf **Speichern**, und wählen Sie **Sofort einsatzbereit** aus.

1. Warten Sie, bis Ihr Segment erstellt wurde.

1. Wählen Sie die Registerkarte **Mitglieder und Erkenntnisse** aus, um Ihre Segmentmitglieder anzuzeigen.

### Aufgabe 4: Erstellen eines Contoso-Segments  
2.  Navigieren Sie unter der Gruppe „Zielgruppe“ zu **Segmente**. 

3.  Wählen Sie „+Neues Segment“ aus. **

4.  Benennen Sie das Segment **Contoso Customers**. Lassen Sie **Kontakt** als Zielgruppe ausgewählt. Klicken Sie auf **Erstellen**.

5.  Fügen Sie eine neue Gruppe hinzu, und wählen Sie **Attributgruppe erstellen** aus. Erweitern Sie im Bereich **Attribute** den Eintrag **Kontakt**, und fügen Sie **Beschreibung** zur Gruppe 1 hinzu. 

6.  Ändern Sie im Segment-Designer den Qualifizierer in **Enthält**. Geben Sie als Wert **Business** ein.

7.  Klicken Sie auf **Speichern**, und wählen Sie **Sofort einsatzbereit** aus. 

8.  Warten Sie, bis Ihr Segment erstellt wurde. 

9.  Wählen Sie die Registerkarte **Mitglieder und Erkenntnisse** aus, um Ihre Segmentmitglieder anzuzeigen. 


### Aufgabe 5: Erstellen eines Kundensegments für Seattle
1. Navigieren Sie unter der Gruppe „Zielgruppe“ zu „Segmente“.

1. Wählen Sie **+Neues Segment** aus.

1. Benennen Sie das Segment **Seattle Customers**. Lassen Sie **Kontakt** als Zielgruppe ausgewählt.

1. Wählen Sie die Schaltfläche **Erstellen**.

1. Fügen Sie eine neue Gruppe hinzu, und wählen Sie **Attributgruppe erstellen** aus. Erweitern Sie im Bereich „Attribute“ den Eintrag **Kontakt > Adresse 1**, und fügen Sie **Adresse 1: Ort** zur Gruppe 1 hinzu.

1. Ändern Sie im Segment-Designer den Qualifizierer nicht. Geben Sie als Wert **Seattle** ein.

1. Klicken Sie auf **Speichern**, und wählen Sie **Sofort einsatzbereit** aus.

1. Warten Sie, bis Ihr Segment erstellt wurde.

1. Wählen Sie die Registerkarte **Mitglieder und Erkenntnisse** aus, um Ihre Segmentmitglieder anzuzeigen.
