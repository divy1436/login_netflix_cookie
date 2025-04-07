<div align="center">

# 🍪 Login to Netflix via Cookie Import  
### A Study on Session Handling and Web Authentication

</div>

---

## 🔍 Objective

This project demonstrates how session-based authentication works in web applications.  
By importing valid browser cookies, we simulate logging into Netflix **without using a traditional username and password**.  
This experiment helps in understanding how session cookies manage login states.

---

## 🧰 Tools Used

| Tool | Description |
|------|-------------|
| 🔌 [Cookie Manager (Chrome Extension)](https://chrome.google.com/webstore/detail/cookie-manager/) | View, import, and export cookies by domain |
| 🧩 [Cookie Editor (Chrome Extension)](https://chrome.google.com/webstore/detail/cookie-editor/) | A more detailed cookie tool for manual editing and management |
| 📄 JSON Cookie File | Contains valid Netflix session data used for testing (*not shared publicly*) |

---

## 🧪 Step-by-Step Guide

### 1. *Install Extensions*
- Install both **Cookie Manager** and **Cookie Editor** from the Chrome Web Store.

### 2. *Obtain Netflix Cookies*
- Use a valid `cookie.json` file for Netflix.
- This file should be in JSON format and contain **unexpired** session data.

### 3. *Login via Cookie Manager*
- Open [Netflix](https://www.netflix.com)
- Click the **Cookie Manager** extension.
- Select **Import**, paste the JSON cookie data, and apply.
- Refresh Netflix – you should now be logged in.

### 4. *Logout and Re-Login via Cookie Editor*
- Manually log out of the current Netflix session.
- Open the **Cookie Editor** extension.
- Select the same domain and re-import the same `cookie.json`.
- Refresh Netflix – your session should restore successfully.

---

## 🎥 Demo Video

📺 Watch the full demonstration video here:  
[🔗 Click to Watch](https://drive.google.com/file/d/11zc4IIDYQvbAHJrNy4L4w6J6Kssjetnu/view?usp=drivesdk)

---

## 📘 What I Learned

- Session cookies are key to keeping users logged in without repeated authentication.
- Valid cookies can recreate login sessions, showing how web apps manage state.
- Mismanagement of cookies can lead to unauthorized access – a major security concern.

---

## ⚠ Disclaimer

> **This project is intended strictly for educational purposes.**  
> All testing was performed in a *controlled environment* using valid session data provided for learning.  
> **Do not use or share cookies without the owner’s consent.**  
> Unauthorized use of cookies violates terms of service and privacy policies.

---

## ✅ Key Takeaways

- Session handling is a core concept in web development and cybersecurity.
- Cookie-based login highlights the importance of secure cookie attributes (`HttpOnly`, `Secure`, etc.).
- Developers and testers must be aware of cookie vulnerabilities to build safer applications.

---


