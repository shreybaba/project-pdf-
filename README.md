
**Live Deployment** → [https://project-pdf-git-main-shreybabas-projects.vercel.app/](https://project-pdf-nine.vercel.app)
<div align="center">

<br/>

```
 ____  _                         ____              _    
/ ___|| |__  _ __ ___ _   _     | __ )  ___   ___ | | __
\___ \| '_ \| '__/ _ \ | | |    |  _ \ / _ \ / _ \| |/ /
 ___) | | | | | |  __/ |_| |    | |_) | (_) | (_) |   < 
|____/|_| |_|_|  \___|\__, |    |____/ \___/ \___/|_|\_\
                       |___/     C O M P A N I O N      
```

<br/>

# 📖 Shrey Book Companion

### *Your AI-powered reading companion. Read smarter, every single day.*

<br/>

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)](https://github.com/shreybaba)
[![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange?style=for-the-badge&logo=firebase)](https://firebase.google.com)
[![Gemini AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-blue?style=for-the-badge&logo=google)](https://aistudio.google.com)
[![PDF.js](https://img.shields.io/badge/PDF.js-3.11-red?style=for-the-badge)](https://mozilla.github.io/pdf.js/)
[![No Backend](https://img.shields.io/badge/Backend-None%20Required-green?style=for-the-badge)](/)
[![Free Forever](https://img.shields.io/badge/Cost-Free%20Forever-brightgreen?style=for-the-badge)](/)

<br/>

> *"A reader lives a thousand lives before he dies. The man who never reads lives only one."*
> — George R.R. Martin

<br/>

![Preview](https://img.shields.io/badge/Status-Active%20Development-blue?style=flat-square)
![Version](https://img.shields.io/badge/Version-3.0-purple?style=flat-square)
![Single File](https://img.shields.io/badge/Architecture-Single%20HTML%20File-orange?style=flat-square)

</div>

---

<br/>

## ✨ What is Shrey Book Companion?

**Shrey Book Companion** is a fully-featured, AI-powered PDF reading app that lives in a **single HTML file**. No installation. No server. No build process. Just open it in a browser and start reading.

It combines the power of **Google Gemini AI**, **Firebase**, and **browser-native storage** to give you a reading experience that rivals dedicated apps — completely free.

<br/>

---

## 🚀 Feature Highlights

<br/>

### 📚 Smart PDF Reader
- **Render any PDF** directly in the browser using PDF.js
- **Chapter detection** — automatically finds chapters via PDF outline, TOC scan, AI detection, or regex fallback
- **Page thumbnails** strip for quick navigation
- **Zoom controls** — scale from 50% to 300%
- **Reading progress bar** — real-time top bar and sidebar display
- **Prominent page counter** — always visible in nav and sidebar
- **Scroll position saving** — resumes exactly where you left off

<br/>

### 🧠 Gemini AI Integration
- **✦ AI Chapter Synopsis** — hover any chapter → click "Synopsis" → Gemini summarizes it in 3 sentences
- **💬 PDF Chat Assistant** — ask anything about the book you're reading, Gemini answers with context
- **💡 Daily Inspiration Quotes** — Gemini generates a fresh reading quote on every dashboard load
- **Smart chapter detection** — when outline fails, Gemini reads the PDF text and finds chapters automatically
- **Rate limiting built-in** — intelligent 4.5s queue prevents API overuse

<br/>

### ☁️ Account & Sync (Firebase)
- **Email + Google sign-in** — secure Firebase Authentication
- **Cloud metadata sync** — progress, page numbers, chapters, streaks all sync to Firestore
- **Your data everywhere** — sign in on any device, your reading history is there
- **No Firebase Storage needed** — works on the free Spark plan, zero billing required

<br/>

### 💾 Smart Local Storage (IndexedDB)
- **Upload once per device** — PDFs are stored in browser's IndexedDB permanently
- **Instant re-open** — no file picker the second time, just click and read
- **Gigabytes of capacity** — stores as many books as your device allows
- **Survives browser refresh** — data persists unless you manually clear browser storage
- **Duplicate protection** — same file name = same book, no accidental duplicates

<br/>

### 📊 Dashboard
- **Good morning/afternoon/evening** greeting with time-aware icon
- **4 live stats** — Books saved, Pages read, AI synopses used, Reading streak
- **Currently reading** card with progress bar, chapters preview, Continue Reading button
- **Recent books** list with progress mini-bars
- **Reading streak tracker** — 7-day visual grid with flame intensity
- **Gemini quotes** — refreshable daily inspiration with fallback quotes

<br/>

### 📅 Reading Calendar
- **AI-powered reading plan** — set your minimum pages/day, generates a schedule for all your books
- **Weekly view** — Mon–Sun grid with daily reading targets and book assignments
- **Mark days done** — click any day to check it off ✓
- **Week navigation** — scroll back and forward through your calendar
- **Per-book breakdown** — shows pages/day, days to finish, estimated finish date
- **Cross-feature sync** — updating progress in Offline Books auto-marks calendar days

<br/>

### 📚 Offline Books Tracker
- **Track physical books** — no PDF needed, just title + total pages
- **Daily page updates** — enter today's page number, app calculates pages read
- **Reading streaks per book** — individual streak tracking with 🔥 badge
- **Progress bars** — visual completion with remaining pages count
- **Firebase synced** — offline book data saved to your Firestore account, available on any device
- **"Updated today" badge** — green indicator when you've logged today's session
- **Finish celebration** — 🎉 when you complete a book

<br/>

### 📖 Library
- **Grid and list views** — toggle between card grid and compact list
- **Sort by** Recent / A–Z / Progress
- **Search** — filter books by name in real-time
- **4 stats bar** — Total books, Completed, Cloud-saved, Total pages
- **Book detail modal** — full info with chapters list, progress, open/delete buttons
- **Book status badges** — New / Reading / Complete
- **Emoji auto-assignment** — 📖💰🔬💻🧠🚀💪 based on book title keywords
- **Delete with cleanup** — removes from Firestore and IndexedDB

<br/>

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | Vanilla HTML, CSS, JavaScript — zero frameworks |
| **PDF Rendering** | PDF.js 3.11.174 |
| **Authentication** | Firebase Auth (Email + Google) |
| **Database** | Firebase Firestore |
| **File Storage** | Browser IndexedDB (no Firebase Storage needed) |
| **AI** | Google Gemini 1.5 Flash |
| **Fonts** | Arial (system font — no downloads) |
| **Hosting** | Any static host (GitHub Pages, Netlify, Vercel, etc.) |
| **Architecture** | Single HTML file — everything inline |

<br/>

---

## ⚡ Quick Start

### 1. Clone or download
```bash
git clone https://github.com/shreybaba/shrey-book-companion.git
```
Or just download `readpdf-v3.html` — that's the entire app.

### 2. Open in browser
```
Just double-click readpdf-v3.html
# or serve locally:
npx serve .
```

### 3. Set up Firebase (5 minutes)
1. Go to [console.firebase.google.com](https://console.firebase.google.com)
2. Create a project → enable **Authentication** (Email/Password + Google)
3. Enable **Firestore Database** (free Spark plan is enough)
4. Copy your Firebase config into the `firebaseConfig` object in the HTML
5. Set Firestore rules (see below)

### 4. Add your Gemini API key (optional but recommended)
1. Go to [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Create a free API key
3. In the app → click **"API Key"** button → paste your key
4. Key is stored in browser only, never in the file

<br/>

---

## 🔒 Firebase Security Rules

Paste these in your **Firestore Rules** tab and click Publish:

```javascript
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /users/{userId}/{document=**} {
      allow read, write: if request.auth != null 
                         && request.auth.uid == userId;
    }
  }
}
```

> ✅ These rules ensure **only you** can access your own data. Safe for production.

<br/>

---

## 📁 Project Structure

```
shrey-book-companion/
│
├── readpdf-v3.html          ← The entire app (single file!)
├── manifest.json            ← PWA manifest
├── icon-192.png             ← App icon
└── README.md                ← You are here
```

Yes, the entire app — all CSS, JavaScript, HTML, UI, and logic — is in **one file**. No `node_modules`, no build step, no webpack.

<br/>

---

## 🗄️ Data Architecture

### Firestore Collections
```
users/
  {uid}/
    name, email, streak, lastReadDate
    stats/
      booksOpened, pagesRead, synopsesUsed
    books/
      {bookId}/
        name, currentPage, progress, totalPages
        currentChapter, chapters[], emoji
        localSaved, lastRead, openedAt
    offlineBooks/
      {bookId}/
        name, totalPages, currentPage
        streak, log[], addedAt, lastUpdated
```

### IndexedDB Schema
```
ReadPDF_Store/
  pdfs/
    {uid}_{bookId}  →  { id, name, buf (ArrayBuffer), savedAt }
```

<br/>

---

## 🎯 How the "No Re-upload" Works

```
First visit on a device:
  User picks PDF → Rendered → Saved to IndexedDB → Metadata to Firestore

Every visit after:
  User clicks book → IndexedDB lookup → Found → Opens instantly ⚡
                                      → Not found → Prompts for file (new device)
```

Your **progress always syncs** to Firestore regardless of which device you're on. The PDF file itself only needs to be uploaded once per device.

<br/>

---

## 🌟 Feature Roadmap

- [ ] **Dark/Light mode toggle** for PDF pages
- [ ] **Highlight & annotations** saved per book
- [ ] **Reading time estimates** per chapter
- [ ] **Export reading stats** as PDF report
- [ ] **PWA offline support** — read without internet
- [ ] **Book notes** — per-book markdown notes
- [ ] **Multi-device PDF sync** via Firebase Storage (when billing available)
- [ ] **Reading goals** — monthly/yearly targets

<br/>

---

## 🙏 Credits & Thanks

| Tool | Use |
|------|-----|
| [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla | PDF rendering engine |
| [Firebase](https://firebase.google.com) by Google | Auth + Firestore database |
| [Gemini API](https://ai.google.dev) by Google | AI features |
| [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) | Local PDF storage |

<br/>

---

## 👨‍💻 Author

<div align="center">

**Built with 💙 by Shreybaba**

*A personal project born from the frustration of losing reading progress and re-uploading the same PDFs over and over.*

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-shreybaba-black?style=for-the-badge&logo=github)](https://github.com/shreybaba)

</div>

<br/>

---

<div align="center">

**If this helped you read more, give it a ⭐**

*"Today a reader, tomorrow a leader." — Margaret Fuller*

</div>
