# ✂️ BowCutz

> **BowCutz** is a barber booking app built for a real barbershop. Clients book their cuts from their phone, and barbers manage everything from a live web dashboard. No more WhatsApp bookings, no more confusion — just clean scheduling.

Built with **React Native (Expo)** on the front and **Firebase** handling everything on the back.

---

## 💡 What It Does

There are two sides to BowCutz:

**📱 Mobile App — for clients**  
Open the app, enter your name, pick a haircut, choose a barber, lock in a time — done. It's quick, it looks good, and it even has a loyalty system that tracks your visits and rewards you with a free cut every 10 visits. 🎁

**🖥️ Admin Dashboard — for barbers**  
Runs in the browser and shows everything happening that day — who's booked, at what time, for which service, and with which barber. When a cut is done, hit **Complete Cut** and it moves to history. Simple as that.

---

## 📸 Screenshots

### Welcome & Onboarding

<p align="center">
  <img src="https://github.com/user-attachments/assets/0df10b15-9989-4cc3-ae42-8dc077724f08" width="300" alt="Welcome Screen" />
</p>

---

### Pick Your Style

> Each cut shows the price in Rands and how long it takes

<p align="center">
  <img src="https://github.com/user-attachments/assets/4f83623b-f644-414e-b6a0-4efeb2592099" width="260" alt="Fade" />
  <img src="https://github.com/user-attachments/assets/5f7f8000-13f4-46c0-8129-ac48312f0960" width="260" alt="Taper and Chiskop" />
  <img src="https://github.com/user-attachments/assets/07ca632f-48a3-43c0-a054-e1762eb1eb00" width="260" alt="Chiskop and Trim" />
</p>

---

### Choose Your Barber & Time

> Barbers show as Available or Busy in real time

<p align="center">
  <img src="https://github.com/user-attachments/assets/20e33605-55b4-42b3-b044-c3f9e8a4ab98" width="260" alt="Select Date and Barber" />
  <img src="https://github.com/user-attachments/assets/4e39b2e9-2887-4e88-a479-b6c0a76b6478" width="260" alt="Select Time Slot" />
</p>

---

### Booking Summary & Confirmation

<p align="center">
  <img src="https://github.com/user-attachments/assets/5b8578a0-f794-496b-a31f-085e4b3a6b73" width="260" alt="Booking Summary" />
  <img src="https://github.com/user-attachments/assets/8af1d6c2-d57a-4095-a90f-621b6c8a61ff" width="260" alt="Booking Confirmed" />
</p>

---

### ⭐ Loyalty Club

> 10 cuts and the next one's on the house

<p align="center">
  <img src="https://github.com/user-attachments/assets/7196567f-5bee-4798-b25d-794103fc895c" width="260" alt="Loyalty Club" />
  <img src="https://github.com/user-attachments/assets/60e91623-0c1a-4694-8681-20b216793f14" width="260" alt="Loyalty Club Progress" />
</p>

---

### 🖥️ Admin Dashboard — Daily Schedule & Live Overview

<p align="center">
  <img src="https://github.com/user-attachments/assets/1657a4f3-c940-4fa6-ac01-b57a2e19c4e6" width="100%" alt="Dashboard Schedule" />
</p>

### Cut History

<p align="center">
  <img src="https://github.com/user-attachments/assets/0b2172cd-055e-4219-929d-b2f8b89a49e5" width="100%" alt="Cut History" />
</p>

### Manage Barbers

<p align="center">
  <img src="https://github.com/user-attachments/assets/1deadc93-c4c2-4cfb-9ee6-ebf43424f17a" width="100%" alt="Manage Barbers" />
</p>

---

## 💈 Services & Pricing

| Cut | Price | Time |
|-----|-------|------|
| Fade | R100 | 45 min |
| Taper | R100 | 30 min |
| Chiskop / Bald | R100 | 30 min |
| Trim | R80 | 20 min |

---

## 🛠️ Built With

- **React Native + Expo** — mobile app
- **React** — admin web dashboard
- **Firebase Firestore** — database and real-time syncing
- **Firebase Authentication** — admin login

---

## 🚀 Running It Locally

You'll need **Node.js (v18+)**, **Expo CLI**, and a **Firebase project** set up with Firestore.

**1. Clone the repo:**

```bash
git clone https://github.com/radebeinnovations/BowCutz-App-Dashboards.git
cd BowCutz-App-Dashboards
npm install
 
---
 
## 📁 Project Layout
 
```
BowCutz-App-Dashboards/
├── .expo/
├── BowCutz Gallery/       ← hairstyle images
├── BowCutzDashboard/      ← admin web dashboard
├── start_dashboards.bat   ← quick start script
└── README.md
```
 
---
 
## 📝 Notes
 
The admin dashboard requires a login — credentials are handled through Firebase Auth. If you're setting this up fresh, make sure to create an admin user in your Firebase console first.
 
---
 
> Built by **Radebe Innovations** 🚀
