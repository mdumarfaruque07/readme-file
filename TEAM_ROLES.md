# 🏛️ SanskritiKhoj (संस्कृति खोज) — 6-Member Team Roles & Hackathon Preparation Guide

> **Problem Statement ID:** SIH 26197 | **Ministry of Tourism & Culture**  
> **Project:** SanskritiKhoj (National Heritage, Living Culture & Verified Artisan Ecosystem)  
> **Team Composition:** 6 Members | **Target Presentation Time:** 8–10 Minutes + Jury Q&A  

---

## 🎯 Executive Overview: Judges Kya Dekhte Hain?

In prestigious hackathons like Smart India Hackathon (SIH), evaluators look for:
1. **Clear Division of Ownership:** Har member ka apna distinct domain ho (Frontend, Backend, AI, Mobile, Artisan/Marketplace, Product Lead). Koi overlap ya confusion na ho.
2. **Technical Mastery:** Har member apne assigned files ko line-by-line samjha sake aur live code dikha sake.
3. **Smooth Transitions:** Ek member se doosre tak conversation natural flow kare, bina awkward pause ke.
4. **Live Working Proof:** Sirf slides nahi, balki live Web browser demo, live terminal API hits, real MySQL database relations, aur native Android APK hardware demo.

---

## ⏱️ The 10-Minute Winning Pitch Flow

| Time | Presenter | Domain & Module | Screen Par Kya Dikhana Hai |
| :--- | :--- | :--- | :--- |
| **0:00 – 1:30** | **Member 1 (Team Lead & Strategist)** | The Hook, Problem Statement, Vision & Architecture | Landing Page hero, Problem hook, High-level architecture |
| **1:30 – 3:00** | **Member 2 (Frontend & UX Lead)** | Tourist Experience, Multi-Lingual Engine & Audio Guide | Live Hindi/English toggle, Audio narration player, Leaflet map |
| **3:00 – 4:30** | **Member 3 (Backend & Database Architect)** | Node.js Server, Prisma ORM & MySQL Relational Schema | Live terminal API curl/fetch, Prisma schema, 9 tables |
| **4:30 – 6:00** | **Member 4 (AI & Cultural Intelligence)** | Groq LLM Cultural Discovery & Prompt Engineering | Admin Panel → Enter monument name → Live AI Auto-Discover |
| **6:00 – 7:30** | **Member 5 (Artisan Ecosystem & Commerce)** | Verified ODOP Bazaar, In-Store Discovery & Pehchan ID | Bazaar page, Direct WhatsApp inquiry, Artisan 4-step portal |
| **7:30 – 9:00** | **Member 6 (Mobile Systems & DevOps Lead)** | Android APK, Hardware GPS Radar, Camera & Resilience | Real Android phone screen, GPS proximity radar, Support tickets |
| **9:00 – 10:00** | **Member 1 (Team Lead)** | Monetization, Government Alignment, Scalability & Closing | 0% commission + Subscription model, PM ODOP alignment, Q&A |

---

---

# 👤 MEMBER 1: Team Lead & Product Visionary (The Anchor)

### 📌 Role Title:
**Team Lead, Product Strategist & Master Anchor**

### 🎯 Primary Responsibilities:
- **Pitch Opening:** Pehle 90 seconds mein emotional aur practical hook create karna.
- **Problem Statement:** Real pain points explain karna (unverified touts selling plastic replicas, lack of footfall to authentic weavers, courier delivery scams).
- **System Vision:** Explain karna ki SanskritiKhoj kaise tourism, culture, aur local economy ko digitally jodata hai.
- **Business Model & Government ROI:** Monetization, 0% commission model, ODOP alignment samjhana.
- **Q&A Coordinator:** Agar judge technical question pooche, toh politely right team member ko question pass karna.

