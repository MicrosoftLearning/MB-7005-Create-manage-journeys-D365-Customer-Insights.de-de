---
lab:
  title: 'Lab 1: Erstellen von E-Mails'
---

## Lab 1: Erstellen von E-Mails 

In diesem Lab lernen Sie Folgendes:
- Erstellen von E-Mails zur Verwendung in einer Journey
- Verwenden von hochgeladenen Ressourcen in einer E-Mail
- Überprüfen Ihrer E-Mail-Inhalte und live gehen

### Aufgabe 1: Erstellen Ihrer ersten E-Mail
1. Melden Sie sich bei Dynamics 365 Customer Insights - Journeys an.

1. Navigieren Sie zum Arbeitsbereich **Echtzeitjourneys**.

1. Wählen Sie unter „Kanäle“ die Option **E-Mails** aus.

1. Erstellen Sie die E-Mail.
   - Klicken Sie auf **+ Neu**, um eine neue E-Mail zu erstellen.
   - Wählen Sie im Vorlagenkatalog **Überspringen** aus.

1. Geben Sie Details zur E-Mail ein.
   - Name: Willkommens-E-Mail 1
   - Betreff: Willkommen bei Contoso Insurance
   - Vorschautext: Wir verpflichten uns, Ihnen eine hochwertige Versicherung anzubieten.

1. Wählen Sie das Standardbrandprofil als Markenprofil aus.

1. Navigieren Sie zu **Einstellungen** und erweitern Sie **Compliance**. Stellen Sie sicher, dass der Zweck auf **Kommerziell** festgelegt ist.

1. Entwerfen Sie die E-Mail. Im Screenshot der Willkommens-E-Mail 1 unten finden Sie Design- und Inhaltsideen mithilfe des Hero-Bilds, das Sie in den Setupanweisungen hochgeladen haben. Sie können die Bilder und Inhalte nach Bedarf ändern, aber Sie sollten eine Interaktive Schaltfläche in diese E-Mail integrieren, da sie innerhalb der Journey als Verzweigungskriterium verwendet wird.

    ![Screenshot von Willkommens-E-Mail 1.](../Labs/Media/welcome-email-1-example.png) 

1. Hier ist eine Beispielkopie für diese E-Mail. Sie können sie kopieren und in Ihr E-Mail-Design einfügen. Verwenden Sie **Personalisierung**, um dynamische Inhalte für den Vornamen des Kontakts einzugeben. 

    ```
    {{FirstName}},
    
    Thank you for putting your trust in Contoso Insurance. We're honored to have you as a customer and look forward to building a lasting relationship with you. 
 
    As America's \#1 insurance company, we're committed to providing quality insurance that protects all aspects of your business. 
 
    We've put together a welcome kit that provides insight about our agency, advises on what to do if you need to report a claim, and provides our staff's direct contact information. Use the link below to download it. 
 
    Feel free to contact us any time at 888-888-8888 with any questions you have. And don't forget to download our mobile app where you can view your account history, pay your bill, and more. 
    ```

1. Fügen Sie eine Schaltfläche zur E-Mail hinzu. 

    - Wählen Sie in der Toolbox die Registerkarte **Elemente** aus. 
    - Ziehen Sie eine Schaltfläche unter den Haupttext. 
    - Ändern Sie die URL in contoso.com. 
    - Erweitern Sie den Abschnitt „Stil“. 
    - Ändern Sie die Schaltflächenfarbe in #0076ad. 

1.  Anzeigen, Testen und Live-Live mit Ihrer E-Mail. 

    - Navigieren Sie zur Registerkarte **Vorschau und Test** Ihrer E-Mails, um Ihre E-Mails zu überprüfen. 
    - Verwenden Sie **Test senden**, um sich selbst eine Kopie zu senden. Geben Sie Ihre persönliche E-Mail-Adresse ein. Wählen Sie den zuvor erstellten Kontakt aus – die Personalisierung füllt den Vornamen dieses Kontakts aus. Prüfen Sie Ihren Junk-E-Mail-Ordner, wenn Sie die E-Mail nicht in Ihrem Posteingang finden. 
    - Nehmen Sie ggf. letzte Änderungen vor. 
    - Klicken Sie auf **Inhalt prüfen**. Korrigieren Sie eventuelle Fehler. 
    - Klicken Sie auf **Bereit zum Senden**. 

