# CipherSafe — Password Manager (Client-only)

A lightweight, client-side password manager built with **React**, **Tailwind CSS**, and **Vite**. CipherSafe was developed as a portfolio project to demonstrate CRUD flows, client-side persistence, and user-friendly interactions. This project is intentionally **client-only** and does **not** implement encryption or server-side sync.

---

## 🚀 Features
- **Add / Edit / Delete credentials** (site, username, password)
- **Copy to clipboard** with subtle toast feedback
- **Search & filter** credentials quickly
- **Persistent storage** using `localStorage`
- Built with **React + Tailwind + Vite**

---

## 📸 Screenshots
| Add Password | Edit Password | Delete Password |
|--------------|---------------|-----------------|
| ![Add](https://github.com/raaj157/CipherSafe/blob/main/CipherSafe%20-/public/assests/CaseStudy5-img1.jpg) | ![Edit](https://github.com/raaj157/CipherSafe/blob/main/CipherSafe%20-/public/assests/CaseStudy5-img2.jpg) | ![Delete](https://github.com/raaj157/CipherSafe/blob/main/CipherSafe%20-/public/assests/CaseStudy5-img3.jpg) |

---

## 🛠️ Tech Stack
- **React** (UI library)
- **Tailwind CSS** (styling)
- **Vite** (bundler & dev server)
- **localStorage** (client persistence)

---

## 📂 Project Structure
```
├── src
│   ├── App.jsx           # Main app wrapper
│   ├── Components
│   │   └── Manager.jsx   # Core CRUD + UI logic
│   └── index.css         # Tailwind styles
├── public/assets         # Screenshots, banner images
├── index.html
└── vite.config.js
```

---

## ▶️ Getting Started
### 1. Clone the repo
```bash
git clone https://github.com/raaj157/ciphersafe.git
cd ciphersafe
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start development server
```bash
npm run dev
```

### 4. Build for production
```bash
npm run build
```

---

## ⚠️ Important Note
This project is **not production-ready**:
- It does **not** implement encryption.
- Passwords are stored in **plain localStorage**.
- No server sync or zero-knowledge design is included.

This is strictly a **UI/UX and frontend development case study**.

---

## 📄 Case Study
See the full case study section in the portfolio for:
- Problem & solution statement
- Key design decisions
- Screenshots & flows
- Learnings and next steps

[View Case Study →](#)

---

© 2026 CipherSafe Portfolio Project
