# 📺 YouTube Data Analytics Pipeline

A data engineering and analytics project that extracts, processes, and analyzes YouTube video data using the YouTube Data API.

---

## 🚀 Project Overview

This project builds a pipeline to:

- Connect to the YouTube API
- Extract video and engagement data
- Analyze trends in views, likes, and comments
- Retrieve and analyze user comments

---

## ⚙️ Features

### 🔌 API Integration
- Connected to YouTube Data API
- Extracted video metadata using search queries

### 📊 Data Extraction
- Pulled top 50 videos for "Avatar Movie"
- Extracted:
  - Views
  - Likes
  - Comments
  - Video titles and IDs

### 💬 Comment Analysis
- Retrieved comments using API
- Stored structured comment data in JSON format

Example:
```json
{
  "textDisplay": "The trailer was so good! ❤️"
}
