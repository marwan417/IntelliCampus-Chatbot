# 🚀 [Tips Hindawi](https://www.tipshindawi.com/) Internship (August–October) 2026[cite: 1]

> 🎓 This project was built during the [ **Tips Hindawi** ](https://www.tipshindawi.com/) **Internship (August–October) 2026**[cite: 1].

## 👤 Participant[cite: 1]

| Field            | Value                                |
| ---------------- | ------------------------------------ |
| Full Name        | Marwan Hassan Morsi (مروان حسن مرسي) |
| Project Name     | Helwan Academic Assistant Chatbot    |
| GitHub Username  | [marwan417](https://github.com/marwan417) |
| Internship Batch | August–October 2026[cite: 1]        |
| Training Program | Large Language Models (LLMs) Program[cite: 1]|
| Organization     | [**Edrak for Ai**](https://edrak4ai.com/en)[cite: 1] |

---

# 📖 Project Overview[cite: 1]

This project is an AI-powered Academic Assistant Chatbot built for the Intelligent Systems Engineering program at Helwan National University[cite: 2]. The application acts as a smart academic advisor that helps students by answering questions about graduation requirements, syllabuses, course prerequisites, and building locations[cite: 2].

---

# ✨ Features[cite: 1]

* **RAG-Based System:** Uses Retrieval-Augmented Generation to search through university documents and extract accurate answers[cite: 2].
* **Local LLM Integration:** Powered by the `qwen2.5:7b` model running locally via Ollama for fast, secure, and private processing[cite: 2].
* **Intelligent Query Routing:** Automatically categorizes user questions into academic, location, recommendations, greetings, or out-of-scope topics[cite: 2].
* **Personalized Course Recommendations:** Extracts the user's GPA to provide tailored academic advice and suitable course suggestions[cite: 2].
* **Bilingual UI Rendering:** Automatically detects Arabic text and aligns the UI right-to-left (RTL) for a seamless user experience[cite: 2].

---

# 🛠️ Technologies Used[cite: 1]

* **Python**[cite: 2]
* **Streamlit:** For building the interactive web interface[cite: 2].
* **LangChain:** For building the LLM and RAG pipelines[cite: 2].
* **Ollama:** To serve the local open-weight model (`qwen2.5:7b`)[cite: 2].
* **Google Generative AI:** For generating text embeddings using `gemini-embedding-001`[cite: 2].
* **FAISS:** As the vector database for efficiently storing document chunks[cite: 2].
* **PyMuPDF:** For parsing and loading text from academic PDF documents[cite: 2].
* **ngrok:** For exposing the local server and creating secure public URLs[cite: 2].

---

# ⚙️ Installation[cite: 1]

1. **Install the required packages:**
   ```bash
   pip install streamlit langchain-ollama langchain-community langchain-text-splitters faiss-cpu pyngrok pymupdf sentence-transformers langchain-huggingface langchain-google-genai
   ```[cite: 2]

2. **Install Ollama and pull the model:**
   ```bash
   curl -fsSL [https://ollama.com/install.sh](https://ollama.com/install.sh) | sh
   ollama pull qwen2.5:7b
   ```[cite: 2]

3. **Set your API Keys:**
   Set up your Gemini API key in the environment variables:
   ```bash
   export GEMINI_API_KEY="your_api_key_here"
   ```[cite: 2]

---

# 🚀 Usage[cite: 1]

1. **Start the Ollama Server:**
   ```bash
   ollama serve
   ```[cite: 2]

2. **Run the Streamlit Application:**
   ```bash
   streamlit run app.py
   ```[cite: 2]

3. The application will launch at port `8501`, and you can start interacting with the academic assistant[cite: 2]. If you are using Google Colab, `ngrok` will generate a public link to access the interface[cite: 2].

---

# 📸 Demo[cite: 1]

*(قم بإضافة صور (Screenshots) أو فيديو قصير (GIF) يوضح طريقة عمل الشات بوت هنا)*

---

# 📈 Results[cite: 1]

Successfully developed a robust academic assistant that accurately answers student inquiries based on the provided PDF rules and text files[cite: 2]. The system efficiently handles PDF text extraction, data chunking, and querying the FAISS vector database to retrieve highly relevant context for the LLM[cite: 2].

---

# 🔮 Future Improvements[cite: 1]

* Integrate more university documents and syllabuses for other departments.
* Add user authentication to securely save student profiles and their academic history.
* Deploy the application to a cloud hosting platform such as AWS or Streamlit Community Cloud for continuous access.

---

# 📚 About the Internship[cite: 1]

This project was developed as part of the [**Tips Hindawi**](https://www.tipshindawi.com/) **Internship (August–October) 2026**, and it will be showcased on the official [Tips Hindawi](https://www.tipshindawi.com/) website[cite: 1].

[Tips Hindawi](https://www.tipshindawi.com/) is the internships department of [**Edrak for Ai**](https://edrak4ai.com/en), and the internship encourages participants to build real-world projects, apply practical skills, and showcase their work through GitHub[cite: 1].

For more information about the internship, training programs, and upcoming batches, visit the official [Tips Hindawi](https://www.tipshindawi.com/) website[cite: 1].

---

# 📄 License[cite: 1]

This project is shared for educational and portfolio purposes[cite: 1].