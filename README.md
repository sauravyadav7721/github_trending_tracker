# 🌟 GitHub Trending Tracker

> 🚀 A Python project that automatically scrapes **GitHub’s Trending Repositories**, saves them into a **database and CSV file**, and visualizes the most popular **programming languages** using charts.

---

## 🧠 What This Project Does

This project acts like a **smart robot** 🤖 that visits GitHub’s Trending page, collects the list of popular repositories, and saves their details — such as **name, stars, language, and description**.

It then stores this data in a **SQLite database** for analysis and generates **beautiful visualizations** (like bar charts) showing which programming languages are trending the most.

---

## ✨ Features

✅ Scrapes latest trending repositories from GitHub  
✅ Extracts useful information: name, stars, language, description  
✅ Stores data in both **CSV** and **SQLite** formats  
✅ Visualizes top programming languages using **matplotlib**  
✅ Beginner-friendly, modular Python codebase  

---

## 📂 Folder Structure
github_trending_tracker/
│
├── main.py               # Entry point: runs the entire workflow
├── requirements.txt      # Required Python libraries
├── README.md             # Project documentation
│
└── src/
    ├── scraper.py        # Fetches trending data from GitHub
    ├── database.py       # Stores data in SQLite database
    ├── plotting.py       # Creates charts for visualizing data
    ├── utils.py          # Helper functions (e.g., save to CSV)
    └── stats.py          # (Optional) Statistics on collected data

