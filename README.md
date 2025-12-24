<h1 align="center">🛒 Abazeer — Enterprise E-Commerce Platform</h1>


<h3 align="center">A high-performance, scalable, and fully-featured e-commerce frontend built with modern technologies.</h3> <p align="center"> <img src="https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge" /> <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/License-Private-red?style=for-the-badge" /> <img src="https://img.shields.io/badge/Maintained-Yes-success?style=for-the-badge" /> <br/> <img src="https://img.shields.io/badge/React-18.0-61dafb?style=for-the-badge&logo=react" /> <img src="https://img.shields.io/badge/Next.js-Latest-black?style=for-the-badge&logo=next.js" /> <img src="https://img.shields.io/badge/TailwindCSS-3.x-38b2ac?style=for-the-badge&logo=tailwindcss" /> <img src="https://img.shields.io/badge/React%20Query-Latest-ff4154?style=for-the-badge&logo=reactquery" /> <img src="https://img.shields.io/badge/Tabby-Integrated-5a2dff?style=for-the-badge" /> <img src="https://img.shields.io/badge/Tamara-Integrated-ff69b4?style=for-the-badge" /> </p>

## Overview

Abazeer is a production-ready e-commerce frontend built with React and TypeScript.
The project focuses on scalability, clean architecture, and performance-aware patterns commonly used in real-world applications.
--------------------------------------------------------------------------
## Architecture & Engineering Focus
- Modular and scalable project structure
- Clear separation between UI, business logic, and data layers
- Centralized API handling with interceptors and unified error logic
- Predictable state management for complex flows (auth, cart, checkout)
- Performance-focused patterns (caching, pagination, debounced search)
--------------------------------------------------------------------------


🚀 Core Features

🔐 Authentication
- Secure token-based login & registration
- Password reset
- Session persistence
- Full validation & error handling

🛒 Cart & Checkout
- Smart & persistent cart
- Add / update / remove items
- Multi-step checkout
- Shipping, summary & review
- Coupon-ready structure

💳 Payment Integrations
Fully integrated with: 
- Tabby (Buy Now Pay Later)
- Tamara (Installments)
   Including:
  - Payment initiation
  - Redirect flow
  - Success & failure handling
  - Callback verification

🔍 Advanced Filtering 
- Price range
- Categories & brands
- Multiple filters at once
- Pagination
- Search with debounce
- Real-time synchronized UI

🔗 API Integration
- React Query caching & prefetching
- Axios interceptors
- Unified error & retry logic
- Optimized data fetching
- Production-grade API structure

📱 UI / UX
- Fully responsive
- Modern component architecture
- Smooth transitions
- Clean, user-friendly product browsing experience

--------------------------------------------------------------------------
## Why This Project
This project was built to simulate real-world frontend challenges found in large-scale e-commerce platforms,
including complex state flows, third-party payment integrations, and performance-critical user experiences.
--------------------------------------------------------------------------


📸 Screenshots

<div align="center"> <h2>🏠 Home Page</h2> <img src="https://github.com/user-attachments/assets/7f301dff-5e7c-453d-bb08-5eb51ce01e6a" width="100%" alt="Home Page" /> </div>
<div align="center"> <h2>🛍️ All Products Page</h2> <img src="https://github.com/user-attachments/assets/2dc1d5be-bf7b-4b7a-92d9-bcd8fe8554f1" width="100%" alt="All Products Page" /> </div>
<div align="center"> <h2>📄 Product Details Page</h2> <img src="https://github.com/user-attachments/assets/8a09e69d-3759-4d1c-b4bc-f940b7c868a1" width="100%" alt="Product Details Page" /> </div>
<div align="center"> <h2>🔐 Login Page</h2> <img src="https://github.com/user-attachments/assets/2b9a5b3f-b10c-437b-a052-7842abd1c9b6" width="100%" alt="Login Page" /> </div>
<div align="center"> <h2>📱 Home Page (Mobile Version)</h2> <img src="https://github.com/user-attachments/assets/91056a8d-2855-4ec8-b956-271867cbf971" width="35%" alt="Mobile View Home Page" /> </div>

--------------------------------------------------------------------------

🧱 Tech Stack
<p align="left"> <img src="https://skillicons.dev/icons?i=react,ts,tailwind,redux,vite,reactquery,git,github,figma" /> </p>

--------------------------------------------------------------------------
📁 Project Structure
src/
 ┣ features /
 ┣ common /   # reusable components and hooks 
 ┣ routes/ 
 ┣ types/     #global types
 ┣ data /     # constant data
 ┣ lib/ configruation for packages in the project ( Axios , i18n , tanstack react query )
 ┣ services/       # API Layer
 ┣ utils/
 ┣ store/
 ┗ styles/
 


--------------------------------------------------------------------------
⚙️ Installation
git clone https://github.com/magedElshafey/abazeer.git
cd abazeer
npm install
npm run dev

