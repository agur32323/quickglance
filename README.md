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

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d61a5440-32f8-41c1-a5db-990730802633" alt="Onboarding" width="200" /></td>
    <td><img src="https://github.com/user-attachments/assets/0424ddb5-38f6-4cf8-ae93-3a5952b17680" alt="Deck List" width="200" /></td>
    <td><img src="https://github.com/user-attachments/assets/ad00ee0e-d06a-4b57-b0a9-83f96f465232" alt="Study View" width="200" /></td>
    <td><img src="https://github.com/user-attachments/assets/1c766867-450e-449d-b019-ba1ba8331d01" alt="Statistics" width="200" /></td>
    <td><img src="https://github.com/user-attachments/assets/4b8d1856-bf66-41ec-a827-be366716ad81" alt="Home Screen Widget" width="200" /></td>
  </tr>
  <tr align="center">
    <td><sub>Onboarding</sub></td>
    <td><sub>Deck List</sub></td>
    <td><sub>Study View</sub></td>
    <td><sub>Statistics</sub></td>
    <td><sub>Widget</sub></td>
  </tr>
</table>

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





