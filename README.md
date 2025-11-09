# 🌍 Wanderlust

[![License: MIT](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)

A full-stack web application for **listing, reviewing, and exploring travel destinations**.  
Built using **Node.js, Express, MongoDB, Mongoose, Passport.js, EJS, Cloudinary, and Bootstrap**.

🔗 **Live Demo:** [https://delta-project-7ul9.onrender.com](https://delta-project-7ul9.onrender.com)

---

## ✨ Features

- 🏞️ Create, edit, and delete travel listings  
- 📝 Add reviews and ratings for listings  
- 🔐 User authentication & authorization (Login/Register with Passport.js)  
- 📸 Upload images via Cloudinary  
- ⚡ Flash messages for user feedback  
- 🎨 Responsive UI with Bootstrap  

---

## 🛠️ Tech Stack

**Frontend:**  
- EJS templating  
- Bootstrap 5  
- CSS  

**Backend:**  
- Node.js  
- Express.js  
- Passport.js (local strategy)  
- Connect-flash & Express-session  

**Database:**  
- MongoDB Atlas (Mongoose ODM)  

**Other Integrations:**  
- Cloudinary (Image storage)  

---

## 🗂️ Folder Structure

wanderlust/
│
├── backend/ # Backend server
│ ├── config/ # DB, Passport.js, Cloudinary config
│ ├── controllers/ # Route controllers
│ ├── models/ # Mongoose schemas
│ ├── routes/ # Express routes
│ ├── middleware/ # Auth & flash middleware
│ └── app.js # Main backend entry
│
├── frontend/ # Frontend views
│ ├── views/ # EJS templates
│ │ ├── partials/ # Header, footer, navbar, etc.
│ │ ├── listings/ # Listing pages
│ │ ├── reviews/ # Review pages
│ │ └── auth/ # Login/Register pages
│ └── public/ # CSS, JS, images
│
├── image/ # Screenshots for README or demo
├── package.json
├── README.md
└── .env # Environment variables

yaml
Copy code

---

## 📸 Screenshots
<p float=left>
<img width="200"  alt="Screenshot 1" src="https://github.com/user-attachments/assets/60561d2b-e284-4b86-9f9c-f45745e989bb" />  
<img width="200"  alt="Screenshot 2" src="https://github.com/user-attachments/assets/3396edba-b518-4e7f-b3f4-b3b303b826c2" />  
<img width="200"  alt="Screenshot 3" src="https://github.com/user-attachments/assets/1d7bf2a5-0957-4f01-bc1b-1c320596fed3" />  
</p>

---

## 🔮 Future Scope

- 🔍 **Advanced Filtering & Search:** Allow users to filter listings by location, price, and ratings  
- 💳 **Payment Gateway Integration:** Add booking & payment system for premium listings using Stripe/Razorpay  
- 📌 **Wishlist/Favorites:** Let users save their favorite destinations
