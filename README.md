<!--
README for TALLAM – AI-Powered Learning App
Last update: 2025-05-28
-->

<h1 align="center">📚 TALLAM – AI-Powered Learning App</h1>

<p align="center">
  Personalised, AI-driven micro-learning that adapts to <em>you</em> in real time.<br/>
  Built with <strong>Flutter + Dart</strong> · Ships to <strong>Android | iOS | Web | Desktop</strong>
</p>

<p align="center">
  <img src="screenshots/home.gif" width="240"/> 
  <img src="screenshots/quiz.gif"  width="240"/> 
  <img src="screenshots/chat.gif"  width="240"/>
</p>

---

## ✨ Key Features
| Category | What it does |
|----------|--------------|
| **Adaptive AI Tutor** | Uses GPT-4o (OpenAI) to explain any concept in plain English, with follow-up Q&A. |
| **Smart Quizzing** | Difficulty auto-adjusts via an on-device Bayesian algorithm → keeps you in the “flow” zone. |
| **Flashcard Generator** | One-tap conversion of any lesson into spaced-repetition cards (stored locally, no cloud fees). |
| **Progress Analytics** | Tracks retention, speed, and confidence scores. All learner data is private & encrypted on device. |
| **AR Extensions *(optional)* ** | Experimental module overlays 3-D labels on physical objects (powered by `ar_flutter_plugin`). |
| **Multi-platform** | Single Flutter code-base → Android (API 21+), iOS 13+, Web, Windows, macOS, Linux. |

---

## 🚀 Quick Start

> **Prerequisites**  
> • Flutter 3.22+  • Dart 3.4+  • An OpenAI API key (set as `OPENAI_API_KEY`)

```bash
# 1  Clone
git clone https://github.com/Mohammed-AlKuhali/TALLAM-AI-POWERED-LEARNING-APP.git
cd TALLAM-AI-POWERED-LEARNING-APP

# 2  Install deps
flutter pub get

# 3  Run (pick one)
flutter run -d android   # Android emulator / device
flutter run -d chrome    # Web
flutter run -d windows   # Desktop (Windows/macOS/Linux)

# 4  (First launch) enter your OpenAI key in Settings → Integrations
