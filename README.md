# 🏷️ Shree Labels – Premium Printing Solutions Website

![Project Status](https://img.shields.io/badge/Status-Live-success)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)
![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)

A fully responsive, dynamic business website designed for **Shree Labels**, a printing press solution provider based in **Karur, Tamil Nadu**.  
This application serves as a digital portfolio showcasing infrastructure, label samples, and services while facilitating real-time client interaction.

---

## 🔗 Live Demo

👉 **[Click here to view the Live Website](https://shree-labels-website.vercel.app)**  
*(Replace the link above if your Vercel URL is different)*

---

## ✨ Key Features

### 1. Modern & Responsive UI
- Built with a **mobile-first approach** using CSS Grid and Flexbox
- Smooth scrolling navigation with **glassmorphism navbar**
- **Hero section** with zooming background animation and call-to-action

### 2. Interactive Gallery Slider
- Horizontal scrolling image slider for label samples
- Displays **3 images on desktop** and **1 image on mobile**
- Hover effects for enhanced user engagement

### 3. Real-Time Client Feedback (Firebase Powered)
- Users can submit reviews with **1–5 star ratings**
- **Live updates** without page refresh using Firestore
- Secure database writes via **Firebase Anonymous Authentication**

### 4. Contact Integration (EmailJS)
- Functional **Contact Us** form
- Messages sent directly to business email inbox
- Success and error handling for better UX

### 5. Location Services
- Embedded **Google Maps iframe** for easy navigation

---

## 🛠 Tech Stack

| Component | Technology |
|---------|-----------|
| Frontend | HTML5, CSS3, JavaScript (ES6 Modules) |
| Database | Firebase Firestore (NoSQL) |
| Authentication | Firebase Auth (Anonymous Sign-in) |
| Email Service | EmailJS |
| Hosting | Vercel |
| Fonts | Google Fonts (Outfit & Playfair Display) |

---

## 📂 Project Structure

```text
/
├── index.html          # Main application file (HTML + CSS + JS logic)
├── README.md           # Project documentation
└── images/
    └── gallery/
        ├── label1.jpeg
        ├── label2.jpeg
        ├── label3.jpeg
        ├── label4.jpeg
        ├── label5.jpeg
        └── label6.jpeg
```
## 🚀 How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/gowthxm07/Shree-Labels-Website.git
cd Shree-Labels-Website
2️⃣ Add Images
Ensure the images/gallery folder contains:

label1.jpeg

label2.jpeg

label3.jpeg

label4.jpeg

label5.jpeg

label6.jpeg

This prevents broken image links.
```

### 3️⃣ Run with Live Server
Because this project uses ES6 modules (type="module"), you cannot open index.html directly.

Recommended:

Open the project in VS Code

Install the Live Server extension

Right-click index.html → Open with Live Server

## ⚙️ Configuration Setup
### 🔥 Firebase Configuration (Reviews System)
Update the firebaseConfig object in index.html:

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID"
};
Firebase Console Setup
Enable Firestore Database

Enable Anonymous Authentication

Firestore rules (development only):

allow read, write: if true;
✉️ EmailJS Configuration (Contact Form)
Update EmailJS initialization and send method:

emailjs.init("YOUR_PUBLIC_KEY");

emailjs.send(
  "YOUR_SERVICE_ID",
  "YOUR_TEMPLATE_ID",
  formData
);

### 👤 Author

- **Gowtham Hari S**
- Undergraduate B.Tech Engineering Student
- Full Stack Development & AI Enthusiast

---

## © License

© 2025 **Shree Labels**. All Rights Reserved.

