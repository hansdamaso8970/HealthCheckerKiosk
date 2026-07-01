Laboratory 5 Activity  
Author: Hans Burton L. Damaso  
Institution: De La Salle University - Dasmariñas, College of Information and Computer Studies (CICS)



About the Project
This web application simulates a walk-in, self-service "Health Self-Check Kiosk" designed for health BMI use. 

Many people lack a quick, private way to check their Body Mass Index (BMI) and receive basic, personalized wellness recommendations without visiting the hospital. 

This kiosk application allows users to securely enter basic physical information, automatically computes their BMI, classifies their health category, and provides tailored wellness advice. Simultaneously, it records every submission to a backend database (Google Sheets) allowing  hospital staff to monitor wellness trends.



Features
Dynamic BMI Calculation: Instantly processes user input (weight and height) to calculate accurate BMI metrics.
Intelligent Categorization: Utilizes JavaScript `switch-case` structures to map the calculated BMI to specific health categories (Underweight, Normal, Overweight, Obese) and returns color-coded UI feedback.
Robust Input Validation: Employs JavaScript loops and `if-else` logic to ensure all form fields are properly filled with valid, non-negative numbers before submission.
Cloud Data Integration: Securely POSTs user data via the `fetch()` API to a custom Google Apps Script Web App, automatically appending records to a Google Sheet.
Responsive UI: Designed with a clean, modern aesthetic utilizing CSS Flexbox, ensuring the application looks great on desktops, tablets, and mobile devices.


Built With
Frontend: HTML5, CSS3, JavaScript 
Backend / Database: Google Apps Script, Google Sheets 
Deployment: GitHub 
