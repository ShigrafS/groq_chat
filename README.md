# DSCPL-AI Agent 🙏🧘‍♂️

A faith-based AI companion built with [Streamlit](https://streamlit.io/) and powered by [GROQ](https://groq.com/) + [LangChain](https://www.langchain.com/). This application acts as a spiritual guide that helps users with daily devotions, prayer, meditation, accountability, and spiritual check-ins using natural language AI.

## 🌟 Features

- 🕊 **Daily Devotion**: Choose from various devotional topics and receive structured, scripture-based content.
- 🙏 **Daily Prayer**: Generate meaningful prayers using the ACTS model.
- 🧘 **Daily Meditation**: Get scripture-centered meditative sessions and breathing guides.
- 🔄 **Daily Accountability**: Provides faith-based accountability encouragement for overcoming struggles.
- 🎥 **Video Devotions & Ideas**: Generates short-form video content ideas from scripture.
- 📖 **Verse-by-Verse Bible Recreation**: Retell Bible passages in modern, emotionally resonant styles.
- 💬 **Just Chat**: Talk freely with the AI about what's on your heart.
- 📺 **SocialVerse Integration**: Pulls inspiring community video posts from the SocialVerse API.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- A [GROQ API Key](https://console.groq.com/)
- A SocialVerse API Token (for video summaries)
- Optional: A [virtual environment](https://docs.python.org/3/tutorial/venv.html) (recommended)

### Installation

1. **Clone the Repository**

```bash
git clone https://github.com/ShigrafS/groq_chat.git
cd groq_chat
````

2. **Set Up Virtual Environment**

```bash
python -m venv chat
chat\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Configure Environment Variables**

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key_here
```

---

## 💻 Running the App

```bash
streamlit run app.py
```

Then open the link shown in the terminal, typically: [http://localhost:8501](http://localhost:8501)

---

## 🧠 Tech Stack

| Component         | Technology                          |
| ----------------- | ----------------------------------- |
| UI                | Streamlit                           |
| LLM API           | GROQ (LLaMA 3 - 8B via LangChain)   |
| Prompt Management | LangChain                           |
| Environment       | Python 3, dotenv                    |
| API Integration   | SocialVerse (for community content) |

---

## 🔐 Environment Variables

| Variable       | Description                                 |
| -------------- | ------------------------------------------- |
| `GROQ_API_KEY` | Your GROQ API key                           |
| `FLIC_TOKEN`   | SocialVerse API token (hardcoded in app.py) |

> **Note:** For production, consider storing all keys in a secure backend or environment vault.

---

## 📦 Dependencies

A sample `requirements.txt` may include:

```txt
streamlit
python-dotenv
langchain
langchain-groq
requests
```

---

## 📝 Example Use Cases

* A user selects **Daily Prayer** with the topic *Healing*. The app returns a custom ACTS-modeled prayer.
* A youth group member uses **Recreate the Bible (Verse-by-Verse)** to study *John 1:1* in a modern storytelling format.
* A digital creator uses **Inspiration Video Idea** to generate faith-centered video content for social media.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo, create a feature branch, and submit a pull request.

---

## 🙌 Acknowledgements

* [GROQ](https://groq.com/)
* [Streamlit](https://streamlit.io/)
* [LangChain](https://www.langchain.com/)
* [SocialVerse](https://socialverseapp.com/) API

---

## ✉️ Contact

For suggestions, collaboration, or questions:

* GitHub: [@ShigrafS](https://github.com/ShigrafS)

---
