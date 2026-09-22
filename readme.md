🛡️ Scam & Fake Offer Scanner

A lightweight, modern web tool designed to instantly detect fake job offers, recruitment scams, advance-fee fraud, and rental traps with real-time heuristic pattern detection.

---

🚀 Overview

Employment and rental fraud continues to rise globally, often targeting job seekers with upfront "registration fees", advance equipment checks, or fake holding deposits. 

This tool provides a **zero-friction, client-side fraud analysis engine** wrapped in an interactive, dynamic liquid glassmorphic interface. Users can paste suspicious messages or offer letters and receive an immediate risk breakdown with detected red flags.

---

✨ Key Features

- **⚡ Instant Fraud Probability Score**: Generates an actionable fakeness percentage (`0% - 100%`) categorized into Low Risk, Warning, or Critical Risk.
- **🇮🇳 Comprehensive Indian Recruitment Scam Rules**:
  - Detects upfront registration fees, training fees, and gate pass charges.
  - Recognizes all currency mentions: `Rupees`, `IndianRupees`, `INR`, `Rs.`, and `₹`.
  - Flags Indian mobile wallets & UPI channels (`UPI`, `Paytm`, `GPay`, `PhonePe`, `BHIM`).
- **🌐 Global Scam Indicators**:
  - Advance fake check & equipment vendor traps (MacBook, hardware vendor reimbursement).
  - P2P wire and cash applications (`Zelle`, `CashApp`, `Venmo`, crypto/USDT, gift cards).
  - Recruiter using free personal emails (`@gmail.com`, `@yahoo.com`, `@outlook.com`) instead of corporate domains.
  - Chat-only or interview-less hiring (`Telegram`, `WhatsApp`, `Signal`).
  - Rental property scams (wire deposit prior to in-person walkthrough, overseas missionary claims).
- **💧 Dynamic Liquid Aurora & Glassmorphic Aesthetic**:
  - **Zero-Image CSS Liquid Aurora**: Pure animated floating fluid plasma orbs in glowing cyan (`#06b6d4`), electric indigo (`#6366f1`), and sky blue (`#38bdf8`) drifting across the screen.
  - **Liquid Text Box**: Flowing, continuous conic neon border stream, specular water droplet reflections, and internal moving plasma waves.
  - **Refractive Glass Cards**: Translucent frosted glass layers with `backdrop-filter: blur(32px) saturate(210%)` that dynamically refract the moving liquid aurora beneath them.
  - **Interactive Light Sheen**: Fluid gleam reflections that sweep across the glass surface.
- **⚡ Quick Test Presets**: Includes one-click test cases for Registration Fee Scams, Fake Check Job Traps, Fake Rental Traps, and Legitimate Corporate Offers.

---

🛠️ Tech Stack

- **Frontend**: HTML5, Modern CSS3 (Animations, Glassmorphism, Conic Gradients), Vanilla JavaScript / React 18 + TypeScript
- **Styling**: Tailwind CSS / Custom Liquid Keyframe Animations
- **Icons**: Lucide Icons
- **Deployment**: Static Webpage / Vite / Cloud Run

---

📂 Project Structure

```text
├── index.html            # Standalone, zero-dependency single-file deployment
├── src/
│   ├── App.tsx          # Main React component with liquid styling & heuristics
│   ├── index.css        # Liquid animation keyframes & glass glow utilities
│   ├── main.tsx         # React root mount
│   └── assets/
│       └── images/      # Cyber-security liquid wave background assets
├── public/
│   └── background.jpg   # Background fallback asset
├── package.json         # Project scripts & dependencies
└── README.md            # Documentation & usage guide