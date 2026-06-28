# unlox-minor-project-1
# 📊 GroupDNA – WhatsApp Group Analytics

> **"Spotify Wrapped, but for your WhatsApp Group."**

GroupDNA is a Python-based data analytics project that transforms a raw WhatsApp chat export into a comprehensive behavioral analytics report. It analyzes messaging patterns, participant activity, response behavior, communication styles, and personality archetypes using only **Python Fundamentals** and **NumPy**.

This project was developed as part of **The Unlox Academy – Industry-Graded Minor Project** and demonstrates how powerful analytics can be built without relying on advanced data science libraries.

---

# 🚀 Project Overview

Have you ever wondered:

- Who sends the most messages?
- Who is the biggest spammer?
- Who stays awake chatting after midnight?
- Who replies the fastest?
- Who disappears from the group for days?
- What words does your group use the most?
- What personality best describes each participant?

GroupDNA answers all these questions by converting thousands of WhatsApp messages into an attractive, easy-to-read analytics report.

The final output is designed to be **clean, aesthetic, screenshot-worthy, and LinkedIn-ready**.

---

# 🎯 Objectives

The objective of this project is to:

- Parse raw WhatsApp exported chat files
- Handle real-world messy chat data
- Perform behavioral analytics
- Generate meaningful statistics
- Detect communication patterns
- Assign personality archetypes
- Produce a visually appealing terminal report

---

# ✨ Features

## 📂 Feature 1 – WhatsApp Chat Parser

- Reads WhatsApp exported `.txt` files
- Extracts:
  - Timestamp
  - Sender
  - Message
- Stores parsed messages efficiently
- Handles malformed entries

---

## 📈 Feature 2 – Group Overview

Displays:

- Total Messages
- Total Participants
- Chat Duration
- Date Range
- Message Leaderboard
- Activity Percentage

---

## 📅 Feature 3 – Activity Analysis

Analyzes:

- Most Active Day
- Most Active Hour
- Daily Activity
- Hourly Activity
- Participant-wise Activity

---

## 🔥 Feature 4 – NumPy Activity Heatmap

Builds a real **NumPy matrix** representing participant activity across 24 hours.

Includes:

- Hour-wise activity
- Unicode Heatmap
- Night activity detection
- Peak hour identification

---

## 💬 Feature 5 – Word Frequency Analysis

Performs:

- Lowercase conversion
- Stopword removal
- Punctuation removal
- Word frequency calculation
- Top 10 group words
- Per-user vocabulary
- Unicode bar charts

---

## 📱 Feature 6 – Media & Deleted Message Analysis

Tracks:

- Media Shared
- Deleted Messages
- Media Leaderboard
- Deleted Message Leaderboard

---

## ⏱ Feature 7 – Response Time Analysis

Calculates:

- Average Reply Time
- Fastest Replier
- Slowest Replier
- Response Distribution

---

## 🤫 Feature 8 – Silent Streak Detection

Finds:

- Longest Silent Streak
- Consecutive Inactive Days
- Silent Period Statistics

---

## 🧠 Feature 9 – Personality Archetype Detection

Automatically assigns personality archetypes such as:

- 🔥 The Spammer
- 🌙 The Night Owl
- 👩‍👧 The Group Mom
- 📖 The Storyteller
- 🎭 The Drama Queen
- 👻 The Ghost
- 😂 The Comedian
- ❓ The Question Master

Each archetype is assigned using quantitative behavioral analysis.

---

## 📑 Feature 10 – Final Analytics Report

Generates a beautiful report containing:

- Group Overview
- Activity Summary
- Heatmap
- Top Words
- Response Statistics
- Silent Streaks
- Personality Cards
- Final Summary

---

# 🛠 Technologies Used

- Python 3
- NumPy
- datetime
- Google Colab

---

# ❌ Project Constraints

Following the project guidelines, this project intentionally **does NOT use**:

- ❌ pandas
- ❌ matplotlib
- ❌ seaborn
- ❌ plotly
- ❌ regex (`re`)
- ❌ collections.Counter
- ❌ defaultdict
- ❌ scikit-learn
- ❌ nltk

Everything is implemented using only:

- Variables
- Lists
- Tuples
- Dictionaries
- Sets
- Loops
- Functions
- File Handling
- NumPy
- datetime

---

# 📂 Dataset

Dataset Used:

```
hostel_bois.txt
```

Dataset Type:

Synthetic WhatsApp Export

Participants:

- Rahul
- Priya
- Aman
- Karan
- Neha
- Vikas

Chat Duration:

60 Days

Messages:

3174+

---

# 🧩 Edge Cases Handled

The parser successfully handles:

- ✅ System Messages
- ✅ Media Omitted
- ✅ Deleted Messages
- ✅ Multi-line Messages
- ✅ Empty Lines
- ✅ Missing Data
- ✅ Large Files
- ✅ Generic WhatsApp Exports

---

# 📊 Output

The notebook generates an attractive terminal report containing:

- Beautiful Headers
- Unicode Tables
- Progress Bars
- Heatmaps
- Rankings
- Personality Cards
- Analytics Dashboard

Designed to be screenshot-worthy for LinkedIn and GitHub.

---

# 📸 Sample Output

> *(Insert Screenshot Here)*

Example:

```
========================================================
                GROUPDNA REPORT
========================================================

👥 Participants : 6
💬 Messages     : 3174
📅 Duration     : 60 Days

🏆 Message Leaderboard

🥇 Rahul
🥈 Priya
🥉 Neha

Activity Heatmap

Top Words

Response Statistics

Personality Archetypes

========================================================
```

---

# 📁 Project Structure

```
GroupDNA.ipynb
README.md
hostel_bois.txt
```

---

# ▶️ How to Run

## Step 1

Clone the repository.

```
git clone https://github.com/yourusername/GroupDNA.git
```

---

## Step 2

Open the notebook in Google Colab.

---

## Step 3

Upload

```
hostel_bois.txt
```

---

## Step 4

Run all notebook cells.

```
Runtime
↓

Run All
```

---

## Step 5

Enjoy your analytics report.

---

# 📈 Future Improvements

Potential enhancements include:

- Interactive dashboard
- PDF report export
- CSV report generation
- Emoji analytics
- Sentiment analysis
- Network graph visualization
- Web application using Streamlit
- Multiple chat comparison

---

# 📚 What I Learned

Through this project I learned:

- File Handling
- Data Cleaning
- Text Parsing
- String Processing
- NumPy Matrix Operations
- Behavioral Analytics
- Time Series Analysis
- Data Visualization using Console
- Modular Programming
- Clean Code Practices
- Software Project Structure

---

# 💡 Challenges Faced

Some of the biggest challenges included:

- Parsing inconsistent chat data
- Handling edge cases
- Designing robust analytics
- Computing response times
- Detecting personality archetypes
- Creating an aesthetic terminal report without visualization libraries

These challenges helped strengthen my understanding of Python fundamentals and problem-solving.

---

# 🎓 Academic Information

**Project:** GroupDNA – WhatsApp Group Analytics

**Developed Using:**

- Python Fundamentals
- NumPy
- Google Colab

**Project Type**

Industry-Graded Minor Project

---

# 🙏 Acknowledgements

Special thanks to **The Unlox Academy** for designing this industry-oriented project and providing the project brief and synthetic dataset that inspired this implementation.

---

# 📜 License

This repository is intended for educational and learning purposes.

Please do not copy the project directly for academic submissions.

---

# ⭐ If you like this project

If you found this project interesting:

⭐ Star the repository

🍴 Fork it

📢 Share it with your friends

Thank you for visiting!
