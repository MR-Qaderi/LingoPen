# LingoPen
# LingoPen (قلم‌یار) 🪶✨

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=vercel)](https://mr-qaderi.github.io/LingoPen/)
[![UI Language](https://img.shields.io/badge/UI-Bilingual_(EN/FA)-blue?style=for-the-badge)](#)

**LingoPen** is an advanced, AI-powered multilingual writing coach. It goes beyond simple spell-checking by analyzing your text, preserving your authentic voice, and providing constructive, coaching-style feedback based on CEFR standards. 

Whether you are preparing for an international language exam, writing a professional business email, or just improving your daily conversations, LingoPen dynamically adapts to your specific needs.

<p align="center">
  <img src="https://github.com/user-attachments/assets/26cee25f-62ba-41d4-b4e5-f1836fb8dd77" alt="LingoPen Main Screen Persian" width="48.5%"/>
  <img src="https://github.com/user-attachments/assets/27357a26-18e0-477e-9919-2405edd2a141" alt="LingoPen Input and Goals English" width="48.5%"/>
</p>

## 🚀 Key Features

*   🌍 **Truly Multilingual:** Master writing in **English, German, French, Spanish, Italian, Russian, Turkish, Chinese, Persian, and Arabic**. Choose to receive coaching feedback in your native language for better understanding, or in your target language for full immersion.
*   🎯 **Context-Aware (Goals & Tones):** Tailor the AI's output by selecting specific goals *(IELTS/TOEFL Tasks, Goethe, DELF, Business Emails)* and desired tones *(Formal, Friendly, Persuasive, Direct, etc.)*.
*   🔍 **Visual Text Diff:** Uses a custom Myers/LCS algorithm to visually highlight exact additions `<ins>` and deletions `<del>` between your raw text and the corrected version.
*   📊 **CEFR-Aligned Assessment:** Estimates your proficiency level (A1 to C2) and provides a structured diagnosis covering *Grammar, Vocabulary, and Flow*.
*   📈 **Target Level Upgrades:** Select a target level (e.g., C1), and LingoPen will generate a model rewrite matching that exact proficiency.
*   📄 **Export to Word:** Download a beautifully formatted Microsoft Word (`.doc`) report containing your original text, all AI feedback, visual diffs, and vocabulary enhancements to share with tutors or keep for your records.

## 📸 Interface & Features in Action

**Bilingual Coaching Feedback (Adaptive UI)**
<p align="center">
  <img src="https://github.com/user-attachments/assets/5a27993a-fbc8-4682-a487-764af93980dc" alt="Coaching English" width="48.5%"/>
  <img src="https://github.com/user-attachments/assets/37d2064c-16f7-4f38-85db-241c47ad2ec7" alt="Coaching Persian" width="48.5%"/>
</p>

**Rewrite Studio (Visual Diff) & Vocabulary Enhancements**
<p align="center">
  <img src="https://github.com/user-attachments/assets/188a17c5-8099-47af-8cc6-6ec53a926394" alt="Suggested Versions and Diff" width="48.5%"/>
  <img src="https://github.com/user-attachments/assets/341ed61d-92e3-4d7d-af14-cf8af6e2ce26" alt="Vocabulary Enhancements" width="48.5%"/>
</p>

**Comprehensive Word (.doc) Export**
<p align="center">
  <img src="https://github.com/user-attachments/assets/cdbee163-6b31-4457-a533-804959e5de3c" alt="Word Export Document" width="98%"/>
</p>

## 🛠 Tech Stack

Designed as a lightweight, lightning-fast Single-Page Application (SPA):
*   **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN).
*   **UI/UX:** Custom Glassmorphism design, fully responsive, with seamless Dark/Light mode integration.
*   **AI Engine:** Powered by LLM API (via a secure Cloudflare Worker proxy) utilizing strict JSON schemas for predictable rendering.

## 💡 How to Use
No installation required. Simply visit the [Live Demo](https://mr-qaderi.github.io/LingoPen/), paste your text, configure your language/goal/tone, and click "Analyze".
