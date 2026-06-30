<div align="center">

# 🌍 WanderLust

### Discover • Share • Explore

A full-stack Airbnb-inspired property listing platform where users can discover unique stays, create listings, upload images, and share reviews.

<p>
  <a href="https://wanderlust-f4t9.onrender.com/listings"><img src="https://img.shields.io/badge/Live-Demo-success?style=for-the-badge" /></a>
  <a href="https://github.com/tpal83957-byte/WanderLust"><img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" /></a>
</p>

<p>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white">
<img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/Mongoose-880000?style=flat-square">
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/EJS-B4CA65?style=flat-square">
<img src="https://img.shields.io/badge/Passport.js-34E27A?style=flat-square">
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square">
</p>

</div>

---

# 📖 About the Project

**WanderLust** is a full-stack web application inspired by Airbnb that enables users to browse travel destinations, create property listings, upload images, and share their experiences through reviews.

The application is built using the **MVC (Model-View-Controller)** architecture and demonstrates modern backend development concepts including secure authentication, authorization, RESTful routing, server-side validation, cloud image storage, and MongoDB integration.

This project was built to strengthen my understanding of full-stack web development using the Node.js ecosystem.

---

# 🚀 Live Demo

### 🌐 https://wanderlust-f4t9.onrender.com/listings

---

# ✨ Features

## 👤 User Authentication

- User Registration
- Secure Login & Logout
- Password Encryption
- Session-based Authentication
- Persistent Login Sessions

---

## 🏡 Property Listings

- Browse all listings
- View listing details
- Create new listings
- Edit existing listings
- Delete listings
- Upload listing images

---

## ⭐ Reviews

- Add reviews
- Delete own reviews
- Review validation

---

## 🔒 Authorization

- Only authenticated users can create listings.
- Only listing owners can edit/delete listings.
- Only logged-in users can post reviews.
- Only review authors can delete their reviews.

---

## ☁️ Image Upload

- Cloudinary Integration
- Multer Middleware
- Cloud-based image storage

---

## ✅ Validation

- Joi Validation
- Server-side validation
- Flash Messages
- Error Handling Middleware

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | HTML, CSS, Bootstrap, JavaScript, EJS |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas, Mongoose |
| Authentication | Passport.js, Passport Local, Passport Local Mongoose |
| Image Storage | Cloudinary, Multer |
| Validation | Joi |
| Sessions | Express Session, Connect-Mongo |
| Utilities | Connect Flash, Method Override, Dotenv |

---

# 🏗 MVC Architecture

```
Client
   │
   ▼
Express Routes
   │
   ▼
Controllers
   │
   ▼
Models
   │
   ▼
MongoDB Atlas
```

The application follows the **MVC Architecture**, making the code modular, maintainable, and scalable.

---

# 📂 Project Structure

```
WanderLust
│
├── assets/
├── controllers/
├── init/
├── models/
├── public/
├── routes/
├── uploads/
├── utils/
├── views/
│
├── app.js
├── middleware.js
├── cloudConfig.js
├── schema.js
├── package.json
└── README.md
```

---

# 📸 Screenshots

## 🏠 Home Page

![Home](assets/home.png)

---

## 🔐 Login

![Login](assets/Login.png)

---

## 📝 Sign Up

![Signup](assets/Signup.png)

---

## 📄 Listing Details

![Listing Details](assets/ListingDetails.png)

---

## ➕ Create New Listing

![New Listing](assets/NewListing.png)

---

# ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/tpal83957-byte/WanderLust.git
```

### Navigate to the project directory

```bash
cd WanderLust
```

### Install dependencies

```bash
npm install
```

---

# 🔑 Environment Variables

Create a **.env** file in the project root and add:

```env
ATLASDB_URL=

SECRET=

CLOUD_NAME=

CLOUD_API_KEY=

CLOUD_API_SECRET=

MAP_TOKEN=
```

---

# ▶️ Run Locally

```bash
node app.js
```

Visit

```
http://localhost:8080
```

---

# 🔐 Security Features

- Secure Password Hashing
- Passport.js Authentication
- Authorization Middleware
- Session Management
- Joi Validation
- Cloudinary Secure Uploads
- Error Handling Middleware
- Flash Messages

---

# 📚 What I Learned

Working on WanderLust helped me gain practical experience with:

- Building RESTful Web Applications
- MVC Architecture
- Authentication & Authorization
- MongoDB Data Modeling
- Cloudinary Integration
- Multer File Uploads
- Express Middleware
- Server-side Validation
- Error Handling
- Session Management
- Full-stack Project Deployment

---

# 🚀 Future Enhancements

- ❤️ Wishlist Feature
- 🔍 Search & Filters
- 📍 Interactive Maps
- 💳 Online Booking & Payments
- 🌐 Google OAuth
- 👤 User Profiles
- 📱 Enhanced Mobile Responsiveness
- 📊 Admin Dashboard

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

Feel free to fork this repository and submit a Pull Request.

---

# 👩‍💻 Author

### Tanya Pal

- GitHub: https://github.com/tpal83957-byte
- LinkedIn: YOUR_LINKEDIN_PROFILE

---

<div align="center">

### ⭐ If you found this project helpful, consider giving it a star!

Thank you for visiting this repository.

</div>
