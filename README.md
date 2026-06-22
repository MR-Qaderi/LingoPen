# LingoPen (قلم‌یار) 🪶✨

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge&logo=vercel)](https://mr-qaderi.github.io/LingoPen/)
[![UI Language](https://img.shields.io/badge/UI-Bilingual_(EN/FA)-blue?style=for-the-badge)](#)

**LingoPen** is an advanced, AI-powered multilingual writing coach. It goes beyond simple spell-checking by analyzing your text, preserving your authentic voice, and providing constructive, coaching-style feedback based on CEFR standards. 

Whether you are preparing for an international language exam, writing a professional business email, or just improving your daily conversations, LingoPen dynamically adapts to your specific needs.

## 🚀 Key Features

*   🌍 **Truly Multilingual:** Master writing in **English, German, French, Spanish, Italian, Russian, Turkish, Chinese, Persian, and Arabic**. Choose to receive coaching feedback in your native language for better understanding, or in your target language for full immersion.
*   🎯 **Context-Aware (Goals & Tones):** Tailor the AI's output by selecting specific goals *(IELTS/TOEFL Tasks, Goethe, DELF, Business Emails)* and desired tones *(Formal, Friendly, Persuasive, Direct, etc.)*.
*   🔍 **Visual Text Diff:** Uses a custom Myers/LCS algorithm to visually highlight exact additions and deletions between your raw text and the corrected version.
*   📊 **CEFR-Aligned Assessment:** Estimates your proficiency level (A1 to C2) and provides a structured diagnosis covering *Grammar, Vocabulary, and Flow*.
*   📈 **Target Level Upgrades:** Select a target level (e.g., C1), and LingoPen will generate a model rewrite matching that exact proficiency.
*   📄 **Export to Word:** Download a beautifully formatted Microsoft Word (`.doc`) report containing your original text, all AI feedback, visual diffs, and vocabulary enhancements to share with tutors or keep for your records.

---

## 📸 Interface & Features in Action

### 1. Bilingual Adaptive UI (English & Persian)
Configure your goal, tone, and desired levels easily. The UI fully adapts to your preferred language (LTR/RTL).

![LingoPen Input and Goals English](https://github.com/user-attachments/assets/27357a26-18e0-477e-9919-2405edd2a141)
![LingoPen Main Screen Persian](https://github.com/user-attachments/assets/26cee25f-62ba-41d4-b4e5-f1836fb8dd77)

### 2. Comprehensive Coaching Feedback
Receive structured feedback on grammar, vocabulary, and flow in either your native language or target language.

![Coaching English](https://github.com/user-attachments/assets/5a27993a-fbc8-4682-a487-764af93980dc)
![Coaching Persian](https://github.com/user-attachments/assets/37d2064c-16f7-4f38-85db-241c47ad2ec7)

### 3. Rewrite Studio & Visual Diff
See exactly what changed with the built-in diff algorithm, and explore natural or upgraded versions of your text.

![Suggested Versions and Diff](https://github.com/user-attachments/assets/188a17c5-8099-47af-8cc6-6ec53a926394)

### 4. Smart Vocabulary Enhancements
Discover better, context-appropriate alternatives for the words you used.

![Vocabulary Enhancements](https://github.com/user-attachments/assets/341ed61d-92e3-4d7d-af14-cf8af6e2ce26)

### 5. Microsoft Word (.doc) Export
Export your entire learning session into a beautifully formatted document with just one click.

![Word Export Document](https://github.com/user-attachments/assets/cdbee163-6b31-4457-a533-804959e5de3c)

---

## 🛠 Tech Stack

Designed as a lightweight, lightning-fast Single-Page Application (SPA):
*   **Frontend:** HTML5, Vanilla JavaScript, Tailwind CSS (via CDN).
*   **UI/UX:** Custom Glassmorphism design, fully responsive, with seamless Dark/Light mode integration.
*   **AI Engine:** Powered by LLM API (via a secure Cloudflare Worker proxy) utilizing strict JSON schemas for predictable rendering.

## 💡 How to Use
No installation required. Simply visit the [Live Demo](https://mr-qaderi.github.io/LingoPen/), paste your text, configure your language/goal/tone, and click "Analyze".
