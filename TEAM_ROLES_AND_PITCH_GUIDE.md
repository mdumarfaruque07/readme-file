# 🏛️ SanskritiGO (संस्कृतिGO) — 6-Member Team Roles, Preparation Guide & Hackathon Pitch Masterplan

> **Problem Statement ID:** SIH 26197 | **Ministry of Tourism & Culture**  
> **Project:** SanskritiGO (National Heritage, Living Culture & Verified Artisan Ecosystem)  
> **Team Composition:** 6 Members | **Target Presentation Time:** 8–10 Minutes + Jury Q&A

---

## 🎯 Executive Overview: How Evaluators Judge a 6-Member Team

In top-tier hackathons like the **Smart India Hackathon (SIH)**, juries look for:
1. **Clear Division of Ownership:** No two members should overlap; every person must own a core engineering or product pillar.
2. **Smooth Transitions:** No awkward pauses like *"Ab agla banda bolega"*. Transitions must be seamless.
3. **Evidence of Real Work:** Evaluators often pick individual members and ask: *"Where in the codebase did you write this?"* or *"Explain this database relation."*
4. **Live Proof & Resilience:** A real live demo on both Web and Mobile (Android APK) backed by an anti-crash offline fallback.

---

## ⏱️ The 10-Minute Winning Pitch Flow (Timeline)

| Time | Presenter | Module Covered | Key Visual on Screen |
| :--- | :--- | :--- | :--- |
| **0:00 – 1:30** | **Member 1 (Team Lead)** | The Hook, Problem Statement & Architecture Vision | Landing page hero, mission statement, high-level impact |
| **1:30 – 3:00** | **Member 2 (Frontend Lead)** | Tourist Experience, Multi-Lingual Engine & Audio Chronicles | Live language switch, audio narrative, 3D monument viewer |
| **3:00 – 4:30** | **Member 3 (Backend & DB)** | Node.js Server, Prisma ORM & MySQL Cloud Architecture | API endpoints, database schema, Prisma migrations |
| **4:30 – 6:00** | **Member 4 (AI/GenAI Lead)** | Groq Multi-Model LLM & Cultural Lore Auto-Discovery | Admin AI Auto-Discovery, YouTube documentary generator |
| **6:00 – 7:30** | **Member 5 (Mobile Lead)** | Native Android APK, Geolocation & Camera Hardware | Real Android phone screen mirror, GPS radius calculation |
| **7:30 – 9:00** | **Member 6 (Admin & Security)** | Physical Shop Verification, Zero-Delivery Anti-Scam Model & Grievance Cell | Admin approval dossier, Pehchan ID validation, support tickets |
| **9:00 – 10:00** | **Member 1 (Team Lead)** | Monetization, Scalability, Government ROI & Closing | Subscription tiers, 0% commission model, Q&A handoff |

---

---

## 👤 Member 1: Team Lead & Product Visionary (The Pitcher & Anchor)

### 📌 Role Title:
**Team Lead, Product Strategist & Master Anchor**

### 🎯 Primary Responsibilities:
- Sets the emotional hook and cultural importance of preserving India's living heritage.
- Explains the core problem (unverified fake souvenirs, courier scams, language barriers for international tourists, lack of footfall to authentic hereditary weavers).
- Controls the slide deck/screen transitions and anchors the presentation time.
- Explains the **Business Model, Artisan Monetization (Subscription plans), and Government ROI**.
- Directs technical jury questions to the appropriate specialist teammate.

