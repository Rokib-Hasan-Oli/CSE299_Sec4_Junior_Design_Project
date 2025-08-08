<p align="center"> 
  <img width="250" height="280" src="image/NSU_Logo.png">
</p>

<h1 align="center">Project Name: GHURBO</h1>
<h2 align ="center">Course Number: CSE 299<br>
Section: 4 <br>
Semester: Summer 2025<br><br>
Faculty Name: Mohammad Shifat-E-Rabbi</h2>

<h3 align="center">
Student Name: Md. Rakibul Hasan<br>
Student Name: Md. Rokib Hasan Oli<br>
Student Name: Md. Nafees Ahommed<br>
North South University, Dhaka
</h3><br><br><br>

---

## 📑 Table of Contents
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Technology Stack](#technology-stack)  
4. [System Architecture](#system-architecture)  
5. [UI Screenshots](#ui-screenshots)  
6. [Local Setup](#local-setup)  
7. [Environment Variables](#environment-variables)  
8. [Run & Scripts](#run--scripts)  
9. [API Overview](#api-overview)  
10. [Roadmap](#roadmap)  
11. [Conclusion](#conclusion)  

---

## 1) Introduction
**GHURBO** is a modern MERN-stack tour package platform designed as a capstone project for **CSE299 Junior Design, Section 4 at North South University**.  

It simplifies trip planning by connecting travelers with curated experiences across Bangladesh and offers a powerful admin dashboard for tour operators to manage packages, bookings, and revenue.  

The project incorporates:
- Practical booking features  
- User-friendly UI/UX  
- Real-time package filtering & search  
- Secure authentication & media handling  

---

## 2) Features
- **Curated Tour Packages** – Browse, filter, and book with real-time availability.  
- **Advanced Filters** – Price range, trip type, sorting (low-high, new-first).  
- **Package Details & Booking** – Image gallery, amenities, date/guest selector, availability check.  
- **Experience Page** – Destination highlights with “Explore Now” navigation.  
- **Owner Dashboard** – KPIs (bookings, revenue), recent bookings, and package toggles.  
- **Package Management** – Add/edit packages with images, price, type, amenities.  
- **Authentication** – Clerk-based secure login/signup and role-based access.  
- **Media & Email** – Cloudinary for storage, Nodemailer for notifications.  

---

## 3) Technology Stack

**Frontend**  
- React (Vite)  
- React Router DOM  
- Tailwind CSS  
- Clerk Authentication  

**Backend**  
- Node.js, Express.js  
- MongoDB & Mongoose  
- Cloudinary, Nodemailer  

**Deployment**  
- Vercel  

---

## 4) System Architecture
```
GHURBO Project
├── client/
│   └── src/
│       ├── components/      # UI Components
│       ├── context/         # AppContext for state management
│       └── pages/           # Pages (Home, TourPackages, PackageDetails, Owner Dashboard)
├── server/
│   ├── configs/             # db, nodemailer, cloudinary configs
│   ├── controllers/         # booking, package, tour, user controllers
│   ├── middleware/          # auth & upload middleware
│   ├── models/              # Mongoose schemas
│   └── routes/              # API routes
```

---

## 5) UI Screenshots
> Store screenshots in `docs/screenshots/` or adjust paths as needed.

- Home Page  
- Tour Packages  
- Package Details & Booking  
- Experiences  
- About Page  
- Dashboard (Owner)  
- Add Package Page  
- Package Listings  

---

## 6) Local Setup
```bash
# Clone repo
git clone <your-repo-url> ghurbo
cd ghurbo

# Install dependencies
cd client && npm install
cd ../server && npm install
```

---

## 7) Environment Variables

**client/.env**
```
VITE_API_BASE_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=pk_test_xxx
VITE_CLERK_SIGN_IN_URL=/sign-in
VITE_CLERK_SIGN_UP_URL=/sign-up
```

**server/.env**
```
PORT=5000
NODE_ENV=development
MONGODB_URI=mongodb+srv://<user>:<pass>@cluster/db
CLERK_SECRET_KEY=sk_test_xxx
CLOUDINARY_CLOUD_NAME=xxx
CLOUDINARY_API_KEY=xxx
CLOUDINARY_API_SECRET=xxx
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=you@example.com
SMTP_PASS=your_app_password
EMAIL_FROM=GHURBO <you@example.com>
CLIENT_URL=http://localhost:5173
```

---

## 8) Run & Scripts
```bash
# Run backend
cd server
npm run dev

# Run frontend
cd client
npm run dev
```

---

## 9) API Overview
**Auth / Users**
- `POST /users/webhooks/clerk`
- `GET /users/me`

**Packages**
- `GET /packages`
- `GET /packages/:id`
- `POST /packages` (owner)
- `PATCH /packages/:id`
- `PATCH /packages/:id/toggle`
- `DELETE /packages/:id`

**Tours**
- `GET /tours`
- `GET /tours/:id`

**Bookings**
- `POST /bookings`
- `GET /bookings/my`
- `GET /bookings/owner`

---

## 10) Roadmap
- Add Stripe/SSLCOMMERZ integration  
- Owner analytics dashboard  
- Wishlist & traveler reviews  
- Multilingual support (Bangla/English)  
- Advanced security features  

---

## 11) Conclusion
GHURBO merges a clean traveler booking experience with an intuitive owner management system.  
Built using a modern MERN stack and supporting services like Clerk and Cloudinary, it’s production-ready and highly scalable.  
