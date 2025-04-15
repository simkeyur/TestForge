# TestForge
AI Enabled Test Data Generator - [Link](https://simkeyur.github.io/TestForge/)

TestForge is a lightweight web app built with **Vanilla JavaScript** and **Bootstrap** to generate realistic test data using **Gemini AI** (Google's LLM).

## ✨ Features

- 🔐 Google Gemini API integration (bring your own API key)
- 🧠 Smart Data (AI) column generator with custom prompt support
- 🎛️ Supports various data types: Email, Number, Boolean, Date, UUID, Regex, List
- 💾 Save and load schema templates using localStorage (modal UI)
- 🌗 Dark/Light theme toggle
- ⏳ Loading spinner while data is being generated
- 📦 Export data in JSON, CSV, or SQL formats
- 🛠️ 100% static and deployable on GitHub Pages

## 🚀 Getting Started

1. Clone or [Download](https://github.com/simkeyur/TestForge) this repo.
2. Open `index.html` in your browser.
3. Enter your [Gemini API Key](https://aistudio.google.com/app/apikey).
4. Define your schema using the dynamic UI.
5. Click `Generate Data` and export it!

## 🧠 Smart Data

Use the `Smart Data (AI)` option to let Gemini infer values based on the column name or a custom prompt.

Example:

- Column Name: `Address`
- Prompt: `Only show addresses from Texas`

## 📁 Hosting

To host on GitHub Pages:

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to `main` branch and root directory
4. Visit `https://your-username.github.io/testforge/`

## 🛡️ Disclaimer

This project uses Gemini API. Ensure your usage complies with Google's usage terms.

---

Made with ❤️ by Keyur
"""
