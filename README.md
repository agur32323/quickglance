# QuickGlance

> Smart flashcard app with spaced repetition — built natively for iOS.

[![App Store](https://img.shields.io/badge/App_Store-Download-blue?logo=apple)](APP_STORE_LINK)
[![Platform](https://img.shields.io/badge/Platform-iOS_17%2B-lightgrey)](#)
[![Swift](https://img.shields.io/badge/Swift-6.0-orange?logo=swift)](#)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#)

QuickGlance helps you remember what you learn using the **SM-2 spaced repetition algorithm** — the same technique used by Anki. Build daily streaks, track your progress, and master any subject one card at a time.

---

## ✨ Features

- 🧠 **Spaced Repetition (SM-2)** — Cards you struggle with come back sooner
- 🔥 **Daily Streaks** — Build a learning habit
- 📊 **Progress Tracking** — Detailed statistics and learning metrics
- 🏠 **Home Screen Widget** — See your daily cards and streak at a glance
- 🌍 **Multi-language** — English & Turkish
- 🔒 **Privacy First** — All data stays on your device. No accounts, no tracking

---

## 📱 Screenshots

<p align="center">
  <img width="1320" height="2868" alt="onboarding" src="https://github.com/user-attachments/assets/d61a5440-32f8-41c1-a5db-990730802633" />
  <img width="1320" height="2868" alt="decklist" src="https://github.com/user-attachments/assets/0424ddb5-38f6-4cf8-ae93-3a5952b17680" />
  <img width="1320" height="2868" alt="stats" src="https://github.com/user-attachments/assets/1c766867-450e-449d-b019-ba1ba8331d01" />
  <img width="1320" height="2868" alt="study" src="https://github.com/user-attachments/assets/ad00ee0e-d06a-4b57-b0a9-83f96f465232" />
  <img width="1320" height="2868" alt="Simulator Screenshot - iPhone 17 Pro Max - 2026-04-19 at 19 09 40" src="https://github.com/user-attachments/assets/4b8d1856-bf66-41ec-a827-be366716ad81" />
</p>

---

## 🛠 Tech Stack

- **Language:** Swift 6.0
- **UI:** SwiftUI
- **Persistence:** SwiftData
- **Widget:** WidgetKit + App Groups
- **Localization:** String Catalog
- **Minimum iOS:** 17.0

---

## 🧮 Spaced Repetition Algorithm

QuickGlance implements the **SM-2 algorithm** from Piotr Woźniak's 1987 paper, the same algorithm behind Anki. Each card has:

- **Ease Factor** — how easy the card is (starts at 2.5)
- **Interval** — days until next review
- **Repetitions** — consecutive correct answers

When you mark a card correct, the interval grows exponentially. Get it wrong, and the card resets to come back the next day.

---

## 📲 Download

Available on the App Store:
https://apps.apple.com/us/app/quickglance-flashcards/id6762561099
---





