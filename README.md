# 📝 Student Registration Form with Google Sheets Integration

This is a basic HTML student registration form that collects the following details:

- Full Name  
- Date of Birth  
- Gender  
- Phone Number  
- Selected Course (BCA, BBA, BSc)

Upon submission, the form data is automatically sent and stored in a linked **Google Sheet** using **Google Apps Script**.

## 🚀 Features

- Simple and clean HTML form (no CSS or JavaScript)
- Real-time data storage in Google Sheets
- Works without any backend server
- Can be used for student data collection in schools, colleges, coaching centers, etc.

## 🔗 How It Works

1. A Google Sheet is created to store form data.
2. A Google Apps Script Web App is deployed to accept POST requests.
3. The HTML form is connected to the Web App URL via the `action` attribute.
4. When users fill out the form and click submit, their data is directly saved into the sheet.

## 📁 Files Included

- `index.html` – The main form page connected to Google Sheets.

## 🛠️ How to Use

1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Fill out the form and submit — the data will be added to your linked Google Sheet.

> ✅ *Make sure to update the `<form action="">` URL with your own Google Apps Script Web App link.*
