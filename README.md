# kithabi
A privacy-focused, offline-first Islamic deed tracker and habit builder. Features gamified scoring, strict challenge modes, offline prayer times via CSV, and a Quran planner.

### **Short Repository Description** (for the sidebar)

> A privacy-focused, offline-first Islamic deed tracker and habit builder. Features gamified scoring, strict challenge modes, offline prayer times via CSV, and a Quran planner. Built as a single HTML file.

---

### **Full README.md Content**

# 🌙 Muhasaba - Islamic Deed Evaluator

**Muhasaba** (Self-Accounting) is a lightweight, privacy-focused web application designed to help Muslims track their daily spiritual obligations, voluntary acts, and personal habits.

Built as a **single HTML file**, it runs completely offline in your browser, using LocalStorage to keep your data secure on your device. It combines spiritual tracking with gamified scoring and strict habit-building challenges.

**

## ✨ Key Features

### 1. 📝 Daily Deed Tracking

* **Sala'th:** Track Fard prayers with specific statuses (Jama'ah +27 pts, Alone +1 pt, Missed -10 pts).
* **Sunnah & Nafl:** Log voluntary prayers (Rawatib, Duha, Qiyam/Witr).
* **Adhkar & Quran:** Track morning/evening Adhkar and daily recitation.
* **Misdeeds:** Self-evaluate and rate your avoidance of bad habits (Anger, Wasting Time) on a 0-10 scale.

### 2. 🔥 Advanced Challenge Mode

* Create custom challenges (e.g., "No Social Media," "No Music") with target durations (e.g., 40 Days).
* **Strict Accountability:** If a day is missed, the app forces a choice:
* **Restart:** Reset progress to Day 0.
* **Continue:** Keep the count but apply a point penalty.


* Visual progress bars for active challenges.

### 3. 🕌 Offline Prayer Schedule

* **CSV Import:** Upload your local annual prayer time CSV file directly in Settings.
* **Dashboard:** View today's prayer times, the next upcoming prayer, and a live countdown.
* Works entirely without an API or internet connection once the CSV is loaded.

### 4. 📊 Analytics & Utilities

* **Scoring System:** Daily, Weekly, and Monthly scores to visualize consistency.
* **Quran Planner:** Input your target days, and the app calculates how many pages you must read daily.
* **Reports:** Visual charts and history logs (last 7 days).

### 5. 🔒 Security & Privacy

* **Local Storage:** No server, no cloud, no tracking. Your data lives in your browser.
* **Passcode Lock:** Integrated lock screen with PIN protection to keep your records private.

### 6. 🌍 Customization

* **Bilingual:** Instant toggle between **English** and **Arabic** (with full RTL support).
* **Themes:** Serene Emerald Green UI.
* **Hijri Date:** Adjustable Hijri date offset.

## 🚀 How to Use

1. **Download:** Simply download the `index.html` file from this repository.
2. **Run:** Open the file in any modern web browser (Chrome, Safari, Edge, Firefox).
3. **Setup:** - Go to **Settings** to configure your Passcode.
* (Optional) Upload your `annual.csv` for prayer times.


4. **Install (Optional):** You can add the file to your mobile home screen to use it like a native app.

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript.
* **Styling:** Tailwind CSS (via CDN).
* **Icons:** Heroicons (SVG).
* **Storage:** Browser LocalStorage.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new deed categories or UI improvements, feel free to fork the repo and submit a pull request.

## 📄 License

This project is open-source and free to use for everyone.

---
