# 📚 The TBR App

A powerful offline-first personal reading tracker built by **Subin Khullar**.

The TBR App helps readers organize, track, review, analyze, and gamify their reading journey while maintaining complete ownership of their data.

---

## ✨ Features

### 📖 Library Management

- Add books manually
- Import books from Goodreads CSV exports
- Import books from Google Books
- Upload custom book covers
- Organize books into:
  - To Be Read (TBR)
  - Currently Reading
  - Read
  - Wishlist
- Edit book details
- Track reading progress
- Search and filter library

---

### ⭐ Reviews & Ratings

- Rate completed books
- Write and save reviews
- Add personal reading notes
- Track reading history

---

### 📊 Reading Analytics

- Reading statistics dashboard
- Books read per month
- Pages read per month
- Reading hours tracking
- Reading calendar with book covers
- Yearly statistics filter
- Reading goals and progress bars
- Reading heatmap

---

### 🎮 Gamification

- Reading streaks
- Daily reading goals
- Daily quests
- XP and levels
- Coins and rewards
- Reading leagues
- Reader profile
- Achievement badges
- Badge gallery
- Reading pet system
- Milestone tracking

---

### 📥 Import & Export

- Goodreads CSV import
- JSON backup export
- JSON backup restore
- Backup preview before restore
- Session snapshots
- Local browser storage

---

### 🌐 Google Books Integration

Search Google Books and import:

- Title
- Author
- ISBN
- Publisher
- Publication Date
- Categories
- Description
- Page Count
- Cover Image

---

### 📱 Progressive Web App (PWA)

- Installable on desktop
- Installable on mobile
- Offline capable
- Service Worker support

---

## 🚀 Running Locally

### Option 1: Python

Open a terminal in the project folder and run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

### Option 2: VS Code Live Server

1. Open project folder.
2. Install Live Server extension.
3. Right-click index.html.
4. Select:

```text
Open With Live Server
```

---

## 📂 Project Structure

```text
TBR-App/

index.html
manifest.json
service-worker.js

images/
    default-cover.svg
```

---

## 🔑 Google Books API

Create a Google Books API key and update:

```javascript
const GOOGLE_BOOKS_API_KEY =
"YOUR_API_KEY";
```

For production deployment:

- Restrict API Key to Books API only
- Restrict API Key to your domain

---

## ☁️ Deployment

Recommended hosting platforms:

### GitHub Pages

```text
https://yourusername.github.io/tbr-app/
```

### Netlify

```text
https://your-site.netlify.app
```

### Cloudflare Pages

```text
https://your-site.pages.dev
```

---

## 📦 Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Chart.js
- Google Books API
- LocalStorage
- Service Workers
- Progressive Web App

---

## 🔒 Privacy

The TBR App is designed as an offline-first application.

Your data is stored locally in your browser unless you explicitly export backups.

No personal reading data is transmitted to external servers except when using optional Google Books searches.

---

## 📜 License

Personal project by **Subin Khullar**.

Feel free to fork and customize for personal use.

---

## ❤️ Built For Readers

Track books.
Write reviews.
Build streaks.
Unlock achievements.
Grow your reading habit.

Happy reading! 📚

