# 📧 Email Automation Using Python

An automated email sender built with Python to send bulk emails at a scheduled time using data from an Excel file. This project simplifies email marketing and notification systems by automating the process of sending personalized emails to multiple recipients.

---

## 🚀 Features

- ✅ Send **bulk emails** using SMTP protocol  
- ✅ Extract **user data and message content** from Excel sheets using `pandas`  
- ✅ Schedule emails with `schedule` and `time` modules  
- ✅ Text-to-speech feedback using `pyttsx3`  
- ✅ GUI interface built with `Tkinter`  
- ✅ Secure credentials using `python-dotenv`  
- ✅ Supports **HTML-formatted email content** and attachments (optional)  

---

## 🧰 Tech Stack / Libraries Used

- `smtplib` – for sending emails via SMTP  
- `pandas` – to read recipient data and email content from Excel  
- `numpy` – for data handling (optional use)  
- `pyttsx3` – to give voice alerts  
- `Tkinter` – for GUI interface  
- `dotenv` – to securely manage email credentials  
- `schedule` & `time` – for scheduling emails

---

3. **Schedule & Send**  
Using the GUI or script, select the Excel file and set the desired time. The emails will be sent automatically using the SMTP server (e.g., Gmail).

---

## 💡 Use Cases

- Email marketing campaigns  
- Event announcements  
- Academic or corporate bulk communication  
- Scheduled newsletters  

---

## 🔐 Security Note

- Your credentials are stored securely using environment variables.
- Make sure to enable **"Less Secure App Access"** if using Gmail (or set up App Passwords).




