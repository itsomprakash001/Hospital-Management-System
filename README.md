# Hospital Management System
Hospital Management System using MySQL, Php and Bootstrap
Need to work on:
1. Ability to accept the appointment by the doctor to acknowledge the patient that their appointment has been approved.
2. User should not be allowed to register if he/she tries to provide the already registered email ID.
3. The password should be encrypted and the password field shouldn't be displayed in the admin panel.
4. Implementation of pagination for all the list view across the application.
5. Bug fix - Bill payment receipt contains multiple record if the patient has associated with the same doctor multiple times.
6. Addition of more fields in the prescription statement to make it more specific one.
7. Addition of more details on payment - such as date of the payment made, amount paid, etc.
8. Implementation of export button in admin module to export all details to an excel sheet.

Prerequisites:
1. Install XAMPP web server
2. Any Editor (Preferably VS Code or Sublime Text)
3. Any web browser with latest version

Languages and Technologies used:
1. HTML5/CSS3
2. JavaScript (to create dynamically updating content)
3. Bootstrap (An HTML, CSS, and JS library)
4. XAMPP (A web server by Apache Friends)
5. Php
6. MySQL (An RDBMS that uses SQL)
7. TCPDF (to generate PDFs)

Steps to run the project in your machine:
1. Download and install XAMPP in your machine.
2. Clone or download the repository.
3. Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4. Start the Apache and Mysql in your XAMPP control panel.
5. Open your web browser and type 'localhost/phpmyadmin'
6. In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7. Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8. Open a new tab and type 'localhost/foldername' in the url of your browser.

GETTING INTO THE PROJECT:
Hospital Management System in php and mysql. This system has a ‘Home’ page from where the patient, doctor & administrator can login into their accounts by toggling the tabs accordingly. Fig 1.1 shows the ‘Home’ page of our project.
![Screenshot 2025-04-29 140134](https://github.com/user-attachments/assets/dc8493ee-0a5e-49ab-807b-e1e57f9079ac)

'About Us' page (Fig 1.2) allows us to get some more information about the quality and the services of the hospital.
![Screenshot 2025-04-29 140539](https://github.com/user-attachments/assets/9a27ab9a-9048-4b9e-914c-f82470da4fc7)

‘Contact’ page allows users to provide feedback or queries about the services of the hospital. Fig 1.3 shows the ‘Contact’ page.
![Screenshot 2025-04-29 141008](https://github.com/user-attachments/assets/d0c5d46f-7007-435f-b016-7bdd947e5fc1)

The ‘Home’ page consists of 3 modules:

1.Patient Module
2.Doctor Module
3.Admin Module

1.Patient Module:
This module allows patients to create their account, book an appointment to see a doctor and see their appointment history. The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.
![Screenshot 2025-04-29 141501](https://github.com/user-attachments/assets/676525f2-6862-45c6-b0f0-a930b69a01b6)

2.Doctor Module:
The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’. Fig 1.10 shows the login form for a doctor. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.
![Screenshot 2025-04-29 141818](https://github.com/user-attachments/assets/36519aa8-9f15-4837-beba-d91e93c23038)

3.Admin Module:
This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too.       Login into admin account can be done by toggling into admin tab of the Home page. Fig 1.13 shows the login page for admin. 
![Screenshot 2025-04-29 141818](https://github.com/user-attachments/assets/e1a8de0f-baba-457a-9659-45c67326134f)
