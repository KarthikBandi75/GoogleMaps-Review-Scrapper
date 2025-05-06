# 🌍 Google Maps Review Scraper

A full-stack application that scrapes and displays **Google Maps reviews** for any business the user searches for. Users can paste a **Google Maps business link** or search a place name with suggestions.

---

## 🚀 Features

- 🔍 Search any business by name or Google Maps URL
- 📄 Scrape and store at least 10 reviews
- 📊 Dashboard view with clean UI
- 💾 Persistent storage using MongoDB
- 🌐 Fast and responsive frontend using React + Tailwind CSS
- 🔗 Uses **SerpAPI** for real-time review scraping

---

## 💻 Tech Stack Overview

### 🧠 Backend
| Tech         | Description                                      |
|--------------|--------------------------------------------------|
| **Node.js**  | JavaScript runtime for backend development       |
| **Express.js**| Web framework to handle routing and APIs        |
| **MongoDB**  | NoSQL database to store scraped reviews          |
| **SerpAPI**  | Third-party API to fetch Google Maps reviews     |
 
---

### 🎨 Frontend
| Tech          | Description                                        |
|---------------|----------------------------------------------------|
| **React.js**  | Component-based UI framework for dynamic rendering |
| **Tailwind CSS** | Utility-first CSS framework for styling         |

---

### 🗺️ Maps Integration
| Service         | Usage                                                                 |
|-----------------|----------------------------------------------------------------------|
| **Google Maps** | Used to fetch place details and handle location-based search queries |

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/google-maps-review-scraper.git
cd google-maps-review-scraper