### 📂 Code & Files to Master:
- [README.md](file:///c:/Users/Mduma/Downloads/SIH26197/README.md) — Complete project context and mission.
- [client/src/App.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/App.jsx) — App structure and routing architecture.
- [server/src/server.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/server.js) — Mounted API routes overview.
- [server/prisma/schema.prisma](file:///c:/Users/Mduma/Downloads/SIH26197/server/prisma/schema.prisma) — High-level database schema overview.

### 🎤 Live Pitch Script (Opening 90 Seconds):
> *"Respected Jury members, India has over 3,600 Centrally Protected Monuments and millions of traditional artisans. Yet, a tourist visiting the Taj Mahal or Varanasi is frequently misled by unauthorized touts selling machine-made plastic souvenirs, while the real National-Award-winning hereditary weaver sitting 800 meters away in an alley receives zero footfall.*
>
> *Existing e-commerce apps rely on courier delivery where counterfeit substitution and transit damage are rampant. Introducing **SanskritiKhoj (संस्कृति खोज)** — a unified national heritage ecosystem that directly guides tourists to verified heritage monuments, offers multilingual audio chronicles, and connects them directly to physically verified artisan workshops with 100% in-store authenticity and zero courier fraud.*
>
> *Let my team demonstrate the engineering behind this platform."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: How does the platform sustain financially if you charge 0% commission on crafts?**
   - **Answer:** *"We believe artisans should keep 100% of their earnings. Our revenue comes from workshop subscription tiers (Silver ₹299/mo, Gold ₹599/mo, Platinum ₹999/mo) for enhanced discoverability and verified badges around monuments. We also offer institutional enterprise licensing for state tourism boards."*
2. **Q: How does this align with Government of India priorities?**
   - **Answer:** *"It directly operationalizes the Hon'ble PM's ODOP (One District One Product) and 'Vocal for Local' initiatives, validates Ministry of Textiles Pehchan IDs, and provides geo-tagged tourist footfall analytics to the Ministry of Tourism."*

### 📋 Member 1 Preparation Checklist:
- [ ] Memorize the 90-second opening hook and 60-second closing pitch.
- [ ] Learn the names and exact domains of all 5 teammates for seamless transitions.
- [ ] Understand the 3 revenue pillars (Subscriptions, Tourism Board licensing, Sponsored heritage trails).

---

---

# 👤 MEMBER 2: Frontend Lead & Cultural UX Designer

### 📌 Role Title:
**Lead Frontend Architect & Cultural UX Specialist**

### 🎯 Primary Responsibilities:
- **Client Architecture:** React 18, Vite, routing structure, responsive design.
- **Bilingual & Localization Engine:** Real-time English ⟷ Hindi switching via `LanguageContext` without page reloads.
- **Audio Heritage Guide:** Web Speech API integration with variable speed control (0.8x, 1.0x, 1.25x).
- **Interactive Mapping:** Leaflet-based heritage map with category-specific map pins and popups.
- **Visual Design:** Glassmorphic modern aesthetic, responsive mobile navigation drawer, and bottom navigation.

### 📂 Code & Files to Master:
- [client/src/context/LanguageContext.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/context/LanguageContext.jsx) — Bilingual state and translation maps.
- [client/src/pages/PlaceDetailPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/PlaceDetailPage.jsx) — Monument audio player, 1-day walking trails, media links.
- [client/src/pages/MapPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/MapPage.jsx) — Leaflet interactive map implementation.
- [client/src/components/AudioNarrationPlayer.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/AudioNarrationPlayer.jsx) — Web Speech synthesis logic.
- [client/src/components/Navbar.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/Navbar.jsx) — Header bar with language pill switcher.

### 🎤 Live Demo Script (90 Seconds):
> *"I built the client application using React 18 and Vite with a focus on immersive cultural UX:*
>
> *1. Notice our header language toggle: with a single tap, the entire application switches seamlessly between English and Hindi. This is powered by our `LanguageContext` which reactive-updates UI strings and bilingual database fields (`nameHi`, `shortLoreHi`) without refreshing the page.*
>
> *2. On any monument page, our built-in Audio Guide uses the browser's native Web Speech Synthesis API. Tourists can plug in headphones and listen to curated historical narratives hands-free while walking around the monument, with adjustable speeds (0.8x to 1.25x).*
>
> *3. Our interactive map renders categorized pins (Forts, Temples, Caves, Ghats) with dynamic popup summaries and direct walking navigation links."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Does the audio narration consume high internet bandwidth?**
   - **Answer:** *"No! We utilize the device's native Web Speech Synthesis API (`window.speechSynthesis`). Once the text lore loads, speech generation occurs locally on the client's device, requiring zero audio streaming bandwidth."*
2. **Q: How is UI responsiveness handled across devices?**
   - **Answer:** *"We use mobile-first CSS breakpoints. On mobile screens, the interface adapts with a persistent thumb-friendly bottom navigation bar and sliding touch drawers, while expanding to a multi-column dashboard on desktops."*

### 📋 Member 2 Preparation Checklist:
- [ ] Practice live language toggle demonstration (English ⟷ Hindi).
- [ ] Practice triggering the Audio Narration player on Taj Mahal or Amer Fort.
- [ ] Understand how `LanguageContext` provides `lang` and `t()` globally.

---

---

# 👤 MEMBER 3: Backend & Database Architect

### 📌 Role Title:
**Backend Engineer & Cloud Database Architect**

### 🎯 Primary Responsibilities:
- **Server Architecture:** Express.js REST API with structured controllers, routes, and middleware.
- **Relational Database Design:** 9 normalized MySQL models managed via Prisma ORM.
- **Security & Authentication:** Password encryption with bcrypt (10 rounds), stateless JWT authentication, and admin role gates.
- **Data Integrity:** Cascading deletes, foreign key relations, connection pooling, and connection resilience.
- **API Performance:** Clean endpoint design with pagination, search query filtering, and calculated ratings.

### 📂 Code & Files to Master:
- [server/prisma/schema.prisma](file:///c:/Users/Mduma/Downloads/SIH26197/server/prisma/schema.prisma) — 9 models: `User`, `Place`, `MediaLink`, `Post`, `Bookmark`, `Product`, `Food`, `ArtisanApplication`, `SupportTicket`.
- [server/src/server.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/server.js) — Express server initialization and middleware chain.
- [server/src/prisma.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/prisma.js) — Prisma client instance & connection management.
- [server/src/controllers/authController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/authController.js) — Registration, JWT login, and profile logic.
- [server/prisma/seed.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/prisma/seed.js) — Database seeding script with realistic heritage data.

### 🎤 Live Demo Script (90 Seconds):
> *"Our backend is powered by Node.js, Express, and Prisma ORM connected to a relational MySQL database:*
>
> *1. Our database schema enforces relational integrity across 9 distinct models: Users, Places, MediaLinks, Posts, Bookmarks, Products, Foods, ArtisanApplications, and SupportTickets.*
>
> *2. User authentication utilizes bcrypt hashing with 10 salt rounds and issue stateless JWT bearer tokens. Protected routes, like admin controls and artisan verification, are shielded by role-based authorization middlewares.*
>
> *3. Using Prisma ORM gives us compile-time type safety, zero SQL injection vulnerability, and automated migrations. For example, when fetching a heritage site, Prisma performs an optimized relational query that joins verified artisan crafts, media documentaries, and community reviews in a single clean payload."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Why Prisma ORM instead of raw SQL queries or MongoDB?**
   - **Answer:** *"Heritage data is inherently relational: a Monument has multiple MediaLinks, ODOP Products, Culinary lore, and Community Posts. MySQL guarantees ACID compliance and referential integrity, while Prisma prevents SQL injection attacks through automatic parameterization and provides clean, type-safe query building."*
2. **Q: How does the system handle high traffic or database disconnections?**
   - **Answer:** *"Prisma handles connection pooling automatically. Furthermore, our frontend client incorporates smart fallback caching (`FALLBACK_PLACES`, `FALLBACK_PRODUCTS`), ensuring the application never displays a blank error screen even under transient network latency."*

### 📋 Member 3 Preparation Checklist:
- [ ] Memorize all 9 models in `schema.prisma` and their foreign key relationships.
- [ ] Have a terminal ready to demonstrate an API call using `curl` or Postman (`GET /api/places`).
- [ ] Understand the JWT verification middleware flow (`verifyToken` & `requireAdmin`).

---

---

# 👤 MEMBER 4: AI & Cultural Intelligence Engineer

### 📌 Role Title:
**AI / GenAI & Heritage Intelligence Engineer**

### 🎯 Primary Responsibilities:
- **Groq LLM Integration:** High-speed inference using state-of-the-art open models (LLaMA-3 / Mixtral / GPT-OSS).
- **AI Cultural Auto-Discovery Engine:** Automating cultural lore generation, architecture summaries, and verified media linking for any heritage site.
- **Prompt Engineering & Hallucination Prevention:** Enforcing strict JSON schema output, system persona anchoring, and temperature control (0.3).
- **Human-in-the-Loop Safeguard:** Ensuring no AI-generated data is directly published without tourism officer review in the Admin Panel.
- **Heuristic Fallback Engine:** Algorithmic fallback if external AI APIs encounter rate limits or network downtime.

### 📂 Code & Files to Master:
- [server/src/controllers/adminController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/adminController.js) — `aiDiscoverCulturalLinks` function (line 201–326).
- [client/src/pages/AdminPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/AdminPage.jsx) — Admin UI trigger (`handleAiAutoDiscover`).
- [client/src/services/api.js](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/services/api.js) — `adminService.aiDiscover` API call.

### 🎤 Live Demo Script (90 Seconds):
> *"Curating authentic historical lore and media for thousands of monuments across India is a massive administrative bottleneck. To solve this, I engineered the **AI Cultural Auto-Discovery Engine**:*
>
> *1. In the Admin Dashboard, when a tourism officer enters a monument name—like 'Amer Fort, Rajasthan'—and clicks 'AI Auto-Discover', our backend connects to Groq's high-speed inference engine.*
>
> *2. In under 1.5 seconds, the LLM generates a structured JSON dossier containing architectural background, folklore, YouTube documentary references, and historical cinema links.*
>
> *3. To prevent GenAI hallucinations, we enforce a strict system prompt anchoring the model as an Indian cultural historian, constrain temperature to 0.3, and implement a mandatory Human-in-the-Loop review: the officer reviews and edits the content before saving it to the live database."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: How do you prevent hallucinations in historical facts?**
   - **Answer:** *"We use a 3-tier defense: First, low temperature (0.3) for deterministic, factual output. Second, strict system prompting enforcing JSON schema response format (`response_format: { type: 'json_object' }`). Third, mandatory Human-in-the-Loop design: the AI output populates an editable form for admin verification before touching the production database."*
2. **Q: Why did you choose Groq instead of standard OpenAI endpoints?**
   - **Answer:** *"Groq's LPU architecture delivers generation speeds of 500+ tokens per second with sub-second latency at significantly lower cost. Furthermore, our engine includes a multi-model fallback chain and an internal heuristic engine if API limits are reached."*

### 📋 Member 4 Preparation Checklist:
- [ ] Practice running the 'AI Auto-Discover' button live in the Admin dashboard.
- [ ] Understand the prompt structure and temperature setting in `adminController.js`.
- [ ] Be ready to explain the multi-model fallback list.

---

---

# 👤 MEMBER 5: Artisan Ecosystem & Heritage Commerce Lead

### 📌 Role Title:
**Artisan Ecosystem Architect & Heritage Commerce Lead**

### 🎯 Primary Responsibilities:
- **ODOP Artisan Bazaar:** Building the verified marketplace interface, craft categorization, and artisan profiles.
- **Physical Verification Gatekeeper:** Implementing the 4-step onboarding workflow for artisans (Application → Physical Audit → Subscription → Listing).
- **Anti-Scam Zero-Delivery Policy:** Explaining why the platform prioritizes in-store experiential visits over risky courier deliveries.
- **Direct Artisan Navigation:** Direct WhatsApp inquiry generator, shop timings, exact monument distance, and Google Maps navigation.
- **Culinary Heritage Module:** Curating hyper-local food heritage (Agra Petha, Banarasi Malaiyyo) linked to monuments.

### 📂 Code & Files to Master:
- [client/src/pages/BazaarPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/BazaarPage.jsx) — Marketplace UI, craft filters, WhatsApp integration.
- [client/src/pages/ArtisanPortalPage.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/pages/ArtisanPortalPage.jsx) — 4-Step Verification Tracker, Pehchan ID validation, Subscription plans.
- [server/src/controllers/productController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/productController.js) — Product endpoints with shop metadata.
- [server/src/controllers/artisanController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/artisanController.js) — Verification application submission and approval logic.
- [server/src/controllers/foodController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/foodController.js) — Culinary heritage endpoints.

### 🎤 Live Demo Script (90 Seconds):
> *"I designed the artisan-facing ecosystem to solve two massive problems: counterfeit tourist souvenirs and courier delivery scams.*
>
> *1. In our **Artisan Bazaar**, tourists can explore authentic ODOP crafts (such as Agra Marble Inlay or Banarasi Brocade). Each craft card transparently displays the master artisan's name, physical workshop address, distance from the monument, and opening hours.*
>
> *2. With one tap on 'WhatsApp Artisan', a pre-filled craft inquiry opens directly on the tourist's phone. Tourists can also tap 'Navigate to Shop' to walk straight to the workshop using Google Maps.*
>
> *3. To onboard, an artisan must pass our 4-step verification gate: submitting their Ministry of Textiles Pehchan ID and workshop coordinates. Only after physical verification and choosing a subscription tier can they list their products.*
>
> *4. We deliberately eliminated courier deliveries: high-value traditional crafts are touch-and-feel goods. Encouraging tourists to visit workshops guarantees 100% authenticity and zero delivery fraud."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Won't eliminating online courier delivery reduce craft sales?**
   - **Answer:** *"Authentic heritage crafts (e.g., a ₹25,000 pure silk saree or marble inlay table) suffer high rates of return fraud and shipping breakage in online couriers. Experiential tourism encourages visitors to witness the artisan at work, creating emotional value, immediate UPI payment, and 100% customer trust with zero courier overhead."*
2. **Q: What is a Pehchan ID and why is it required?**
   - **Answer:** *"Pehchan is the official biometric identification card issued to certified artisans by the Office of the Development Commissioner (Handicrafts), Ministry of Textiles. By requiring Pehchan verification, we guarantee only genuine craftspeople join the platform."*

### 📋 Member 5 Preparation Checklist:
- [ ] Practice showing an ODOP craft card with shop address, timing, and WhatsApp button.
- [ ] Understand the 4 verification steps in `ArtisanPortalPage.jsx`.
- [ ] Be prepared to explain the rationale behind non-deliverable culinary heritage items.

---

---

# 👤 MEMBER 6: Mobile Systems & DevOps Lead

### 📌 Role Title:
**Mobile Systems Engineer & Deployment Lead**

### 🎯 Primary Responsibilities:
- **Android Native Application:** Capacitor Android packaging, Gradle build pipeline, and APK generation (`SanskritiKhoj.apk` ~9.7 MB).
- **Hardware Geolocation & Radar:** Native GPS integration, Haversine proximity calculations, and floating radar beacon.
- **Hardware Camera Access:** Native camera trigger for artisans uploading craft photos.
- **Offline Reliability:** Client-side fallback caching ensuring zero-crash behavior during network loss.
- **Citizen Grievance Support:** In-app issue reporting modal creating tracked support tickets (`SK-TKT-...`).

### 📂 Code & Files to Master:
- [client/capacitor.config.json](file:///c:/Users/Mduma/Downloads/SIH26197/client/capacitor.config.json) — Capacitor native configuration.
- [client/src/components/HeritageRadar.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/HeritageRadar.jsx) — Geolocation proximity radar.
- [client/src/components/PermissionModal.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/PermissionModal.jsx) — Hardware permission flow.
- [client/src/components/ReportIssueModal.jsx](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/components/ReportIssueModal.jsx) — Tourist grievance reporting modal.
- [server/src/controllers/supportController.js](file:///c:/Users/Mduma/Downloads/SIH26197/server/src/controllers/supportController.js) — Grievance ticket persistence in MySQL.
- [client/src/data/fallbackData.js](file:///c:/Users/Mduma/Downloads/SIH26197/client/src/data/fallbackData.js) — Offline cache definitions.

### 🎤 Live Demo Script (90 Seconds):
> *"To ensure every tourist and rural artisan has instant access, I engineered SanskritiKhoj into a lightweight native Android APK (9.7 MB) using Capacitor:*
>
> *1. Here on my actual Android device, our app directly bridges with native hardware. When opened, our `PermissionModal` requests GPS access. Once granted, our **Heritage Radar** uses native coordinates and the Haversine formula to calculate nearby monuments within walking distance.*
>
> *2. For rural artisans, the app accesses native Android camera hardware to capture and upload workshop craft photos without needing desktop scanners.*
>
> *3. In rural monument zones where mobile data fluctuates, our app features an offline fallback layer (`fallbackData.js`) that keeps monuments, audio narratives, and craft listings accessible without network crashes.*
>
> *4. Finally, our Settings menu includes a formal Grievance Support Desk where tourists can report fake shops or app issues, generating a persistent tracking ticket in MySQL."*

### ❓ Top Jury Questions & Model Answers:
1. **Q: Why Capacitor over Flutter or React Native?**
   - **Answer:** *"Capacitor enables 100% codebase reuse between Web and Mobile while providing direct access to native APIs (GPS, Camera, Storage). This drastically reduces maintenance overhead for government agencies and ensures features update simultaneously on both Web and Android."*
2. **Q: What Android versions are supported?**
   - **Answer:** *"Our build targets Android API 22+ (Android 5.1 Lollipop up to Android 14), ensuring compatibility with over 99% of active smartphones across urban and rural India."*

### 📋 Member 6 Preparation Checklist:
- [ ] Have the APK installed and tested on a physical Android smartphone.
- [ ] Test the GPS Radar widget with permissions enabled.
- [ ] Be ready to demonstrate filing a grievance ticket via the Report Issue modal.

---

---

## 📋 Master Cheat Sheet: Team Roles Summary Table

| Member | Formal Title | Code Modules Owned | Live Demo Action | Secret Weapon / Pitch Line |
| :---: | :--- | :--- | :--- | :--- |
| **M1** | **Team Lead & Strategist** | `README.md`, `App.jsx`, High-Level Pitch | Controls intro, problem hook & monetization | *"0% Commission on artisans + verified tourist footfall."* |
| **M2** | **Frontend & Cultural UX Lead** | `LanguageContext.jsx`, `PlaceDetailPage.jsx`, `MapPage.jsx` | Toggles Hindi/English, plays Audio Guide | *"Hands-free audio guide in multiple languages."* |
| **M3** | **Backend & Database Architect** | `schema.prisma`, `server.js`, `authController.js` | Shows terminal API query & 9 MySQL models | *"Prisma type-safety with 9 normalized relational models."* |
| **M4** | **AI & Cultural Intelligence Lead** | `adminController.js`, Groq LLM, Prompting | Clicks 'AI Auto-Discover' on Admin page | *"1.5-second automated cultural lore & media curation."* |
| **M5** | **Artisan Ecosystem Lead** | `BazaarPage.jsx`, `ArtisanPortalPage.jsx`, `foodController.js` | Shows WhatsApp craft inquiry & Pehchan verification | *"Zero courier fraud: 100% in-shop verified artisan visits."* |
| **M6** | **Mobile Systems & DevOps Lead** | `capacitor.config.json`, `HeritageRadar.jsx`, `ReportIssueModal.jsx` | Shows Android phone, GPS radar & grievance tickets | *"9.7 MB lightweight APK compiled cleanly for rural India."* |

---

## 🏆 Presentation Day Golden Rules

1. **The 3-Second Rule:** Teammate ko bolne ka mauka dete waqt unka naam aur title bolein:
   - *Example: "Now our Backend Architect, [Member 3's Name], will demonstrate our database architecture."*
2. **Never Say "I Don't Know":** Agar judge doosre domain ka question pooche, politely redirect karein:
   - *Example: "That relates to our mobile hardware integration; my teammate [Member 6's Name], who led our Android build, can explain that exact implementation."*
3. **Keep the Servers Pre-Warmed:**
   - Client dev server (`npm run dev`) aur Server (`npm run dev`) presentation se 5 minute pehle start rakhein.
   - APK phone par open aur ready rakhein.
   - Admin account (`admin@heritage.gov.in` / `password123`) par pehle se logged in rahein.
4. **Show, Don't Just Tell:** Har claim ka screen par proof dikhayein (live database query, live AI generation, live Android app).

---

## 📅 1-Week Preparation Roadmap

| Day | Team Goal | Individual Focus |
| :--- | :--- | :--- |
| **Day 1** | App Walkthrough | Sabhi members app ke har page ko use karein (Tourist, Artisan, Admin) |
| **Day 2** | Code Understanding | Har member apne assigned files ko padhein aur flow samjhein |
| **Day 3** | Script Practice | Har member apna 90-second demo script timer lagakar practice kare |
| **Day 4** | Full Rehearsal 1 | Pura 10-minute presentation run-through karein with stopwatch |
| **Day 5** | Mock Jury Q&A | Teammates ek-doosre se tough technical questions poochein |
| **Day 6** | Hardware & APK Check | Android phone screen mirroring aur terminal demo finalize karein |
| **Day 7** | Final Dress Rehearsal | Seamless transitions test karein aur presentation lock karein |

---

*All files referenced in this guide exist directly in the project repository and are fully operational.*
