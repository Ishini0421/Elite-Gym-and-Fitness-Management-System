<div align="center">

# ELITE Gym & Fitness Management

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF6F00?style=for-the-badge)
![Stripe](https://img.shields.io/badge/Stripe-Payments-6772E5?style=for-the-badge&logo=stripe&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-Auth-6C47FF?style=for-the-badge)
![Vapi](https://img.shields.io/badge/Vapi-Voice_AI-00D9FF?style=for-the-badge)

**🇱🇰 AI-Driven Digital Gym Platform for Sri Lanka**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Vercel-black?style=for-the-badge)](https://elite-gym-and-fitness.vercel.app)

[Overview](#overview) • [Features](#features) • [Tech Stack](#tech-stack) • [Installation](#installation) • [Usage](#usage) • [Contributing](#contributing)

</div>

---

## Overview

**ELITE Gym & Fitness Management** is a full-stack platform designed to **modernize gym operations** and provide **personalized fitness experiences**. From membership management and AI-driven workout plans to trainer scheduling and e-commerce, ELITE covers everything a modern fitness business needs.

Built with **Next.js 15**, **Convex**, **Stripe**, **Clerk**, and **Vapi AI**, this system is tailored for **gym owners, trainers, and members** in Sri Lanka, offering seamless AI-powered solutions for workouts, diet plans, bookings, and payments.

---

## Features

### **AI Fitness Experience**
- Conversational voice interaction with **Vapi AI**  
- Personalized workout and diet plans via **Google Gemini AI**  
- Real-time transcript display during voice consultation  
- Auto-generated plans synced to member profiles  

### **Membership & Subscription Management**
- Flexible tiers: Basic, Premium, Elite  
- Stripe-powered recurring billing  
- Member dashboards with progress tracking  
- QR code check-ins (coming soon)  

### **Trainer Management**
- Apply and create detailed trainer profiles  
- Real-time session booking and schedule tracking  
- Admin-controlled approvals and salary management  

### **Marketplace**
- Browse and purchase gym products (equipment, supplements, apparel)  
- Secure Stripe checkout  
- Admin inventory management and order history  
- User reviews and ratings  

### **Security & Authentication**
- Clerk-powered authentication with social login  
- Role-based access control: Users, Trainers, Admins  
- Protected routes and secure session handling  

### **Admin Tools**
- Full user and membership management  
- Analytics dashboards for subscriptions and revenue  
- Blog & recipe content management  
- System configuration and platform settings  

### **Mobile-Optimized UI**
- Responsive, touch-friendly design  
- Light/Dark theme toggle with **next-themes**  
- Fast load times with **Turbopack**  
- Modern UI components via **shadcn/ui**

---

## Tech Stack

| Layer | Technology | Purpose |
|-------|------------|---------|
| Frontend | Next.js 15 + React 19 + TypeScript | Modern, fast, component-based web UI |
| Styling | TailwindCSS + shadcn/ui | Utility-first responsive design |
| Backend | Convex | Real-time backend and database |
| Auth | Clerk | User authentication & role management |
| Payments | Stripe | Membership, bookings, and marketplace |
| AI & Voice | Vapi Voice AI + Google Gemini AI | Conversational fitness plans |
| Deployment | Vercel + Edge Functions | Scalable hosting and low-latency routing |

---

## Installation

**Prerequisites**
- Node.js 18+
- npm / yarn / pnpm
- Convex, Stripe, Clerk, Google Gemini, Vapi accounts

**Setup**
```bash
git clone https://github.com/Ishini0421/Elite-Gym-and-Fitness-Management-System.git
cd Elite-Gym-and-Fitness-Management-System

npm install
# or yarn / pnpm install

# Create .env.local and add your keys
