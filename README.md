<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=180&section=header&text=BCA%20Student%20%7C%20Python%20Developer&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Machine%20Learning%20%7C%20Backend%20Development%20%7C%20Android%20Apps%20%7C%20Automation&descAlignY=60&descSize=15" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&multiline=true&width=700&height=70&lines=Python+Developer+%7C+ML+Enthusiast;Backend+Development+%7C+Android+Apps;Building+practical+projects+that+solve+real+problems)](https://git.io/typing-svg)

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20Internships-22C55E?style=for-the-badge&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/Degree-BCA-8B5CF6?style=for-the-badge&labelColor=0D0D0D" />
  <img src="https://img.shields.io/badge/Focus-Software%20Engineering-6D28D9?style=for-the-badge&labelColor=0D0D0D" />
</p>

</div>

---

## About Me

I am a BCA student interested in Machine Learning, Backend Development, Web Automation, and Mobile Application Development.

I enjoy building practical projects that solve real problems — ranging from recommendation systems and AI-powered study applications to YouTube automation tools and data extraction pipelines.

Currently focused on strengthening my software engineering fundamentals, machine learning skills, and backend development knowledge while building hands-on projects with real codebases.

---

## Open To

<div align="center">

| Role | Status |
|------|--------|
| Software Development Internship | ✅ Open |
| Backend Development | ✅ Open |
| Python Development | ✅ Open |
| Machine Learning Projects | ✅ Open |
| Android Development | ✅ Open |

</div>

---

## Tech Stack

<div align="center">

### Languages
<img src="https://skillicons.dev/icons?i=python,java,js,bash&theme=dark" />

### Backend & Frameworks
<img src="https://skillicons.dev/icons?i=nodejs,express,flask&theme=dark" />

### Mobile & Database
<img src="https://skillicons.dev/icons?i=androidstudio,firebase,sqlite&theme=dark" />

### ML & Data
<img src="https://skillicons.dev/icons?i=sklearn&theme=dark" />
&nbsp;
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=0D0D0D" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white&labelColor=0D0D0D" />

### Cloud & Tools
<img src="https://skillicons.dev/icons?i=aws,linux,git,github,selenium&theme=dark" />

</div>

---

## Machine Learning & Data Skills

<div align="center">

| Domain | Technologies |
|--------|-------------|
| Recommendation Systems | PySpark ALS, TF-IDF, Hybrid Filtering |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-Learn, PySpark MLlib |
| Data Visualization | Matplotlib, Seaborn, Streamlit |
| Model Evaluation | RMSE, Cross-Validation |
| NLP (Basic) | TF-IDF Vectorization |

</div>

---

## Featured Projects

<details>
<summary><b>📱 NoteSphere — AI-Powered Study Application</b></summary>

<br/>

