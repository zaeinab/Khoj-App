# Khoj (کھوج) - AI-Powered Cultural Heritage & Tourism Explorer 🇵🇰🏛️

An interactive, immersive Android application that transforms historical monuments and archaeological ruins into rich, living museums. Built with *Kotlin, **Jetpack Compose (Material 3), and powered by server-side **Google Gemini APIs*.

---

## 🌟 Key Features

### 1. 🔍 Smart Landmark Scan & Bilingual Detail
- Instant on-device image scanning for landmarks and architectural ruins.
- Compiles custom deep-dives on the structural history in *English* and *Urdu*.
- Highlights chronological contexts including constructed peak periods, decline stories, fun facts, and transit directions to neighboring ruins.

### 2. 💬 Conversational Chat with Local Custodians
- Engage in automated, high-fidelity real-time Q/A directly with virtual heritage guides representing scanned sites.
- Learn hidden facts, local folklore, and cultural stories behind the architecture.

### 3. 📜 Ancient Script Deciphering
- Capture photos of ancient carvings, stones, calligraphy, or inscriptions (e.g., Harappan, Gandharan, Arabic, Persian, or Kharosthi).
- Extract localized translations, script classification, estimated timeframes, and cultural significance.

### 4. 🗺️ AI-Curated Heritage Trails & Local Stops
- Input travel limits (e.g., 4 hours, 8 hours) to discover tailored travel loop guides.
- Coordinates transit times, distance scales, focal points, and highly rated local historical food stops.

### 5. 🏆 Interactive Weekly Quests & Badges
- Engage with local historic discovery lists designed as active mini-quests (e.g., "Find the Mughal fresco arches").
- Earn virtual explorer badges upon completing travel loops.

### 6. 🛡️ AI Conservation Risk Reporter
- Scan structural damage, cracks, or active deterioration on site.
- Generates localized structural risk indexes (1-10 scale), classifies types of degradation, and matches reports with concrete steps local citizens and administrators can execute to help preserve the sites.

### 🖼️ Dynamic Discovery Cards
- Generate customized retro-postcard images embedded with dynamic headlines, discovery logs featuring user names, and beautiful classic Urdu descriptions to share on social networks.

---

## 🛠️ Stack & Technologies

- *Language:* Kotlin
- *UI Toolkit:* Jetpack Compose (Material 3 Adaptive Dynamic Theming)
- *Asynchronous Flow:* Kotlin Coroutines & Flow (Stateflow, Lifecycle-aware collectors)
- *Core AI Integration:* Google Gemini API (orchestrated using both gemini-1.5-flash and gemini-2.5-flash endpoints)
- *Networking:* Retrofit 2, OkHttp 4 & Moshi (JSON Serialization/Deserialization schemas)
- *Local Utilities:* CameraX, Jetpack Navigation API (Type-safe routes)

---

## ⚙️ How to Build and Run Locally

### Prerequisites
- Android Studio Ladybug (or newer versions).
- Android SDK 34 (Upside Down Cake or higher).
- A valid Gemini API Key from [Google AI Studio](https://aistudio.google.com/).

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/khoj-heritage-app.git
   cd khoj-heritage-app
Open the project in Android Studio.
Add your Gemini API key:
In Android Studio, go to the top-level root directory and locate or create a .env file or export your system environment variables.
Insert your key:
code
Env
GEMINI_API_KEY=your_actual_gemini_api_key_here
Gradle will automatically sync configurations and expose BuildConfig.GEMINI_API_KEY to the application.
Click Run on Android Studio to deploy the application onto your emulator or connected physical Android device.

### 🏛️ Project Motivation
Pakistan contains thousands of years of human civilization layers (including Mohenjo-daro, Harappa, Taxila civilizations,
and beautiful Mughal/Sikh/Colonial monuments) that suffer from a lack of digital accessibility and preservation metrics. 
Khoj bridges this generational divide, putting the power of an expert historian and digital conservation platform directly
inside the pockets of global and local travelers.

## 📽️ Demo Notes
⚠️ *The demo video may contain a minor visual repetition artifact resulting from extensive training and testing cycles. App performance and features remain fully stable.*
