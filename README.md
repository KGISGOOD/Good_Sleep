# 🌙 Sleep Cycle Calculator (Multilingual)

A simple, single-page web application designed to help users determine the optimal time to go to sleep or wake up based on 90-minute sleep cycles. By waking up at the end of a full cycle, you can minimize grogginess and wake up feeling refreshed.

This application is built entirely in a single HTML file using **vanilla JavaScript** for logic and **Tailwind CSS** for a modern, dark-mode, responsive interface.

---

## ✨ Features

- **Optimal Timing Calculation**  
  Calculates up to **6 recommended sleep/wake times** based on the scientifically recognized 90-minute human sleep cycle.

- **Three Modes**
  - **When to Wake**: Calculates when you should go to sleep if you need to wake up at a specific time.
  - **When to Sleep**: Calculates when you should wake up if you go to sleep at a specific time.
  - **Sleep Now**: Calculates your ideal wake-up times starting from the current moment.

- **Sleep Latency Toggle**  
  Optional **15-minute buffer** to account for the time it typically takes to fall asleep after lying down.

- **Multilingual Support**
  Interface available in:
  - 🇺🇸 English (`en-US`)
  - 🇹🇼 Traditional Chinese (`zh-TW`)
  - 🇯🇵 Japanese (`ja-JP`)
  - 🇰🇷 Korean (`ko-KR`)

- **Intuitive Feedback**
  - Color-coded results:
    - 🟢 Green: Adequate sleep duration
    - 🔴 Red: Critically low sleep duration
  - Results sorted by **priority** and **practicality** (earlier cycles first).

---

## 🚀 Getting Started

Since this is a self-contained, single-file application, **no installation or build process is required**.

### ✅ Prerequisites

You only need a **modern web browser**, such as:

- Google Chrome  
- Mozilla Firefox  
- Safari  
- Microsoft Edge  

### ▶️ How to Run

[Sleep Cycle Calculator web](https://kgisgood.github.io/Good_Sleep/sleep.html)

---

## 💻 Tech Stack

| Technology       | Purpose        | Notes                                                                |
|------------------|----------------|----------------------------------------------------------------------|
| **HTML5**        | Structure      | Main document and layout container.                                 |
| **Vanilla JavaScript** | Core Logic    | Handles state management, time calculation, and DOM manipulation.   |
| **Tailwind CSS** | Styling        | Loaded via CDN for a responsive, dark-mode, and modern UI design.   |

---

## 😴 The 90-Minute Cycle

The calculation is based on the premise that a full **sleep cycle lasts approximately 90 minutes**.

- Waking up at the **end** of a sleep cycle (during lighter sleep) can:
  - Reduce **sleep inertia** (the groggy feeling upon waking).
  - Help you feel **more refreshed**, even if total sleep time is slightly shorter.

The application suggests between:

- **1 to 6 cycles**
- Corresponding to **1.5 hours to 9 hours** of sleep.

Each recommended time is calculated as:

> base time ± (90 minutes × number of cycles) [+ 15-minute latency if enabled]

---
