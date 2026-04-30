# ✂️ BowCutz

> **BowCutz** is a barber booking app built for a real barbershop. Clients book their cuts from their phone, and barbers manage everything from a live web dashboard. No more WhatsApp bookings, no more confusion — just clean scheduling.

Built with **React Native (Expo)** on the front and **Firebase** handling everything on the back.

---

## 💡 What It Does

There are two sides to BowCutz:

**📱 Mobile App — for clients**
Open the app, enter your name, pick a haircut, choose a barber, lock in a time — done. It's quick, it looks good, and it even has a loyalty system that tracks your visits and rewards you with a free cut every 10 visits. 🎁

**🖥️ Admin Dashboard — for barbers**
Runs in the browser and shows everything happening that day — who's booked, at what time, for which service, and with which barber. When a cut is done, hit "Complete Cut" and it moves to history. Simple as that.

---

## 📸 Screenshots

### Welcome & Onboarding

<p float="left">
  <img src="https://github.com/user-attachments/assets/a06176b8-db87-4631-aac7-920624397628" width="300" alt="Welcome Screen" />
  <img src="https://github.com/user-attachments/assets/715878e3-bde3-4613-b1a8-6e92655c8104" width="300" alt="Onboarding" />
</p>

---

### Pick Your Style
> Each cut shows the price in Rands and how long it takes

<p float="left">
  <img src="https://github.com/user-attachments/assets/a7da3521-1001-4b5f-8886-78574e69a001" width="300" alt="Fade" />
  <img src="https://github.com/user-attachments/assets/b1d050fc-3c1e-417e-aa6b-ee5bea3ad37d" width="300" alt="Taper and Chiskop" />
  <img src="https://github.com/user-attachments/assets/06fdefbb-6173-4e8a-bbb4-7b430319d5b4" width="300" alt="Chiskop and Trim" />
</p>

---

### Choose Your Barber & Time
> Barbers show as Available or Busy in real time

<p float="left">
  <img src="https://github.com/user-attachments/assets/b7b02671-e174-4836-9b27-304becfa3647" width="300" alt="Select Date and Barber" />
  <img src="https://github.com/user-attachments/assets/85f4cf6d-9e05-4030-8957-c45ed7e0a670" width="300" alt="Select Time Slot" />
</p>

---

### Booking Summary & Confirmation

<p float="left">
  <img src="https://github.com/user-attachments/assets/b9568b68-690c-48e5-9d75-5fcb3d5d64df" width="300" alt="Booking Summary" />
  <img src="https://github.com/user-attachments/assets/2360e443-d8e6-4a5e-baa8-c19cfb36fd02" width="300" alt="Booking Confirmed" />
</p>

---

### ⭐ Loyalty Rewards
> 10 cuts and the next one's on the house

<img src="https://github.com/user-attachments/assets/707942c8-7593-4950-9d40-c90efa8af356" width="300" alt="Loyalty Club" />

---

### 🖥️ Admin Dashboard — Daily Schedule & Live Overview

<img src="https://github.com/user-attachments/assets/de575ca3-f0e3-4bd8-b4d4-f34442596cdb" width="100%" alt="Dashboard Schedule" />

### Cut History

<img src="https://github.com/user-attachments/assets/0ae73da7-0166-45e0-8e2c-6919f6bd7e3e" width="100%" alt="Cut History" />

### Manage Barbers

<img src="https://github.com/user-attachments/assets/739cdb70-6b17-4a15-9984-37e074bf34bb" width="100%" alt="Manage Barbers" />

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
```

**2. Add your Firebase credentials to the config file:**
```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

**3. Start the mobile app:**
```bash
npx expo start
```
Then scan the QR code with **Expo Go** on your phone.

**4. Start the dashboard:**
```bash
cd BowCutzDashboard
npm install
npm start
```
Opens at `http://localhost:3000`

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
