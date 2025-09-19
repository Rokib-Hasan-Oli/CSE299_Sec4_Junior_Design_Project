<p align="center">
  <a href="https://ghurbotravel.vercel.app/" target="_blank">
    <img width="320" src="image/Ghurbo Logo Gold.svg" alt="GHURBO Logo">
  </a>
</p>

<h1 align="center">GHURBO — Smart Tour Package Platform for Bangladesh</h1>

<p align="center">
  <a href="https://ghurbotravel.vercel.app/" target="_blank"><b>🌐 Visit Live Website</b></a>
</p>

<h2 align="center">
  Course: CSE 299 Junior Design · Section 4 · Semester: Summer 2025<br/><br/>
  Faculty: Mohammad Shifat-E-Rabbi
</h2>

<h3 align="center">
  Md Nafees Ahommed — ID: 2111934642 <br/> Md Rokib Hasan Oli — ID: 2211950642 <br/> Md Rakibul Hasan — ID: 2212346042<br/>
  Date Prepared: August 2025
</h3>

---

## 📑 Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Technology Stack](#technology-stack)
4. [Business Plan / Monetization](#business-plan--monetization)
5. [Project Screenshots](#project-screenshots)
   - [Gallery View](#gallery-view)
   - [Home Page](#home-page)
   - [Tour Packages](#tour-packages)
   - [Package Details & Booking](#package-details--booking)
   - [Check Availability](#check-availability)
   - [Book Now](#book-now)
   - [My Bookings](#my-bookings)
   - [Dashboard (Package Owner)](#dashboard-package-owner)
   - [Package Listings](#package-listings)
   - [Add Package](#add-package)
   - [Package Registration Form](#package-registration-form)
   - [AI Chatbot](#ai-chatbot)
   - [Email Verification](#email-verification)
   - [Booking Confirmation Email](#booking-confirmation-email)
   - [Experience Page](#experience-page)
   - [About Page](#about-page)
6. [Conclusion](#conclusion)

---

## 1. Introduction
GHURBO is a **full-stack travel platform** built for Bangladesh. Travelers can discover curated tour packages, compare options, chat with an AI assistant, and book securely — while tour providers manage listings, pricing, and bookings through a dedicated dashboard.

[▲ Back to top](#-table-of-contents)

---

## 2. Features
- **🎯 Curated Packages** — Filter by destination, budget, and dates with live availability.
- **💎 Exclusive Offers** — Seasonal discounts and special deals.
- **🤖 AI Assistant** — English & Bangla chatbot for instant help and recommendations.
- **📊 Provider Dashboard** — Manage packages, bookings, and visibility.
- **🔒 Secure Booking & Emails** — Reliable confirmations and receipts.
- **📱 Responsive UI** — Mobile-first, modern interface.

[▲ Back to top](#-table-of-contents)

---

## 3. Technology Stack
<!-- Clickable logos + names in a neat responsive grid -->
<div align="center">
  <table>
    <tr>
      <td align="center" width="120">
        <a href="https://react.dev/" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="48" alt="React"/><br/>React
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://vitejs.dev/" target="_blank">
          <img src="https://vitejs.dev/logo.svg" width="48" alt="Vite"/><br/>Vite
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://tailwindcss.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="48" alt="Tailwind CSS"/><br/>Tailwind CSS
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://reactrouter.com/" target="_blank">
          <img src="<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" id="React-Router--Streamline-Svg-Logos" height="24" width="24">
  <desc>
    React Router Streamline Icon: https://streamlinehq.com
  </desc>
  <path fill="#000000" d="M7.4162 14.099375c1.17665 0 2.1305 -0.95385 2.1305 -2.1305s-0.95385 -2.1305 -2.1305 -2.1305c-1.176625 0 -2.130475 0.95385 -2.130475 2.1305s0.95385 2.1305 2.130475 2.1305ZM2.380495 18.36035c1.17663 0 2.130505 -0.95385 2.130505 -2.130475 0 -1.17665 -0.953875 -2.1305 -2.130505 -2.1305C1.203855 14.099375 0.25 15.053225 0.25 16.229875c0 1.176625 0.953855 2.130475 2.130495 2.130475Zm19.239005 0c1.17665 0 2.1305 -0.95385 2.1305 -2.130475 0 -1.17665 -0.95385 -2.1305 -2.1305 -2.1305 -1.176625 0 -2.1305 0.95385 -2.1305 2.1305 0 1.176625 0.953875 2.130475 2.1305 2.130475Z" stroke-width="0.25"></path>
  <path fill="#d0021b" d="M14.622225 12.058625c-0.068125 -0.711775 -0.1028 -1.304225 -0.6481 -1.7206 -0.690575 -0.527325 -1.4728 -0.185175 -2.436375 -0.53295 -0.9468 -0.22905 -1.649075 -1.0697 -1.649075 -2.071675 0 -1.1782 0.971025 -2.1333 2.168825 -2.1333 0.88715 0 1.6499 0.523925 1.98585 1.274375 0.5142 0.976675 0.180025 1.97065 0.82605 2.471325 0.764975 0.592825 1.796275 0.158675 2.94705 0.720375 0.36975 0.1699 0.682725 0.4394 0.903275 0.7734 0.220525 0.334 0.348625 0.7325 0.348625 1.16045 0 1.001975 -0.702275 1.8426 -1.649075 2.07165 -0.96355 0.3478 -1.7458 0.00565 -2.436375 0.532975 -0.77655 0.592975 -0.360825 1.585 -0.993725 2.63295 -0.359225 0.69005 -1.089375 1.16235 -1.931675 1.16235 -1.1978 0 -2.168825 -0.955125 -2.168825 -2.133325 0 -0.85585 0.5124 -1.594 1.251925 -1.933825 1.15075 -0.5617 2.18205 -0.127575 2.947025 -0.7204 0.4413 -0.342 0.5346 -0.869575 0.5346 -1.553775Z" stroke-width="0.25"></path>
</svg>" width="48" alt="React Router"/><br/>React Router
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://nodejs.org/" target="_blank">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="48" alt="Node.js"/><br/>Node.js
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://expressjs.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-icon.svg" width="48" alt="Express"/><br/>Express
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <a href="https://www.mongodb.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" width="48" alt="MongoDB"/><br/>MongoDB
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://clerk.com/" target="_blank">
          <img src="https://avatars.githubusercontent.com/u/121480667?s=200&v=4" width="48" alt="Clerk"/><br/>Clerk
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://cloudinary.com/" target="_blank">
          <img src="https://res.cloudinary.com/cloudinary-marketing/images/f_auto,q_auto/w_256/v1708628982/website-2021/brand/cloudinary_icon_for_white_bg/cloudinary_icon_for_white_bg.png" width="48" alt="Cloudinary"/><br/>Cloudinary
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://nodemailer.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/nodemailer/nodemailer-icon.svg" width="48" alt="Nodemailer"/><br/>Nodemailer
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://www.brevo.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/sendinblue/sendinblue-icon.svg" width="48" alt="Brevo"/><br/>Brevo
        </a>
      </td>
      <td align="center" width="120">
        <a href="https://vercel.com/" target="_blank">
          <img src="https://www.vectorlogo.zone/logos/vercel/vercel-icon.svg" width="48" alt="Vercel"/><br/>Vercel
        </a>
      </td>
    </tr>
  </table>
</div>

[▲ Back to top](#-table-of-contents)

---

## 4. Business Plan / Monetization
- Partner listings (hotels, guides, experiences)
- Premium package promotions
- Service fees per booking
- Subscription plans for tour providers

[▲ Back to top](#-table-of-contents)

---

## 5. Project Screenshots

### Gallery View
<!-- Clean, responsive horizontal gallery (works on GitHub) -->
<div align="center">
  <h4>🖼️ Complete Application Showcase</h4>
  <em>Swipe or scroll to explore all features</em>
</div>

<br/>

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="image/Home.png" alt="Home Page" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Home Page</strong>
      </td>
      <td align="center">
        <img src="image/Tour%20Packages.png" alt="Tour Packages" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Tour Packages</strong>
      </td>
      <td align="center">
        <img src="image/Tour%20Package%20info%20and%20Booking.png" alt="Package Details" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Package Details</strong>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="image/Check%20Availability.png" alt="Check Availability" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Check Availability</strong>
      </td>
      <td align="center">
        <img src="image/Book%20Now.png" alt="Book Now" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Book Now</strong>
      </td>
      <td align="center">
        <img src="image/My%20Bookings.png" alt="My Bookings" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>My Bookings</strong>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="image/Dashboard.png" alt="Provider Dashboard" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Provider Dashboard</strong>
      </td>
      <td align="center">
        <img src="image/Package%20Listings.png" alt="Package Listings" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Package Listings</strong>
      </td>
      <td align="center">
        <img src="image/Add%20Package.png" alt="Add Package" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Add Package</strong>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="image/Tour%20Package%20Seller%20Can%20Sell%20pakage%20after%20get%20Register.jpg" alt="Package Registration" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Package Registration</strong>
      </td>
      <td align="center">
        <img src="image/ChatBot.jpg" alt="AI Chatbot" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>AI Chatbot</strong>
      </td>
      <td align="center">
        <img src="image/Verification%20code%20Email%20For%20Login%20or%20Delete%20account.jpg" alt="Email Verification" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Email Verification</strong>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="image/createBooking%20Email.jpg" alt="Booking Email" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Booking Confirmation</strong>
      </td>
      <td align="center">
        <img src="image/Experience.png" alt="Experience Page" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>Experience Page</strong>
      </td>
      <td align="center">
        <img src="image/About.png" alt="About Page" width="280" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
        <br/><strong>About Page</strong>
      </td>
    </tr>
  </table>
</div>


[▲ Back to top](#-table-of-contents)

### Home Page
<img src="image/Home.png" alt="Home Page">

### Tour Packages
<img src="image/Tour Packages.png" alt="Tour Packages">

### Package Details & Booking
<img src="image/Tour Package info and Booking.png" alt="Package Details & Booking">

### Check Availability
<img src="image/Check Availability.png" alt="Check Availability">

### Book Now
<img src="image/Book Now.png" alt="Book Now">

### My Bookings
<img src="image/My Bookings.png" alt="My Bookings">

### Dashboard (Package Owner)
<img src="image/Dashboard.png" alt="Dashboard">

### Package Listings
<img src="image/Package Listings.png" alt="Package Listings">

### Add Package
<img src="image/Add Package.png" alt="Add Package">

### Package Registration Form
<img src="image/Tour Package Seller Can Sell pakage after get Register.jpg" alt="Package Registration">

### AI Chatbot
<img src="image/ChatBot.jpg" alt="AI Chatbot">

### Email Verification
<img src="image/Verification code Email For Login or Delete account.jpg" alt="Email Verification">

### Booking Confirmation Email
<img src="image/createBooking Email.jpg" alt="Booking Confirmation Email">

### Experience Page
<img src="image/Experience.png" alt="Experience Page">

### About Page
<img src="image/About.png" alt="About Page">

[▲ Back to top](#-table-of-contents)

---

## 6. Conclusion
GHURBO is built for **real travelers and local providers** — combining curated experiences, modern UX, AI assistance, and secure booking. The stack and design choices make it **scalable and production-ready**.

---
