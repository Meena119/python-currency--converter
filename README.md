# 🌍 Currency Converter (Tkinter + Real-Time API)

A Python desktop application that allows users to convert between different currencies using real-time exchange rates. It includes features such as automatic country detection, flag display, searchable dropdowns, conversion history export, and a user-friendly GUI built with Tkinter.

---

## 🚀 Features

- 🔁 Convert between **150+ currencies** using real-time data
- 🌐 **Auto-detects your local currency** based on your IP address
- 🔎 **Searchable dropdowns** with currency codes and full names
- 🏳️ Displays **country flags** for source and target currencies
- 📅 Choose a **custom date** for historical exchange rates
- 💾 Export your conversion history to a **CSV file**
- 🔄 Quickly **switch** "From" and "To" currencies with one click
- 🛡️ Handles errors and API failures gracefully

---

## 🖼️ Screenshots

![Screenshot 2025-06-16 135528](https://github.com/user-attachments/assets/b2fe59ef-f476-4782-ac8a-a49f480694c8)


## 🛠️ Installation


### 📦 Requirements

Install all dependencies using pip:

```bash
pip install requests pillow tkcalendar pycountry geocoder
Python 3.x

Tkinter – GUI framework

Frankfurter API – Real-time exchange rates

PyCountry – Currency metadata

Geocoder – IP-based location detection

Pillow – For flag image handling

Tkcalendar – Date picker widget

python currency_converter.py

📁 Project Structure
Edit
.
├── currency_converter.py   # Main Python script

├── README.md               # Project documentation

└── screenshots/            # (Optional) UI screenshots for GitHub

📤 Export Format
You can export your conversion history as a .csv file. The exported file will contain:

Amount	From	Converted	To	Date

📌 To-Do / Optional Features
 Add dark mode

 Add favorites dropdown for frequent conversions

 Export history as PDF

 Build as .exe desktop app

 Add multi-currency rate table view

🙌 Acknowledgements
Frankfurter Exchange Rate API

FlagCDN for country flags

Tkinter + Python community

💬 Feedback
Feel free to fork, open issues, or submit pull requests!









