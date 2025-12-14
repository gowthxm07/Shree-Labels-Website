# Shree Labels – Premium Printing Solutions

A premium, fully responsive business website for **Shree Labels**, a printing press solution provider based in **Karur, Tamil Nadu**.  
This website showcases infrastructure, products, and services while providing **real-time client feedback** and **contact capabilities**.

---

## 🌟 Features

- **Modern UI/UX**  
  Built with a glassmorphism aesthetic, smooth scrolling, and CSS animations.

- **Responsive Design**  
  Fully optimized for **Mobile, Tablet, and Desktop** screens with a custom hamburger menu.

- **Dynamic Gallery**  
  Tab-based filtering system (**Infrastructure** vs **Label Samples**).

- **Live Feedback System**  
  Integrated with **Firebase Firestore** to store and display client reviews in real-time.

- **Contact Form**  
  Fully functional contact form powered by **EmailJS** (no backend server required).

- **Location Integration**  
  Embedded **Google Maps** for easy location access.

---

## 🛠️ Tech Stack

- **Frontend:**  
  HTML5, CSS3 (Variables, Flexbox, Grid), JavaScript (ES6 Modules)

- **Backend as a Service:**  
  Firebase v11.6.1 (Authentication & Firestore Database)

- **Email Service:**  
  EmailJS

- **Fonts:**  
  Google Fonts (Outfit & Playfair Display)

- **Icons:**  
  Flaticon & Unicode

---

## 📂 Project Structure

Printing-Press-Website/
│
├── index.html # Main application file (Single Page Application)
├── README.md # Project documentation

yaml
Copy code

---

## 🚀 Setup & Installation

Since this project uses **ES6 Modules** (`type="module"` in script tags), you need a **local server** to run it correctly on your machine to avoid CORS issues.

---

### 🔁 Clone the Repository

git clone https://github.com/gowthxm07/Shree-Labels-Website.git
cd Shree-Labels-Website

yaml
Copy code

---

### ▶️ Run Locally

#### Option A — VS Code (Recommended)

1. Install the **Live Server** extension  
2. Right-click `index.html`  
3. Select **Open with Live Server**

#### Option B — Python

python -m http.server 8000

arduino
Copy code

Then open:

http://localhost:8000

yaml
Copy code

---

## ⚙️ Configuration Details

The website connects to the following external services.  
The configuration keys are currently embedded in `index.html`.

---

### 1️⃣ Firebase (Google)

Used for the **Review / Feedback** section.

- **Project ID:** `shree-labels`
- **Services Used:**
  - Authentication (Anonymous)
  - Firestore Database
- **Collection Name:** `reviews`

---

### 2️⃣ EmailJS

Used for the **Contact Us** form submission.

- **Service ID:** `service_15i8wvf`
- **Template ID:** `template_a3kk19i`
- **Public Key:** `LIyW5ilfH6JzF8_Hc`

---

## 📸 Sections Overview

- **Hero**  
  Full-screen introduction with animated zoom background.

- **About**  
  Company location (**Karur, Tamil Nadu**) and expertise details.

- **Gallery**  
  Interactive portfolio showcasing:
  - Machinery (Heidelberg Press)
  - Printed Label Samples

- **Services**  
  Grid layout of services:
  - Label Printing
  - Sticker Printing
  - Offset Printing
  - Custom Finishing

- **Feedback**  
  Read and write client reviews dynamically using **Firebase Firestore**.

- **Contact**  
  Contact form integrated with **EmailJS** along with address details.

---

## 📬 Contact Information

**Shree Labels**  
📍 Location: Karur, Tamil Nadu, India  
📧 Email: info@company.com  
📞 Phone: +91 98765 43210  

---

## 👨‍💻 Developer

**Developed by:**  
**Gowtham Hari S**
