# Flight-Reservation-Automation-Framework-using-UFT

🧪 UFT Flight Reservation Automation | Group 4
This repository contains a complete data-driven test automation framework created using Micro Focus UFT (Unified Functional Testing). The test targets the Flight Reservation GUI application and was developed as part of a course assignment at Northeastern University (INFO6255 - Spring 2025).

📌 Features
✅ Data-Driven Testing using Excel input for flight booking

✅ Object Repository to manage test objects

✅ 4 Scenarios tested with varying flight inputs

✅ Screenshots Before and After each booking

✅ 4 Checkpoints (3 Pass, 1 Fail intentionally)

✅ Script is repeatable and live-runnable

✅ Includes Recovery Scenarios for error handling

🛠 Project Structure
php
Copy
Edit
GROUP-4 UFT CODE/
│
├── Default.xlsx             # Excel file with flight booking data
├── Parameters.mtr           # Test parameters for data-driven execution
├── GROUP-4 UFT CODE.usr     # UFT Test File
├── Test.tsp                 # Test settings and recovery scenarios
├── default.cfg, .usp        # Configuration files
│
├── Before/                  # Screenshots before filling flight form
└── After/                   # Screenshots after submitting form
📷 Screenshots
This project captures flight booking screenshots before and after every test to ensure visual verification.

Before/: Screenshots of blank or initial flight booking form

After/: Screenshots after flight form is filled and submitted

🚀 How to Run the Test
Open UFT and select Open Existing Test.

Load the GROUP-4 UFT CODE folder as a test.

Make sure the Flight GUI application is running.

Hit Run.

Observe test output and screenshots.


