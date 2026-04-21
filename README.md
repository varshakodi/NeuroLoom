# 🧠 NeuroLoom

**Weaving cognitive states, one song at a time.**

NeuroLoom is an interactive **AI-powered music therapy experience** that transforms raw thoughts into a personalized emotional journey.
By combining cognitive state analysis, weather-based ambiance, and adaptive music sequencing, it creates a **5-song bridge** that guides users from their current emotional state to a better one.

---

## ✨ Features

### 🧠 AI Mood Analysis

* Uses **Gemini AI** to interpret user thoughts and detect emotional state
* Maps emotions into a **2D cognitive space (Energy × Valence)**
* Generates a narrative describing the user’s emotional journey 

---

### 🎵 Adaptive Music Bridge

* Builds a **step-by-step playlist** that transitions mood gradually
* Uses a custom **bridge algorithm** to move from start → target state
* Each song represents a point in emotional transformation

---

### 🌦️ Weather-Driven UI

* Real-time weather using **OpenWeather API**
* Dynamic color palettes based on conditions (clear, rain, mist, etc.)
* Optional manual override via interactive UI

---

### 🎧 Embedded Music Player

* Automatically fetches YouTube tracks (no API key needed)
* Inline player for seamless listening experience

---

### 🧘 Subconscious Mode (Hidden Feature)

* Unlockable immersive full-screen experience
* Mouse-reactive particle system
* Designed for introspection and sensory reset 

---

### 🌌 Emotional Feedback System

* Dynamic UI reacts to user text input
* Generates:

  * Mood labels
  * Narrative descriptions
  * A poetic **fortune message**

---

## 🏗️ Architecture

```
NeuroLoom/
│
├── app.py                # Main Streamlit app (UI + flow)
├── services/             # External integrations
│   ├── gemini.py         # AI mood analysis + fortune generation
│   ├── weather.py        # Weather fetching + mood mapping
│   └── music.py          # YouTube scraping + player
│
├── components/           # UI components
│   ├── journey_viz.py    # Mood transition visualization
│   ├── subconscious.py   # Immersive particle system
│   └── weather_switcher.py
│
├── core/
│   └── bridge.py         # Playlist generation logic
│
├── data.py               # Song dataset
├── styles.py             # UI themes + palettes
└── config.py             # Environment configuration
```

---

## ⚙️ Tech Stack

* **Frontend/UI:** Streamlit
* **AI:** Google Gemini API
* **APIs:** OpenWeather
* **Music Source:** YouTube (scraped search)
* **Languages:** Python
* **Libraries:**

  * `streamlit`
  * `requests`
  * `pandas`, `numpy`
  * `google-generativeai`

---



## 💡 Inspiration

NeuroLoom explores the idea that:

> music isn’t just entertainment — it’s a **transition tool for emotional states**

---



## 📬 Future Improvements

* Spotify integration
* Real-time biofeedback (heart rate, etc.)
* Better recommendation models
* Mobile-friendly UI




