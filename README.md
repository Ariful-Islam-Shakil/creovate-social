# 🚀 Creovate Social

**Creovate Social** is a **CrewAI-based intelligent social media agent** that generates **context-aware Facebook posts** using real-world signals such as **time, weather, mood, topic, and occasion**, with optional **auto-posting or scheduling** support.

The system uses a **multi-agent architecture** to plan, write, validate, and publish high-quality Facebook content automatically.

---

## ✨ Key Features

* 🧠 **Multi-Agent System** powered by CrewAI
* ⏰ Time-aware post generation
* 🌦 Weather-based content adaptation
* 😊 Mood & context-driven tone control
* 📝 Smart content strategy & writing agents
* 🛡 Content quality & policy checking
* 📘 Facebook Page auto-posting (Graph API)
* 🗂 Post history & logging support

---

## 🏗 Project Architecture (High-Level)

```
Context Agent → Strategy Agent → Writer Agent → Policy Agent → Publisher Agent
```

Each agent is responsible for a **single, well-defined task**, making the system modular and extensible.

---

## ⚙️ Project Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/creovate-social.git
cd creovate-social
```

---

### 2️⃣ Create & Activate Python Environment (pyenv)

Make sure **pyenv** is installed.

```bash
pyenv virtualenv 3.11.6 creovate-social
pyenv activate creovate-social
```

(Optional)

```bash
pyenv local creovate-social
```

---

### 3️⃣ Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

---

### 4️⃣ Environment Variable Setup

Create a `.env` file in the project root:

```bash
touch .env
```

Add the following variables (example):

```env
# LLM Provider
OPENAI_API_KEY=your_openai_key
# or
GROQ_API_KEY=your_groq_key

# Weather API
WEATHER_API_KEY=your_openweathermap_key

# Facebook Graph API
FB_PAGE_ACCESS_TOKEN=your_facebook_page_token
FB_PAGE_ID=your_facebook_page_id

# General
ENV=development
```

⚠️ **Note:**
Auto-posting is recommended for **Facebook Pages**, not personal profiles.

---

### 5️⃣ Run the Project

```bash
python main.py
```

---

## 📌 Example Use Cases

* Daily motivational posts
* Weather-based storytelling posts
* Event or campaign announcements
* Personal brand content automation
* Business page content scheduling

---

## 🛣 Roadmap

* [ ] Scheduler & cron-based posting
* [ ] Mood inference using sentiment analysis
* [ ] Multi-platform support (LinkedIn, Twitter)
* [ ] Web dashboard (FastAPI + UI)
* [ ] Analytics & engagement tracking

---

## 🤝 Contribution

Contributions, ideas, and improvements are welcome!
Feel free to open issues or submit pull requests.

---

### ⭐ Tagline

**Creovate Social — Create. Innovate. Post.**

---
