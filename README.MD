# 🧠 NutriBot - AI Fitness & Diet Chatbot (LangFlow)

NutriBot is an **AI-powered fitness and diet chatbot** built using **LangFlow**.  
It interacts with users step-by-step to collect their health goals, diet preferences, and activity levels — then generates a **personalized workout and nutrition plan**.

This repo includes **two LangFlow versions** of NutriBot:

---

## ⚙️ Versions Included

### 🟢 `nutribot_ollama_flow.json`
- Uses **Ollama LLM** (local model)
- Runs entirely **offline** on your system
- Perfect for those who want privacy and local inference
- Compatible with models like `llama3`, `mistral`, `phi3`, etc.
- ⚡ No API key required

#### 🔧 How to Use:
1. Install and run [Ollama](https://ollama.com/download)
2. Open [LangFlow](https://github.com/langflow-ai/langflow)
3. Import `nutribot_ollama_flow.json`
4. Choose your local Ollama model in the LLM node
5. Run the chatbot!

---

### 🔵 `nutribot_gemini_flow.json`
- Uses **Google Gemini API**
- Provides more fluent and contextual diet & fitness suggestions
- Ideal for cloud-based or production AI setups
- Requires a Google Gemini API key

#### 🔧 How to Use:
1. Get your Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a `.env` file with:
  (GOOGLE_API_KEY=your_api_key_here)
3. Open [LangFlow](https://github.com/langflow-ai/langflow)
4. Import `nutribot_gemini_flow.json`
5. Add your API key in LangFlow’s environment settings
6. Run the chatbot!

---

## 💪 Features
- Step-by-step question flow for custom fitness and diet planning  
- Separate flows for **local (Ollama)** and **cloud (Gemini)** LLM setups  
- Modular and easy to modify for other LLMs (OpenAI, Claude, etc.)  
- Ready-to-import LangFlow `.json` files  
- Can be extended with memory, APIs, or database integration

---

## 📁 Project Structure

NutriBot/

│

├── nutribot_ollama_flow.json # Flow using Ollama LLM

├── nutribot_gemini_flow.json # Flow using Gemini LLM

├── README.md # Documentation (this file)

├── .env.example # Placeholder for Gemini API key

└── .gitignore # Prevents sensitive uploads


---

## 🧩 Files Overview
| File | Description |
|------|--------------|
| `nutribot_ollama_flow.json` | LangFlow flow using Ollama (local LLM) |
| `nutribot_gemini_flow.json` | LangFlow flow using Gemini (cloud LLM) |
| `.env.example` | Sample env file for Gemini API key |
| `.gitignore` | Protects secrets from being uploaded |
| `README.md` | Project documentation |

---

## 🧠 Future Improvements
- Add **Conversation Memory** for contextual responses  
- Integrate **nutrition APIs** for real diet suggestions  
- Create a **web interface** (React or Streamlit frontend)  
- Add **user authentication** for personalized dashboards

---

## 👨‍💻 Author
**Rahul Bansal**  
AI & Web Development Enthusiast  
*Project Type:* AI Chatbot · LangFlow · LLM Integration  
**Tags:** `LangFlow` `Ollama` `Gemini` `ChatGPT` `AI` `Fitness` `Diet`


