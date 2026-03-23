# 🤖 Mood Based AI Chatbot

An interactive AI chatbot built with **Streamlit** and **LangChain**, powered by **Mistral AI**, where you can chat with different AI personalities based on mood.

---

## 🚀 Features

* 🎭 Multiple AI personalities:

  * 😡 Angry
  * 😂 Funny
  * 😢 Sad
* 💬 Real-time chat interface using Streamlit
* 🧠 Context-aware conversations with session memory
* 🔄 Reset chat functionality
* ⚡ Fast and simple UI

---

## 🧠 How It Works

1. User selects an AI mood/personality
2. A **System Message** sets the behavior of the AI
3. User sends messages via chat input
4. The model responds according to the selected personality
5. Conversation history is stored in session state

---

## 📦 Tech Stack

* **Python**
* **Streamlit** – UI framework
* **LangChain** – message handling
* **Mistral AI** – language model
* **python-dotenv** – environment management

---

## 📁 Project Structure

```
project/
│── app.py
│── requirements.txt
│── .env
│── README.md
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <your-project-folder>
```

2. (Optional) Create virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```
MISTRAL_API_KEY=your_api_key_here
```

> ⚠️ Keep your API keys secure and never share them publicly.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 💡 Usage

* Select a mood from the top:

  * 😡 Angry → aggressive replies
  * 😂 Funny → humorous replies
  * 😢 Sad → emotional replies

* Start chatting in the input box

* Type **`0`** to stop the conversation

* Click **🔄 Reset Chat** to start fresh

---

## 📌 Example Interaction

**Mode:** 😂 Funny
**User:** Tell me a joke
**AI:** Why don’t programmers like nature? Too many bugs! 😄

---

## ⚠️ Notes

* Changing the mode resets the conversation automatically
* Responses depend on the model and may vary
* Session data is not stored permanently

---

## 🔮 Future Improvements

* Add more personalities (Sarcastic, Motivational, etc.)
* Multi-model support (OpenAI, Groq)
* Save chat history
* Voice input/output

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.
