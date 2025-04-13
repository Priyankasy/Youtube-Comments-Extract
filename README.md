# Youtube-Comments-Extract

# 📺 YouTube Comments Extractor (Snow White Trailer) – *Google Apps Script*

This project uses **Google Apps Script** to extract comments from the *Snow White* movie trailer on YouTube. It pulls public comments using the **YouTube Data API v3** and stores them directly in a **Google Sheet** for easy analysis.

---

## 🎯 Purpose

The goal is to collect real user feedback from the *Snow White* trailer to:

- Analyze public sentiment
- Identify trending opinions or common themes
- Export comments for NLP or visualization projects

---

## 🛠️ Tech Stack

- Google Apps Script (JavaScript-based)
- YouTube Data API v3
- Google Sheets

---

## 📋 Features

- 🔑 Uses your own YouTube API Key
- 📄 Fetches top-level comments (with optional replies)
- 💾 Stores data neatly into a Google Sheet (Author, Comment, Likes, Date)
- 🔄 Can be re-run to fetch newer comments

---

## 🚀 How to Use

### 1. Set Up Google Sheet

- Open [Google Sheets](https://sheets.google.com)
- Go to `Extensions` → `Apps Script`

### 2. Paste the Code

Replace the default `Code.gs` with the script from this repo (`Code.gs`).

### 3. Add Your YouTube API Key and Video ID

Edit the top of the script:

```javascript
const API_KEY = 'YOUR_YOUTUBE_API_KEY';
const VIDEO_ID = 'abcd1234'; // Replace with actual video ID
```

### 4. Run the Script

Click the ▶️ Run button in the Apps Script editor.  
The comments will be written into the active sheet.

---

## 🧾 Output Format

| Author Name | Comment | Likes | Published At |
|-------------|---------|-------|---------------|
| John Doe    | "Loved it!" | 23 | 2025-03-01T12:00:00Z |

---

## 📌 Example

Trailer URL:  
```
https://www.youtube.com/watch?v=abcd1234
```

Video ID: `abcd1234`

---

## 🧠 Future Additions

- [ ] Add sentiment analysis via Google Cloud Natural Language API
- [ ] Support replies (threaded comments)
- [ ] Auto-refresh to pull latest comments on a schedule
- [ ] Export to Google Drive as CSV

---

## 📄 License

MIT License – see [LICENSE](./LICENSE)

---

## 🙌 Contributions

Pull requests, feature ideas, and issues are welcome! Let’s make YouTube data more accessible for creators and researchers.
