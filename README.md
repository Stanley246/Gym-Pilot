# GymPilot — High‑Performance CRM Frontend

GymPilot is a premium, aggressive, productivity‑focused SaaS frontend built for fitness studios.  
This repository contains the static HTML/CSS/JS marketing site and Supabase authentication layer.

## 🚀 Tech Stack
- Plain HTML/CSS/JS
- Supabase (Auth + Profiles)
- GitHub Pages (Hosting)
- Clixio (White‑label CRM backend)

## 📁 Structure
/
├── index.html
├── features.html
├── pricing.html
├── login.html
├── styles.css
└── README.md

## 🔐 Authentication
GymPilot uses Supabase for:
- Email/password login
- Session management
- User profiles

To configure:
1. Create a Supabase project
2. Enable Email Auth
3. Copy your Project URL + anon key
4. Paste them into the Supabase client snippet in each HTML file

## 🌐 Deployment (GitHub Pages)
1. Go to **Settings → Pages**
2. Select **Deploy from branch**
3. Choose **main** and **/root**
4. Save
5. Your site will deploy automatically

## 🧩 Redirect to Clixio
After successful login, users are redirected to:

`https://app.gympilot.software`

## 🛠 Development
This is a static site.  
No build tools required.

## 📄 License
Proprietary — All rights reserved.
