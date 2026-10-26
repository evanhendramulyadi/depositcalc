<p align="center">
  <img src="img/logo-depositcalc.png" alt="DepositCalc Logo" width="100">
</p>

<h1 align="left">DepositCalc</h1>

DepositCalc is a sleek, responsive client-side time deposit investment simulator designed to help users calculate potential earnings, compare simple vs. compound interest, and visualize portfolio growth directly in their browser.

## 🌐 Live Demo

Experience the live application here:  
👉 **[DepositCalc](https://depositcalc.vercel.app/)**

## ✨ Key Features

- **Dual Interest Modes**: Calculate returns using **Simple Interest** or **Compound Interest** calculation models.
- **Flexible Compounding Frequencies**: Model interest compounded **Annually**, **Semi-annually**, **Quarterly**, **Monthly**, or **Daily** with effective APY (Annual Percentage Yield) calculation.
- **Multi-Currency Support**: Switch between **IDR (Rp)** and **USD ($)** with currency-tailored limits and formatted displays.
- **Bilingual Interface**: Seamlessly switch between **English** and **Indonesian (Bahasa Indonesia)** with dynamic localized descriptions and insights.
- **Comprehensive Result Breakdown**: Instant calculation of total maturity value, net interest profit, annualized/monthly growth estimates, and personalized takeaways.
- **Visual Composition Bar**: Dynamic proportion bar illustrating the exact ratio of initial principal to earned interest.
- **Input Validation & Real-time Bounds**: Built-in boundary clamping and validation for principal, interest rate (0.01% – 50%), and tenure (months or years).
- **Modern Responsive Dark UI**: Refined dark interface featuring smooth transitions, ambient accents, and responsive layout across desktop and mobile devices.

## 🛠️ Tech Stack

- **HTML5**: Semantic document structure and accessible input controls.
- **CSS3**: Modern layout with Flexbox, CSS Grid, custom properties, smooth transitions, and keyframe animations.
- **JavaScript (ES6+)**: Pure vanilla JavaScript for state management, financial formulas, DOM updates, and client-side localization.
- **Hosting**: [Vercel](https://vercel.com)

## 💻 Local Setup Instructions

No build tools or external dependencies are required.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/evanhendramulyadi/depositcalc.git
   cd depositcalc
   ```

2. **Run the application**:
   - Open `index.html` directly in any modern web browser, **or**
   - Serve it using a lightweight local development server:
     ```bash
     # Using Python
     python -m http.server 3000
     ```
     Then open `http://localhost:3000` in your browser.

## 📄 Copyright & Ownership

© 2026 Evan Hendra Mulyadi. All Rights Reserved.

This project is an original work created by **Evan Hendra Mulyadi**.

This repository is publicly accessible solely for viewing, studying, and reviewing the source code. Public access does **not** grant permission to copy the entire project, rebrand or rename it, remove attribution, or claim it as your own creation. Re-use or distribution without explicit permission from the author is strictly prohibited.

