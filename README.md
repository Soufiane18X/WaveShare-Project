Project Specification – Volunteering Web App (MERN Stack)
Project Name: WaveShare – Volunteer & Surf in Morocco

1. Project Overview
a. Context
In Morocco, surf houses often look for help with daily tasks in exchange for accommodation. At the same time, young people (Moroccan and international) seek unique, affordable experiences. Local associations also need volunteers. This platform will connect volunteers with hosts (surf houses, NGOs, youth centers), focusing on areas like Taghazout and Tamraght.
b. Main Goal
Develop a full-stack MERN application that:
Connects hosts (surf houses, NGOs) and volunteers.


Provides local and international opportunities.


Supports commission-based monetization.


Uses AI to help users (ex: match volunteers to tasks, auto-generate messages).


Works well on both desktop and mobile.



2. Target Users
Foreign travelers looking for volunteering in Morocco


Moroccan youth looking for local social involvement


Surf houses, hostels in Taghazout/Tamraght


Local NGOs and associations


 Platform admins



3. Core Features
a. Volunteer Features
Create account & profile


Browse and filter volunteering offers


Apply to a mission with optional AI-generated motivation message


Dashboard with upcoming missions and history


b. Host Features
Register as a host (Surf house or NGO)


Post, edit, or delete volunteering opportunities


View applications and manage accepted volunteers


Option to boost/pin listings (paid feature)


c. Admin Features
Manage users and host accounts


Moderate posted opportunities


View basic platform stats (users, activity, etc.)



4. Technical Stack
Layer
Technology
Frontend
React.js + Tailwind CSS(Shadcn)
Backend
Node.js + Express.js
Database
MongoDB (MongoDB Atlas)
Auth
JWT + Bcrypt
AI Integration
(later)
OpenAI API (GPT)
Payment (later)
Stripe API (for commissions or boosts)
Deployment
Vercel (frontend) + Render or Railway (backend)


5. Business Model
💰 Commission: 10–15% on each confirmed volunteer stay (paid by host or volunteer)


⭐ Boosted Listings: Hosts can pay to pin their offers


🛂 Premium Profiles: In the future, verified profiles with higher visibility


🎁 Freemium Access: Basic features free, advanced matching and visibility paid



6. Sprint Plan (3 Sprints)
🚀 Sprint 1: Foundation & Core
Project setup (frontend/backend)


Authentication (login/signup with roles)


Volunteer & host profiles


Create/read/update/delete (CRUD) for volunteering opportunities


🔍 Sprint 2: AI + Matching + Dashboard
AI-based message generator for applications


Matching logic (recommendation system)


User dashboard (volunteer & host)


Admin panel (basic)


💸 Sprint 3: Commission + Final Touches
Stripe integration (test mode)


Boosted listing logic (optional upgrade)


Testing (manual), bug fixes


Deployment (Vercel + Render), final documentation & demo



7. Constraints
Mobile-first responsive design


User data privacy (no public emails, GDPR-ready)


Clear UI for non-tech-savvy users


Multi-language support (EN/FR) planned for later version



8. Deliverables
Full GitHub repo (frontend + backend)


Project presentation and live demo


Final documentation (code, setup, sprint retrospectives)


PDF version of this specification



