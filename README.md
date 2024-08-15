# Patient-Health-Tracker

The Patient Health Tracker is a comprehensive web-based application designed to optimize the management of patient and doctor information within a healthcare environment. Leveraging modern web technologies, this application provides healthcare professionals with a secure, intuitive interface to manage critical medical data efficiently.

### Key Features:

- __User Authentication:__ Secure login system ensuring that only authorized personnel can access sensitive healthcare data.
- __Data Management:__ Seamless addition, viewing, and management of doctor and patient information, including assignment of doctors to patients.
- __Administrative Efficiency:__ Enhances the efficiency of healthcare administration through a user-friendly platform that simplifies the management of medical records.

### Application Structure:
The Patient Health Tracker is organized into several key modules, each serving a specific function:

- __Login Module:__ Secure entry point for the application, ensuring only verified users can access the system.
- __Doctor Management:__
  - __Doctor List Page:__ Displays a comprehensive list of doctors along with their specializations.
   - __Add Doctor Form:__ Interface for adding new doctors to the system.
3 __Patient Management:__
         3.1 __Patient List Page:__ Provides a detailed list of patients, including their medical information and assigned doctors.
          3.2 __Add Patient Form:__ Interface for adding new patients, complete with relevant medical and personal details.
4 __Dashboard:__
A centralized hub for navigating between different functionalities, such as viewing lists or adding new records.
5  __Client-Side Validation:__

Scripts to validate user inputs in real-time before form submission, enhancing data integrity and user experience.

### Installation Guide:

To set up and run the Patient Health Tracker locally, follow these steps:

- __Clone the Repository:__
git clone https://github.com/your-username/patient-health-tracker.git
- __Navigate to the Project Directory:__ <br>

                       - bash
                       - Copy code
                       - cd patient-health-tracker
- __Database Setup:__
- Import the provided SQL file into your MySQL database.
- Update the database connection details in the config.php file.
- Run the Application:
- Start your local server (e.g., XAMPP, WAMP).
- Access the application via http://localhost/patient-health-tracker.
- Usage Instructions:

- __Login:__
- Access the login page at http://localhost/patient-health-tracker/login.php.
- Enter your credentials to gain access to the dashboard.
- __Navigating the Dashboard:__

From the dashboard, easily navigate to add new doctors, add new patients, or view existing records.
- __Adding a Doctor/Patient:__

Use the respective forms to input new doctor or patient information into the system.
- __Screenshots:__
  ![login dashboard](https://github.com/user-attachments/assets/4428f87f-9d8c-46fb-99e7-2460d76f769c)
 
 ![AddForm](https://github.com/user-attachments/assets/4a3b6f14-72ae-42bc-9508-ee2db2840b4c)
 
 ![List](https://github.com/user-attachments/assets/95091f92-7421-4fb1-8505-39be924bc0d6)


### Conclusion:
The Patient Health Tracker showcases the potential of web technologies to streamline healthcare administration. With its secure, user-friendly interface and robust functionality, it serves as an essential tool for healthcare professionals aiming to manage patient and doctor data more effectively.

### License:
 This project is licensed under the MIT License.
