🧹 Data Cleansing Software
A high-performance, web-based tool for cleaning, validating, and transforming datasets instantly.
Status: v1.0.0 | License: MIT | Build: Passing
📌 Project Overview
This software provides a streamlined interface for processing large Excel (.xlsx) and CSV files. It
enables users to apply complex cleansing rules—ranging from text normalization to date
standardization—without writing a single line of code.
🚀 Key Features
Text Cleansing: Trim leading/trailing spaces, collapse extra spaces, and perform case
conversions (UPPER, lower, Title).
Date Normalization: Standardize inconsistent date columns to DD-MM-YYYY , DD-MM-YY , or
DD-MMM-YYYY .
Numeric Formatting: Remove currency symbols, fix decimal places, and enforce value
ranges (Cap/Floor).
Validation Rules: Automated email validation, phone number standardization, and mandatory
field checks.
Advanced Tools: Duplicate detection, find & replace (with Regex support), and HTML tag
stripping.
Blueprint Tracking: Live sidebar summary of all active rules applied to the current session.
🛠️ Installation & Setup
This is a standalone client-side application. No server installation is required.
•
•
•
•
•
•
# Clone the repository
git clone https://github.com/yourusername/data-cleansing-software.git
📖 Usage Guide
Upload: Drag and drop your .xlsx or .csv file into the upload zone.
Configure: Use the sidebar navigation to select cleansing rules. Toggle cards to customize
specific column targeting.
Preview: Click "Run Cleanse & Preview" to see the first 100 rows and a summary
of issues found.
Export: Download your cleaned dataset as a professional Excel file or standard CSV.
⚙️ Tech Stack
Frontend: HTML5, CSS3 (Modern Flexbox/Grid)
Logic: Vanilla JavaScript (ES6+)
Libraries: SheetJS (XLSX.js) for file parsing and generation.
Fonts: Space Grotesk & JetBrains Mono via Google Fonts.
🤝 Contributing
Contributions are welcome! Please follow these steps:
Fork the project.
Create your feature branch ( git checkout -b feature/AmazingFeature ).
Commit your changes ( git commit -m 'Add some AmazingFeature' ).
Push to the branch ( git push origin feature/AmazingFeature ).
Open a Pull Request.
# Navigate to the project folder
cd data-cleansing-software
# Open the main file in your browser
open Data_Cleansing_Software.html
1.
2.
3.
4.
•
•
•
•
•
•
•
•
•
