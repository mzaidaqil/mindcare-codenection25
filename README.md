🌿 Mind Care – Mobile Application
**Your guide to a healthier university journey.**

*Mind Care* is a mobile application designed to support university students in managing mental health challenges such as *depression* and *anxiety*.  
Our goal is *not to replace professional counsellors, but to provide **self-help exercises* and *emotional support tools* for students, especially outside counselling hours.

---

## 🔗 Links
- **Figma Prototype:**  
- **YouTube Presentation:**  

---

## 🧩 Problem We Address
- Academic & financial stress are rising; counselling slots are limited.  
- Many students avoid seeking help due to **stigma** and **privacy concerns**.  
- Generic wellness apps don’t fit student routines or campus constraints.

**Our approach:** build a **student-specific**, proactive, stigma-free companion that meets students where they are—on mobile, privately, anytime.

---

## ✨ Features

•⁠  ⁠🧘 *Exercises to manage anxiety & depression*
  - Breathing exercises  
  - Gratefulness journaling  
  - Mood diary  

•⁠  ⁠💬 *AI Chatbot*
  - Available after counselling hours  
  - Lets students express and share their feelings  

•⁠  ⁠👩‍⚕️ *Counsellor Directory*
  - Quick access to counsellor contacts for professional help  

•⁠  ⁠♿ *Accessibility First*
  - User-friendly design for students with disabilities  

•⁠  ⁠🎮 *Gamification*
  - Streaks & rewards system  
  - Earn coins by completing exercises  
  - Unlock new themes to personalize the app  

---

 🔐 Safety, Privacy & Offline Readiness
- **Privacy-by-default:** no public social features, private journals  
- **Anonymous auth** for stigma-free use  
- **Local-only journaling** with optional background sync when online  
- **Crisis state machine:** surfaces help immediately (no timers, no friction)  
- **Offline-first:** caches last 7 days (e.g., IndexedDB) so key tools work without campus Wi-Fi

---

## 🛠️ Tech Stack

•⁠  ⁠*Frontend:* React Native  
•⁠  ⁠*Backend:* Node.js / FastAPI  
•⁠  ⁠*Database:* MySQL / Firebase  
•⁠  ⁠*Cloud Hosting:* AWS / Google Cloud  
•⁠  ⁠*External APIs:* (to be integrated as needed)  

---

## 🧪 Engineering Challenges → Solutions
- **Stigma-free but personalized** → **Anonymous auth + local-only journals**  
- **Fast crisis escalation** (without pretending to be clinical care) → **Deterministic state machine** that opens the crisis sheet instantly  
- **Unreliable campus Wi-Fi** → **Offline-first caches** for last 7 days + background sync

---

## 🎯 Target Users & Impact
- **Who:** University & college students facing stress, anxiety, burnout  
- **Short-term:** easier check-ins, better awareness, instant support  
- **Mid-term:** reduced isolation; healthier coping habits  
- **Long-term:** contribution to lower dropout risk and improved academic outcomes

## 🚀 Installation & Usage

1.⁠ ⁠*Clone the repository*
   ```bash
   git clone https://github.com/your-username/mind-care.git
   cd mind-care 