| Category | Details |
|----------|---------|
| **What it is** | An Android application that combines note management, document processing, and AI-assisted learning in a single app |
| **Tech Stack** | Java, Android SDK, Node.js, Firebase, Gemini AI API, SQLite |
| **Key Features** | Note management, PDF processing, AI flashcard generation, quiz generation, AI chat assistant |
| **Backend** | Node.js REST API with Firebase for authentication and real-time data sync |
| **AI Integration** | Gemini AI for generating flashcards, quizzes, and answering student questions from notes |
| **Repository** | [View Repository →](https://github.com/mrvanshgoel/NoteSphere) |

**What it does**

NoteSphere is a study companion Android app. Students upload their notes or PDFs, and the app uses Gemini AI to automatically generate flashcards for memorization, create quiz questions for self-testing, and provide an AI chat interface to ask questions about the material.

**Stack breakdown**

```
[Android App (Java)]
        │
        ▼
[Node.js REST API] ──► [Firebase Auth + Realtime DB]
        │
        ▼
[Gemini AI API] ──► [Flashcard / Quiz / Chat Generation]
        │
        ▼
[PDF Processing Layer] ──► [SQLite local cache]
```

**What I learned**

Working on NoteSphere gave me hands-on experience integrating a third-party AI API into a mobile app, designing a REST API backend for Android consumption, and managing Firebase authentication and data sync alongside a local SQLite cache.

</details>

---

<details>
<summary><b>🎬 Hybrid Movie Recommendation System</b></summary>

<br/>

| Category | Details |
|----------|---------|
| **What it is** | A movie recommendation system combining collaborative filtering and content-based filtering on the MovieLens dataset |
| **Tech Stack** | Python, PySpark, PySpark MLlib (ALS), Scikit-Learn, TF-IDF, Pandas, Streamlit, Matplotlib |
| **Dataset** | MovieLens (standard benchmark dataset for recommendation research) |
| **Approaches** | Collaborative filtering via ALS; content-based filtering via TF-IDF on movie metadata |
| **Evaluation** | RMSE on held-out validation split |
| **Interface** | Streamlit web app for interactive recommendations |
| **Repository** | [View Repository →](https://github.com/mrvanshgoel/hybrid-movie-recommender) |

**How it works**

The system uses two complementary approaches. ALS (Alternating Least Squares) from PySpark MLlib learns latent factors from user-movie rating interactions to generate collaborative recommendations. TF-IDF vectorization on movie genres and metadata generates content-based similarity scores. The hybrid layer combines both signals for the final recommendation list.

**Pipeline**

```
[MovieLens Dataset]
        │
        ▼
[Data Cleaning & Preprocessing (Pandas)]
        │
        ├──► [ALS Collaborative Filtering (PySpark MLlib)]
        │         └── learns user/movie latent factors
        │
        └──► [TF-IDF Content Similarity (Scikit-Learn)]
                  └── vectorizes genres + metadata
        │
        ▼
[Hybrid Score Combiner]
        │
        ▼
[RMSE Evaluation on Validation Set]
        │
        ▼
[Streamlit Interface for interactive recommendations]
```

**What I learned**

This project introduced me to PySpark for distributed data processing, the ALS algorithm for matrix factorization, and how to combine two different recommendation strategies. Building the Streamlit frontend taught me how to turn a notebook-based ML project into an interactive application.

</details>

---

<details>
<summary><b>🔭 SearchTube — YouTube Chat & Metadata Collection System</b></summary>

<br/>

| Category | Details |
|----------|---------|
| **What it is** | A Python-based YouTube chat and metadata collection system with a Flask API backend |
| **Tech Stack** | Python, Flask, SQLite, Selenium, BeautifulSoup, Requests, Async scraping |
| **Key Features** | YouTube metadata extraction, live chat collection, channel monitoring, structured storage |
| **Backend** | Flask REST API with SQLite database layer |
| **Reliability** | Retry handling and logging for scraping stability |
| **Repository** | [View Repository →](https://github.com/mrvanshgoel/Searchtube) |

**What it does**

SearchTube collects YouTube video metadata and live chat messages, stores them in a SQLite database via a Flask API, and supports channel monitoring workflows. It uses a combination of direct HTTP requests and Selenium for pages requiring JavaScript rendering.

**Architecture**

```
[YouTube (HTTP / Selenium)]
        │
        ▼
[Async Scraper with Retry Logic]
        │
        ▼
[BeautifulSoup HTML Parser]
        │
        ▼
[Flask REST API]
        │
        ▼
[SQLite Database] ──► [Metadata / Chat / Channel Tables]
        │
        ▼
[Logging System]
```

**What I learned**

SearchTube taught me how to architect a Python backend around a scraping pipeline, how to use Flask to expose data via a REST API, and how to handle the practical challenges of web scraping: dynamic content, retries, and structured storage.

</details>

---

<details>
<summary><b>🛡️ YT Mod Logger — YouTube Moderation Monitoring Tool</b></summary>

<br/>

| Category | Details |
|----------|---------|
| **What it is** | A Python tool that tracks YouTube live chat moderation actions and delivers structured logs to Discord |
| **Tech Stack** | Python, YouTube Data API v3, OAuth 2.0, Selenium, Discord Webhooks, Logging |
| **Key Features** | OAuth authentication, moderator action detection, timeout/ban tracking, Discord webhook delivery |
| **Integration** | YouTube Data API for live chat data; Discord webhooks for real-time notification delivery |
| **Repository** | [View Repository →](https://github.com/mrvanshgoel/YT-ModLogger) |

**What it does**

YT Mod Logger connects to a YouTube channel's live chat via the YouTube Data API using OAuth authentication, monitors for moderation actions (timeouts, bans, message deletions), and sends structured event logs to a Discord channel via webhooks in real time.

**Architecture**

```
[YouTube Data API v3]
        │
        ▼
[OAuth 2.0 Authentication]
        │
        ▼
[Live Chat Poller]
        │
        ▼
[Moderation Event Detector]
        ├── Timeout detection
        ├── Ban detection
        └── Message deletion detection
        │
        ▼
[Structured Log Formatter]
        │
        ▼
[Discord Webhook Sender] + [Local Log File]
```

**What I learned**

This project gave me practical experience with OAuth 2.0 authentication flows, the YouTube Data API, and designing an event-driven monitoring loop. Integrating Discord webhooks taught me how to connect services together via HTTP APIs.

</details>

---

<details>
<summary><b>📋 ClipBot — YouTube API Content Processing Tool</b></summary>

<br/>

| Category | Details |
|----------|---------|
| **What it is** | A Python tool for automating YouTube video metadata collection and processing via the YouTube Data API |
| **Tech Stack** | Python, YouTube Data API v3, REST APIs, JSON Processing |
| **Key Features** | Paginated API traversal, metadata extraction, structured JSON output, quota-aware request handling |
| **Repository** | Currently private and under active development |

**What it does**

ClipBot automates the process of collecting and structuring YouTube video metadata using the official Data API. It handles paginated responses automatically, extracts structured fields (title, ID, stats, tags, timestamps), and outputs clean JSON for downstream use.

**What I learned**

Building ClipBot introduced me to API pagination patterns, quota management, and writing Python code that handles real-world API quirks like varying response schemas and rate limits.

> **Project Status:** Currently private and under active development. Public release planned after feature completion and documentation cleanup.

</details>

---

## Projects & Learning

<div align="center">

| Area | What I've Built / Learned |
|------|--------------------------|
| **Android Development** | Full Android app (NoteSphere) with Firebase, REST API integration, SQLite, AI features |
| **Machine Learning** | Hybrid recommendation system using PySpark ALS + TF-IDF on MovieLens dataset |
| **Backend Development** | REST APIs with Node.js/Express.js and Flask; Firebase and SQLite for data storage |
| **Python Automation** | Web scraping with BeautifulSoup + Selenium; async scraping; retry logic |
| **API Integration** | YouTube Data API v3, Gemini AI API, Discord Webhooks, OAuth 2.0 |
| **Data Processing** | Pandas, NumPy, PySpark for data cleaning and transformation |
| **Cloud** | AWS EC2 instance setup, Linux server management, SSH, application deployment |
| **Version Control** | Git and GitHub for all projects |

</div>

---

## Achievements

- Developed a Hybrid Movie Recommendation System combining PySpark ALS collaborative filtering and TF-IDF content-based filtering with a Streamlit interface
- Built NoteSphere, an AI-powered Android study application integrating Gemini AI for flashcard, quiz, and chat functionality
- Created YouTube automation tools in Python including a moderation tracker with Discord webhook delivery and a chat/metadata collection system with a Flask + SQLite backend
- Worked across the full stack: Android (Java) + Node.js + Firebase + REST APIs in a single project
- Deployed and managed an application on AWS EC2 with Linux server configuration via SSH

---

## GitHub Analytics

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=mrvanshgoel&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D0D0D&title_color=8B5CF6&icon_color=6D28D9&text_color=E5E7EB" />

<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrvanshgoel&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D0D0D&title_color=8B5CF6&text_color=E5E7EB" />

</div>

---

## GitHub Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=mrvanshgoel&theme=tokyonight&hide_border=true&background=0D0D0D&stroke=8B5CF6&ring=6D28D9&fire=A78BFA&currStreakLabel=8B5CF6&sideLabels=8B5CF6&dates=6B7280" />

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=mrvanshgoel&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" />

</div>

---

## Contribution Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mrvanshgoel&theme=tokyo-night&bg_color=0D0D0D&color=8B5CF6&line=6D28D9&point=A78BFA&area=true&area_color=4C1D95&hide_border=true" />

</div>

---

## Snake Animation

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mrvanshgoel/mrvanshgoel/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mrvanshgoel/mrvanshgoel/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/mrvanshgoel/mrvanshgoel/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

## Current Focus

```yaml
status: BCA Student

currently_learning:
  - Data Structures & Algorithms
  - Backend Development (Node.js, Flask)
  - Machine Learning (Scikit-Learn, PySpark)
  - Cloud Fundamentals (AWS)
  - System Design basics

actively_building:
  - NoteSphere (AI-powered Android study app)
  - SearchTube (YouTube metadata & chat collection)
  - ML projects for learning and portfolio

goal:
  - Software Development Internship
  - Backend Development roles
  - Python / ML engineering roles

values:
  - Learn by building real projects
  - Understand the fundamentals properly
  - Write code I can explain and maintain
```

---

## Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/mrvanshgoel/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D0D0D" />
</a>
&nbsp;
<a href="mailto:mrvanshgoel@gmail.com">
  <img src="https://img.shields.io/badge/Email-Reach%20Out-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D0D0D" />
</a>
&nbsp;
<a href="https://github.com/mrvanshgoel">
  <img src="https://img.shields.io/badge/GitHub-Follow-E5E7EB?style=for-the-badge&logo=github&logoColor=white&labelColor=0D0D0D" />
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" width="100%" />

<br/>

<img src="https://komarev.com/ghpvc/?username=mrvanshgoel&color=8B5CF6&style=for-the-badge&label=PROFILE+VIEWS&abbreviated=true" />

</div>
