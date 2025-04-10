
# 🔎 LangChain-Powered AI Search Engine  
*Smart Answers from the Web, Wikipedia, and Arxiv – All in One Chat!*

Welcome to your **intelligent conversational search assistant**, built with **LangChain**, **Groq LLMs**, and **Streamlit**. This app combines the power of **cutting-edge LLMs** with **real-time knowledge sources** like **Wikipedia**, **Arxiv**, and **DuckDuckGo** to bring you instant, context-aware answers—all inside an intuitive chat interface.

---

## 🚀 Features

- **Conversational AI Interface:** Chat naturally with the assistant via an elegant Streamlit UI.
- **Multiple Knowledge Tools:** Seamlessly queries:
  - 🔍 **DuckDuckGo** for real-time web searches  
  - 📚 **Wikipedia** for encyclopedic knowledge  
  - 🧠 **Arxiv** for scientific and academic insights  
- **Powered by Groq's Llama3:** Utilizes Groq’s blazing-fast **Llama3-8b-8192** for rapid, intelligent responses.
- **Streaming Responses:** Experience real-time AI thinking through **LangChain's streaming callbacks**.
- **Agentic Reasoning:** Employs **LangChain Agents (ZERO_SHOT_REACT_DESCRIPTION)** to decide which tools to use per question.

---

## 🧠 Built With

- **[Streamlit](https://streamlit.io/)** – For building the responsive and beautiful UI.
- **[LangChain](https://www.langchain.com/)** – Framework for agent-based LLM orchestration.
- **[Groq + Llama3](https://groq.com/)** – Ultra-low-latency LLM inference.
- **[DuckDuckGo Search API](https://duckduckgo.com/)** – For general search queries.
- **[Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page)** – To access human-curated knowledge.
- **[Arxiv API](https://arxiv.org/help/api/index)** – For scientific publications and technical depth.

---


## 🔧 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/UroojAshfa/ai-search-engine.git
   cd ai-search-engine
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app:**
   ```bash
   streamlit run app.py
   ```

4. **Enter your Groq API key** in the sidebar and start chatting!

---

## 🔐 Environment Variables

If you're using a `.env` file, include your Groq API key:
```
GROQ_API_KEY=your-groq-key-here
```

---

## 💡 Example Queries

- "What is quantum entanglement?"
- "Latest research on transformer models?"
- "Tell me about LangChain"
- "Who won the Nobel Prize in Physics 2023?"

---

## 🏆 Why This Project Rocks

- **Combines Search and Chat:** One interface, multiple information sources.
- **Production-Ready:** Easily extendable for knowledge bots, academic assistants, or research tools.
- **Ultra-Fast Inference:** Groq's chips provide unmatched LLM speed.
- **Minimal Setup:** No complex backend—just Streamlit, LangChain, and a Groq API key.

---


## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Acknowledgements

Thanks to the developers of **LangChain**, **Groq**, **Streamlit**, and the open APIs from **Wikipedia**, **Arxiv**, and **DuckDuckGo** that made this project possible.
