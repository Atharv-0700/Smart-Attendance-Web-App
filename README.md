#📱 Smart QR-Based Secure Attendance Web Application

A **modern, secure, and real-time attendance system** designed to completely eliminate **proxy attendance** in colleges using **QR codes, geo-fencing, browser locking, and Google Firebase**.

🎓 **Department:** BCA  
🏫 **Institution:** Bharati Vidyapeeth University  
🚀 **Use Case:** College / University Attendance System  

---

## 🎯 Problem Statement

Traditional college attendance systems face major issues:

- ⏳ Manual roll calls waste 10–15 minutes per lecture  
- ❌ Proxy attendance (friends marking for others)  
- 📄 Paper registers can be lost or manipulated  
- 📍 No location validation (attendance from anywhere)  
- 📊 No real-time tracking or analytics  
- 🔐 Login sharing enables misuse  

---

## ✨ Our Solution

**Smart QR-Based Secure Attendance System** is a **web application** where attendance is marked **only when all security conditions are satisfied**:

✅ Student is **physically present on campus** (100m geo-fence)  
✅ QR code is **time-limited** (5–10 minutes)  
✅ **One student = one browser/device** (browser fingerprinting)  
✅ Attendance stored **live on Firebase**  
✅ Teachers get **instant Excel reports**

---

## 💡 Why This System Is Better

| Traditional Method | Smart Attendance System |
|-------------------|-------------------------|
| 10–15 minutes per lecture | ⏱️ 30-second QR scan |
| Proxy attendance possible | 🔒 Browser + device lock |
| No location check | 📍 100m geo-fencing |
| Paper registers | ☁️ Cloud storage |
| Manual reports | 📥 One-click Excel |
| No analytics | 📊 Live dashboard |

---

## 👥 User Roles

### 👨‍🏫 Teacher
- Generate time-limited QR codes
- Monitor live attendance
- View subject-wise & class-wise reports
- Download Excel / CSV reports
- Identify at-risk students (<75%)

### 🎓 Student
- Scan QR to mark attendance
- View subject-wise attendance %
- See color-coded status (Green / Yellow / Red)
- Track attendance history
- One browser, one device access

### 👔 Admin (Future Scope)
- Manage users
- Override attendance (with audit log)
- Department-level analytics
- Policy control (QR time, geo-fence)

---

## 🔑 Key Features

- 📱 **Time-limited QR code attendance**
- 📍 **100-meter campus geo-fencing**
- 🔒 **Browser fingerprint & session locking**
- 📊 **Real-time attendance dashboard**
- 📥 **Excel / CSV export**
- 🚫 **Duplicate & proxy attendance prevention**
- ☁️ **Firebase real-time sync**

---

## 🔄 User Flow

**Teacher Flow**
Login → Start Lecture → Generate QR → Live Attendance → End Lecture → Download Report

css
Copy code

**Student Flow**
Login → Browser Check → Location Check → Scan QR → Attendance Marked

yaml
Copy code

---

## 🏗️ System Architecture

Student / Teacher Browser
↓
QR Scan + Location Validation
↓
Browser Fingerprint Check
↓
Firebase Authentication
↓
Firebase Realtime Database
↓
Live Dashboard & Excel Export

yaml
Copy code

---

## ☁️ Google Technologies Used

- **Firebase Authentication** – Secure login & sessions  
- **Firebase Realtime Database** – Live data synchronization  
- **Firebase Hosting** – Fast & secure deployment  
- **Google Cloud Platform** – Scalable infrastructure  

✔ Free tier supports up to **50,000 users**

---

## 🛡️ Security Highlights (Anti-Proxy System)

1. **Browser Fingerprinting** – Prevents login sharing  
2. **Geo-Fencing** – Attendance only inside campus  
3. **Time-Limited QR** – No screenshots or reuse  
4. **Duplicate Scan Check** – One scan per lecture  
5. **Session Locking** – One active session only  

➡️ Result: **Zero proxy attendance**

---

## 📊 Data Storage (Simplified)

```json
/users/{userId}
/lectures/{lectureId}
/lectures/{lectureId}/students/{studentId}
/deviceBindings/{userId}
/attendanceSummary/{studentId}
🚀 Future Scope
Admin dashboard

Face verification with QR

AI-based attendance analytics

Mobile apps (Android & iOS)

Multi-campus support

Parent portal & ERP integration

👨‍💻 Team
Team Leader: Atharva Gogawale
Department: BCA
University: Bharati Vidyapeeth University

🌟 Why This Project Stands Out
✔ Solves a real campus problem
✔ Strong multi-layer security
✔ Uses Google-grade technology
✔ Scalable & cost-effective
✔ Production-ready concept

⭐ If you like this project, give it a star!
