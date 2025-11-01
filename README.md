# 📧 Gmail OTP Forwarder — Visual Demo

This is a **front-end simulation** of the Gmail OTP Forwarder concept.  
It visually shows how the real C# service works — detecting OTP codes in incoming emails and saving them to a database.

---

## 🌟 What this demo does

✅ Simulates incoming Gmail messages  
✅ Detects One-Time Passwords (4–8 digits) automatically  
✅ “Forwards” matching messages visually (green success animation)  
✅ Displays detected OTPs in a table with timestamp and sender  

No login or real Gmail connection is required — it’s 100% browser-based.

---

## 🧠 How it works

1. Each time you click **“Simulate New Incoming Email”**, the page creates a fake message.
2. The script searches the message body for any 4–8 digit code using **Regex** (`\b\d{4,8}\b`).
3. When found, the OTP is shown in a “Captured OTP Table” with sender, subject, and timestamp.
4. A visual “Forwarded” message appears for a few seconds.

---

## 🧩 Files included

- **index.html** — main front-end page (HTML + CSS + JavaScript).  
  You can edit it directly in GitHub to change animations, colors, or add new sample messages.

---

## 🚀 How to View (no setup needed)

1. Open this link:  