### Aufgabe 2: Erstellen Ihrer zweiten E-Mail
Wir werden zwei weitere E-Mails erstellen, indem wir die soeben erstellte E-Mail kopieren.

1. Während die Willkommens-E-Mail 1 geöffnet ist, klicken Sie auf die Dropdownliste neben **Speichern** und wählen Sie dann **Speichern unter** aus.

1. Aktualisieren Sie den Namen der E-Mail auf **Willkommens-E-Mail 2**. 

1. Klicken Sie auf **Speichern und schließen**.

1. Wählen Sie im Popup **Datensatz anzeigen** aus, um zu Ihrer neu erstellten E-Mail zu wechseln. (Wenn das Popup nicht angezeigt wird, wechseln Sie zu **E-Mails** und wählen Sie **Willkommens-E-Mail 2** aus.)

1. Ändern Sie den Betreff und den Vorschautext.
    - Vorgeschlagenes **Thema:** Erhalten Sie On-Demand-Zugriff auf Ihr Contoso Insurance-Portal.
    - Vorgeschlagener **Vorschautext:** Überprüfen Sie Kontoinformationen, Richtliniendetails, übermitteln Sie einen Anspruch und vieles mehr.

1. Entwerfen Sie die E-Mail. Im Screenshot der Willkommens-E-Mail 2 unten finden Sie Design- und Inhaltsideen. Sie können die Bilder und Inhalte nach Bedarf ändern. 

    ![Screenshot der Willkommens-E-Mail 2.](../Labs/Media/welcome-email-2-example.png) 

1. Hier sehen Sie eine Beispielkopie für diese E-Mail. Sie können sie kopieren und in Ihr E-Mail-Design einfügen. (Hinweis: Wir empfehlen, FirstName aus der ersten E-Mail beizubehalten und dann den Rest der Kopie damit zu ersetzen.) 

    ```
    I would like to welcome you to the Contoso family! Our specialists are here to help you with all your insurance needs. We also encourage you to setup your Contoso Insurance online account to gain 24/7 access to:  
        -   Your account information and policy details. 
        -   Submit a request for coverage verification, start a claim, or review prior claims. 
        -   A secure and encrypted internal messaging tool for sharing sensitive information. 
    Feel free to contact me with any questions you have. 
        
    Cheers, 
    John Smith, Insurance Specialist   jsmith@contosoinsurance.com 
    888-888-8888 

1. Preview, test, and go live with your email.

### Task 3: Create your third email
We will create one final email by copying email 2.

1. Create a new email by copying email 2. Name the email Welcome email 3. 

1. Enter details about the email.
    - Suggested **Subject:** Welcome to Contoso
    - Suggested **Preview text:** Review your welcome information.

1. Design the email. Refer to the screenshot of Welcome Email 3 below for design and content ideas. You can modify the images and content as desired. 

    ![Screenshot of Welcome Email 3.](../Labs/Media/welcome-email-3-example.png) 

1. Here is sample copy for this email. You can copy and paste this into your email design. (Note: We recommend leaving FirstName from the first email and then replacing the rest of the copy with this.) 

    ```
    Vielen Dank, dass Sie Ihr Vertrauen in Contoso Insurance setzen. Ich fühle mich geehrt, Sie als Kunden zu haben und freue mich auf eine dauerhafte Zusammenarbeit mit Ihnen. Ihr Willkommenskit bietet Einblicke in unsere Agentur, berät darüber, was Sie tun müssen, wenn Sie einen Anspruch melden müssen, und stellt die direkten Kontaktinformationen unserer Mitarbeiter zur Verfügung. 

    Verwenden Sie den nachstehenden Link, um das Kit von unserer Website herunterzuladen.
    
    Wenn Sie weitere Fragen haben, wenden Sie sich bitte an mich. Cheers, John Smith, Versicherungsspezialist jsmith@contosoinsurance.com888-888-8888
    ```

1. Update the button in the email. In the **Button text** field, change it to **Click here for the welcome kit.**

1. Preview, test, and go live with your email.
