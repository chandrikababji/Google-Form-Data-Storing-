Simple Form with CSV Download
This is a simple form built using HTML and JavaScript that allows users to submit their contact information (name, email, and message). The submitted data is stored in the browser's localStorage, and users can download the data as a CSV file (which can be opened in Excel or Google Sheets).

Features
Simple form with fields for Name, Email, and Message.
Submitted data is stored locally in the browser using localStorage.
Option to download the form data as a CSV file.
The form is styled with basic CSS for a clean, responsive layout.
Demo
To see the form in action, simply clone the repository or download the index.html file and open it in your browser. You can fill out the form and click the Download Form Data as CSV button to download the submitted data as a CSV file.

How to Use
Clone the repository or download the HTML file.
Open the index.html file in any modern web browser (Chrome, Firefox, Safari, etc.).
Fill out the form with your details.
Click Submit to save the data.
Click Download Form Data as CSV to download the form submissions as a CSV file.
Files in this repository:
index.html: The HTML file containing the form and JavaScript logic.
README.md: This file, providing project details and usage instructions.
style.css: (Embedded in HTML) Contains the basic styling for the form.
How it Works
1. Form Submission:
When the user submits the form, the form data is captured and stored in localStorage. Each submission adds a new record to the stored data.
2. Download Data:
The "Download Form Data as CSV" button allows users to download all the form submissions as a CSV file, which can be opened in Excel or Google Sheets.
3. CSV Format:
The data is converted into a CSV string and downloaded as a .csv file. Each submission appears as a new row in the CSV file, with the columns representing Name, Email, and Message.
Technologies Used
HTML: Markup language for creating the structure of the form.
CSS: Styling language for the form layout.
JavaScript: Logic for form submission, data storage (localStorage), and CSV file generation.
License
Copyright (c) 2024 Saichandrika Kanaparthi

This project is licensed under the MIT License - see the LICENSE file for details.
Copyright
Copyright (c) 2024 Saichandrika Kanaparthi. All rights reserved.