### 📂 Code & Files to Master:
- [README.md](file:///c:/Users/Mduma/Downloads/SIH26197/README.md) — Overall project documentation and problem statement.
- [client/src/App.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/App.jsx) — App structure and routing architecture.
- [client/src/pages/HomePage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/HomePage.jsx) — Hero section, live radar widget, ODOP showcase.

### 🎤 Live Pitch Script (Opening 90 Seconds):
> *"Respected Jury members, India has over 3,600 Centrally Protected Monuments and millions of traditional artisans. Yet, a tourist visiting the Taj Mahal or Varanasi often gets trapped by unauthorized touts selling counterfeit plastic replicas, while the real National-Award-winning hereditary weaver sitting 800 meters away in a gali receives zero footfall.*  
>  
> *Existing apps only sell courier deliveries where delivery scams frequently ruin the tourist experience. Introducing **SanskritiGO** — a unified digital ecosystem connecting tourists directly to monuments, audio chronicles in 10+ languages, and physically verified master artisan workshops with 100% in-store transparency and zero courier fraud. Let my team demonstrate how we built this."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: How does this make money? (Business Model)**
   - **Answer:** *"We do NOT charge sales commissions (0% cut) from poor artisans. Instead, verified workshops pay an affordable monthly/annual listing subscription (Silver, Gold, Platinum) for prime discovery around monuments. Premium subscription covers physical audit costs, giving predictable revenue for the platform."*
2. **Q: What is the benefit for the Government / Ministry of Tourism?**
   - **Answer:** *"It directly supports the Prime Minister's ODOP (One District One Product) and 'Vocal for Local' initiatives, boosts formal digital footfall tracking via GPS, and integrates with the Ministry of Textiles Pehchan Registry."*

---

---

## 👤 Member 2: Frontend Lead & Cultural UX Designer (Web Experience)

### 📌 Role Title:
**Lead Frontend Architect & Cultural UX Specialist**

### 🎯 Primary Responsibilities:
- Owns the React + Vite single-page application structure.
- Explains the responsive design system (Glassmorphism, Tailwind/Vanilla CSS tokens, Lucide icons).
- Demonstrates the **Bilingual / Multi-lingual localization engine (English, Hindi, Bengali, Tamil, etc.)**.
- Demonstrates the interactive **Leaflet Map**, **3D Monument visualizer**, and **Web Speech API Audio Narration**.

### 📂 Code & Files to Master:
- [client/src/context/LanguageContext.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/context/LanguageContext.jsx) — Localization state and dictionary mappings.
- [client/src/pages/PlaceDetailPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/PlaceDetailPage.jsx) — Audio chronicle player, 1-day walking trails, media links.
- [client/src/pages/MapPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/MapPage.jsx) — Leaflet interactive map with custom colored monument pins.
- [client/src/components/AudioNarrationPlayer.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/AudioNarrationPlayer.jsx) — Audio speed controller & narration engine.

### 🎤 Live Demo Script (90 Seconds):
> *"I built the client experience with React 18 and Vite. Our UX prioritizes cultural immersion:  
> 1. With one tap on the top language pill, the entire interface switches between Hindi and English seamlessly via our `LanguageContext`.  
> 2. On the monument page, our built-in Audio Guide uses the browser's speech synthesis with speed control (0.8x, 1.0x, 1.25x), allowing tourists to listen to verified ASI historical lore hands-free while walking around the site.  
> 3. We built categorized interactive maps where monuments, sacred ghats, and royal forts have custom color pins with radial distance calculation."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: How does the language toggle work without reloading the page?**
   - **Answer:** *"We use React Context API (`LanguageContext`) with reactive dictionary mappings and bilingual database columns (`name` and `nameHi`, `shortLore` and `shortLoreHi`). Toggling updates state globally in milliseconds without network re-fetching."*
2. **Q: Is the website responsive on mobile browsers?**
   - **Answer:** *"Yes, we tested it with responsive breakpoints from 360px mobile viewports up to 4K displays, with mobile-first sliding bottom sheets and thumb-friendly touch targets."*

---

---

## 👤 Member 3: Backend & Database Architect (Server & Cloud Engineer)

### 📌 Role Title:
**Backend & Cloud Database Architect**

### 🎯 Primary Responsibilities:
- Owns the Express.js REST API server and Prisma ORM configuration.
- Explains the **MySQL Database Schema** hosted on Aiven Cloud with local fallbacks.
- Explains security: JWT authentication, bcrypt password hashing (10 rounds), connection pooling, and connection timeout resilience (`connect_timeout=30`, `pool_timeout=30`).
- Demonstrates API routing, error handling, and file upload middlewares (Multer).

### 📂 Code & Files to Master:
- [server/prisma/schema.prisma](file:///c:/Users/Mduma/Downloads/SIH26197/server/prisma/schema.prisma) — Database models (`User`, `Place`, `Product`, `Post`, `Bookmark`, `MediaLink`).
- [server/src/prisma.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/prisma.js) — Sanitized database connection string & pool management.
- [server/src/controllers/authController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/authController.js) — JWT login/registration logic.
- [server/src/controllers/productController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/productController.js) — Craft listing API with food policy restrictions.

### 🎤 Live Demo Script (90 Seconds):
> *"Our backend is powered by Node.js, Express, and Prisma ORM connected to MySQL on Aiven Cloud.  
> 1. Our schema enforces relational integrity across 6 normalized models: `User`, `Place`, `Product`, `Post`, `Bookmark`, and `MediaLink`.  
> 2. Passwords are encrypted using bcrypt with salt rounds of 10, and API requests are guarded with stateless JWT bearer tokens.  
> 3. For cloud stability, our Prisma client features automated connection pool sanitization with a 30-second connection timeout, ensuring zero connection dropouts during network fluctuations."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Why Prisma ORM over raw SQL queries?**
   - **Answer:** *"Prisma provides compile-time type safety, automated schema migrations (`prisma migrate`), prevents SQL injection attacks by auto-parameterizing queries, and makes complex relational queries (like fetching a monument with its products and media links) clean and maintainable."*
2. **Q: What happens if the database connection drops or experiences high latency?**
   - **Answer:** *"Our client features a 25-second axios resilience window, and our services have built-in offline cached fallbacks (`FALLBACK_PLACES`, `FALLBACK_PRODUCTS`), meaning the app remains 100% operational even during a temporary cloud outage."*

---

---

## 👤 Member 4: AI & Cultural Intelligence Engineer (LLM & GenAI Specialist)

### 📌 Role Title:
**AI / GenAI & Heritage Intelligence Engineer**

### 🎯 Primary Responsibilities:
- Owns the integration with **Groq Multi-Model Cloud API (LLaMA-3 / Mixtral-8x7b)**.
- Explains the **Admin AI Auto-Discovery Engine** (how 1 monument name automatically discovers rich cultural lore, verified YouTube documentaries, and Bollywood cinema links).
- Demonstrates prompt engineering techniques that prevent AI hallucinations and enforce ASI historical authenticity.
- Explains image processing and content moderation safeguards.

### 📂 Code & Files to Master:
- [server/src/utils/groqClient.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/utils/groqClient.js) — Groq LLM API caller and prompt templates.
- [server/src/controllers/adminController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/adminController.js) — `aiDiscoverCulturalLinks` function.
- [client/src/pages/AdminPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/AdminPage.jsx) — `handleAiAutoDiscover` UI trigger button.

### 🎤 Live Demo Script (90 Seconds):
> *"Curating accurate cultural lore manually for thousands of monuments is a huge bottleneck for tourism departments. To solve this, I built the **AI Cultural Auto-Discovery Engine** powered by Groq's high-speed inference:  
> 1. In the Admin Dashboard, the officer merely enters a monument name—say, 'Amer Fort'—and clicks 'AI Auto-Discover'.  
> 2. Our LLM pipeline generates verified architectural history, identifies authentic YouTube documentaries, and finds historic cinema shots (like Jodhaa Akbar) within 1.5 seconds!  
> 3. The officer reviews the generated chronicle, edits if needed, and publishes it with one click."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: How do you prevent GenAI hallucinations in historical facts?**
   - **Answer:** *"We use strict system prompting with temperature set to 0.2 for deterministic factual output, enforce structured JSON schema formatting, and place a mandatory Human-In-The-Loop (Admin officer verification) before any AI-generated data is published live to tourists."*
2. **Q: Why Groq API instead of standard OpenAI?**
   - **Answer:** *"Groq's LPU (Language Processing Unit) architecture delivers generation speeds of 500+ tokens per second with near-instant sub-second response times at a fraction of the cost, making it ideal for scalable government applications."*

---

---

## 👤 Member 5: Mobile Systems & Native Integration Engineer (Android Lead)

### 📌 Role Title:
**Mobile Systems & Native Integration Engineer**

### 🎯 Primary Responsibilities:
- Owns the **Capacitor Android Native Application** and Gradle build pipeline.
- Explains hardware integration: **Native Camera API** for artisan craft photos and **Geolocation GPS API** for near-monument radar.
- Explains packaging: `app-debug.apk` generation, asset synchronization, permissions handling (`CAMERA`, `ACCESS_FINE_LOCATION`).
- Demonstrates the live application running on an actual Android device or emulator.

### 📂 Code & Files to Master:
- [client/capacitor.config.json](file:///c:/Users/Mduma/Downloads/SIH26197/client/capacitor.config.json) — Capacitor app configuration.
- [client/android/app/build.gradle](file:///c:/Users/Mduma/Downloads/SIH26197/client/android/app/build.gradle) — Android build configuration and SDK versions.
- [client/src/pages/ArtisanPortalPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/ArtisanPortalPage.jsx) — Camera capture handlers (`takePhotoWithCamera`, `CameraPlugin`).
- [SanskritiGO-debug.apk](file:///c:/Users/Mduma/Downloads/SIH26197/SanskritiGO-debug.apk) — Compiled Android package file (~10.1 MB).

### 🎤 Live Demo Script (90 Seconds):
> *"To ensure every tourist and artisan across India has access—even in rural craft clusters—we compiled SanskritiGO into a lightweight native Android APK (10.1 MB) using Capacitor:  
> 1. An artisan doesn't need a computer. They open the app, tap 'Snap Craft Photo', which directly invokes the native Android camera hardware to capture their handmade item.  
> 2. On the tourist side, our app uses native GPS to calculate the exact walking distance (e.g., 350 meters from Taj West Gate) to verified artisan workshops.  
> 3. Our APK compiles cleanly via Gradle wrapper with zero legacy Cordova dependencies."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Why Capacitor instead of Flutter or React Native?**
   - **Answer:** *"Capacitor allows 100% codebase reuse between Web and Mobile while still providing direct native bridge access to device hardware (Camera, GPS, Biometrics). This drastically cuts maintenance overhead for government agencies and ensures updates reflect simultaneously on both platforms."*
2. **Q: What is the minimum Android version supported?**
   - **Answer:** *"Our app targets Android API 22+ (Android 5.1 Lollipop up to Android 14), covering more than 99% of all active Android smartphones in India."*

---

---

## 👤 Member 6: Security, Compliance & Government Operations Lead (QA & Admin)

### 📌 Role Title:
**Security, Compliance & Government Admin Operations Lead**

### 🎯 Primary Responsibilities:
- Owns the **Artisan Physical Verification Workflow & Gatekeeper Security**.
- Explains the **Anti-Scam Zero-Delivery Policy** (why courier checkout was removed to protect tourists from replica scams and ensure 100% money goes to the artisan in-store).
- Explains the **Ministry of Textiles Pehchan ID validation** and District Industries Centre (DIC) verification audit.
- Demonstrates the **Government Admin Dashboard (`/admin`)**, approving pending artisan dossiers, and the **Citizen Grievance Support Desk (`/api/support/report`)**.

### 📂 Code & Files to Master:
- [client/src/pages/AdminPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/AdminPage.jsx) — Artisan approval table, Dossier modal, Approve/Reject handlers.
- [client/src/pages/ArtisanPortalPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/ArtisanPortalPage.jsx) — 4-Step Pending Tracker, Pehchan ID registry validation.
- [server/src/controllers/artisanController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/artisanController.js) — Server persistence of verification applications.
- [server/src/controllers/supportController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/supportController.js) — Digital grievance tickets (`ASI-GRV-...`).

### 🎤 Live Demo Script (90 Seconds):
> *"A major issue in tourism is fraudulent sellers listing mass-produced factory items as authentic handicrafts. In SanskritiGO, we implemented a strict 4-step Physical Verification Gatekeeper:  
> 1. An artisan cannot publish items simply by creating an account. They must submit their physical workshop address, nearest monument distance, and Ministry of Textiles Pehchan ID.  
> 2. The seller is locked in a 4-step progress review until a Government Tourism Officer verifies the dossier in the Admin Panel.  
> 3. Once approved, they select a subscription plan, unlocking their physical shop catalog.  
> 4. We deliberately eliminated courier delivery: tourists visit the workshop in-person, verify the craft with their own eyes, and pay the artisan directly via UPI with 0% platform commission."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Why eliminate online delivery? Won't that reduce sales?**
   - **Answer:** *"Authentic heritage crafts (like a ₹25,000 pure silk Kashi saree or marble inlay) are high-value touch-and-feel goods. Online courier models suffer from high return fraud, courier transit damage, and counterfeit substitution scams. Experiential tourism encourages visitors to walk into the artisan's workshop, creating a personal emotional connection and guaranteeing 100% authentic sales."*
2. **Q: How does a tourist report a grievance or fraudulent shop?**
   - **Answer:** *"Through our built-in Support Desk in Settings, tourists can file an official grievance ticket with photo attachments (`ASI-GRV-...`). These tickets are reviewed by tourism administrators who can revoke a workshop's certified status instantly."*

---

---

## 📋 Master Cheat Sheet: Team Roles Summary Table

| Member | Formal Title | Code Modules Owned | Live Demo Action | Secret Weapon / Pitch Line |
| :---: | :--- | :--- | :--- | :--- |
| **M1** | **Team Lead & Product Strategist** | Pitch Deck, Business Model, Strategy | Controls intro, problem hook & monetization | *"0% Commission on artisans + verified tourist footfall."* |
| **M2** | **Frontend & Cultural UX Lead** | React 18, Vite, UI, i18n Localization | Toggles Hindi/English, plays Audio Guide | *"Hands-free audio guide in 10+ languages."* |
| **M3** | **Backend & Database Architect** | Express, Prisma ORM, MySQL Cloud | Shows API calls & MySQL database schema | *"Prisma type-safety with 30s cloud pool resilience."* |
| **M4** | **AI & Heritage Intelligence Lead** | Groq LLaMA-3, GenAI Prompting | Clicks 'AI Auto-Discover' on Admin page | *"1.5-second automated cultural lore & YouTube curation."* |
| **M5** | **Mobile Systems (Android) Lead** | Capacitor, Gradle, Native APIs, Camera | Live Android phone demo & camera photo snap | *"10.1 MB native APK compiled cleanly for rural India."* |
| **M6** | **Security & Admin Operations Lead** | Verification Gate, Anti-Scam, Support | Approves pending workshop dossier in Admin | *"Zero courier fraud: 100% in-shop verified artisan visits."* |

---

## 🏆 Golden Rules for Hackathon Presentation Day

1. **The 3-Second Rule:** When passing the speaking turn to your teammate, do it naturally with their name and title:
   - *Example: "Now our Backend Architect, [Member 3], will explain our cloud database design."*
2. **Never Say "I Don't Know":** If a judge asks you something outside your assigned domain, politely redirect:
   - *Example: "That relates to our mobile hardware integration; my teammate [Member 5], who led our Android build, can explain that exact implementation."*
3. **Keep the Servers Pre-Warmed:**
   - Both `npm run dev` in `client` and `node src/server.js` in `server` should be running before the judges arrive at your table.
   - Keep `SanskritiGO-debug.apk` already installed on at least 1 real Android smartphone.
4. **Show, Don't Just Tell:** Whenever you make a claim, show the proof on screen (the live database table, the running APK, the AI output).

---

*All files, documentation, and the compiled APK are ready for evaluation in the workspace root.*
