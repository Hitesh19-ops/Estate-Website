# 🏠 Estate – Real Estate Landing Website

A modern, fully responsive Real Estate Landing Website built using **React.js**, **Tailwind CSS**, and **Framer Motion**.  
This project showcases property listings, testimonials, smooth animations, and a fully functional contact form powered by the Web3Forms API.

🔗 **Live Demo:**  
https://estate-website-c6o8.vercel.app/

📂 **GitHub Repository:**  
https://github.com/Hitesh19-ops/Estate-Website

---

## 🚀 Tech Stack

- ⚛️ React.js (Vite)
- 🎨 Tailwind CSS
- 🎬 Framer Motion
- 🔔 React Toastify
- 📩 Web3Forms API

---

## ✨ Features

- Fully Responsive Design (Mobile, Tablet, Desktop)
- Smooth Scroll Navigation
- Animated Sections using Framer Motion
- Dynamic Project Slider / Carousel
- Customer Testimonials Section
- Functional Contact Form with Toast Notifications
- Newsletter Subscription UI
- Mobile Responsive Navbar
- Clean & Modern UI

---

## 📁 Folder Structure

```
REAL ESTATE WEBSITE/
│
└── react-project/
    │
    ├── public/
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   │   ├── About.jsx
    │   │   ├── Contact.jsx
    │   │   ├── Footer.jsx
    │   │   ├── Header.jsx
    │   │   ├── Navbar.jsx
    │   │   ├── Projects.jsx
    │   │   └── Testimonials.jsx
    │   │
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    │
    ├── index.html
    ├── tailwind.config.js
    ├── postcss.config.js
    ├── vite.config.js
    └── package.json
```

> ⚠️ Note: The main React application is inside the `react-project` folder.

---

## 🛠 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Hitesh19-ops/Estate-Website.git
```

### 2️⃣ Navigate to project folder

```bash
cd "REAL ESTATE WEBSITE/react-project"
```

### 3️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Run development server

```bash
npm run dev
```

App will run at:

```
http://localhost:5173
```

---

## 📩 Contact Form Integration

The contact form is integrated using **Web3Forms API**.

If you want to use your own access key:

1. Go to https://web3forms.com  
2. Generate your access key  
3. Replace inside `Contact.jsx`:

```js
formData.append("access_key", "YOUR_ACCESS_KEY");
```

---

## 🎯 Learning Outcomes

Through this project, I practiced and improved:

- Component-based architecture in React
- State management using `useState`
- Handling window resize using `useEffect`
- Creating responsive layouts with Tailwind CSS
- Adding animations using Framer Motion
- API form submission handling
- Mobile menu state control
- UI structuring for landing pages
- Deployment on Vercel

---

## 🚀 Deployment

This project is deployed using **Vercel**.

Live URL:  
https://estate-website-c6o8.vercel.app/

---

## 👨‍💻 Author

**Hitesh Srivastava**  
B.Tech Computer Science  
Aspiring Full Stack Developer
