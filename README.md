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

<img src="https://github.com/user-attachments/assets/e5ba5d41-83db-42b7-8bfc-00f94027708f" width="300" alt="Welcome Screen" />

---

### Pick Your Style
> Each cut shows the price in Rands and how long it takes

<p float="left">
  <img src="https://github.com/user-attachments/assets/20e27fab-dcfb-423f-b353-d3d2c4f5c801" width="300" alt="Fade" />
  <img src="https://github.com/user-attachments/assets/03cddf63-0827-4cd4-94c8-afcede418b78" width="300" alt="Taper and Chiskop" />
  <img src="https://github.com/user-attachments/assets/e2812a59-3995-42d6-8053-066b597e5f70" width="300" alt="Chiskop and Trim" />
</p>

---

### Choose Your Barber & Time
> Barbers show as Available or Busy in real time

<p float="left">
  <img src="https://github.com/user-attachments/assets/a9eb57ca-d308-4651-b144-dc2c265ea7fa" width="300" alt="Select Date and Barber" />
  <img src="https://github.com/user-attachments/assets/f4bab490-11f1-4b9f-9f69-2ac44cd539ef" width="300" alt="Select Time Slot" />
</p>

---

### Booking Summary & Confirmation

<p float="left">
  <img src="https://github.com/user-attachments/assets/00f54c2c-9f67-46cc-8e94-16db11d4837a" width="300" alt="Booking Summary" />
  <img src="https://github.com/user-attachments/assets/130c8129-6bf8-49c9-8b1d-53cb57da5bb0" width="300" alt="Booking Confirmed" />
</p>

---

### ⭐ Loyalty Club
> 10 cuts and the next one's on the house

<p float="left">
  <img src="https://github.com/user-attachments/assets/5405f6c3-d170-4627-96b6-5c08abd2d3bf" width="300" alt="Loyalty Club" />
  <img src="https://github.com/user-attachments/assets/d844550f-533e-4d2f-b21f-d32c4832e768" width="300" alt="Loyalty Club Progress" />
</p>

---

### 🖥️ Admin Dashboard — Daily Schedule & Live Overview

<img src="https://github.com/user-attachments/assets/bbffa1c3-e217-4f22-9e31-358672bfa483" width="100%" alt="Dashboard Schedule" />

### Cut History

<img src="https://github.com/user-attachments/assets/408ce77a-de1c-4242-a62d-9200b5560523" width="100%" alt="Cut History" />

### Manage Barbers

<img src="https://github.com/user-attachments/assets/4e7c020c-1dd2-4304-865e-21a8c4e2cf2a" width="100%" alt="Manage Barbers" />

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
