# Hi — I'm Aadhithya S.

Software Developer | Java · Python · JavaScript · Full‑Stack Engineer

I build production-oriented backend systems, full‑stack web applications, and applied AI/ML prototypes. The README below summarizes my active repositories, their primary technologies, and the quickest steps to run or evaluate each project.

---

## Portfolio overview

My work spans three main areas:

- Backend systems: Java + Spring Boot, REST API design, authentication and authorization.
- Frontend applications: React + Vite, responsive UI, client-side state and API integration.
- AI/ML prototypes: Python + Streamlit, NLP and audio processing using transformer models.

---

## Repository summaries

Below are selected public repositories with a one-line description, primary stack, and the fastest way to run them locally.

- **food-delivery-backend** — Backend APIs for an online food delivery system. Stack: Java 21, Spring Boot, Spring Security, Spring Data JPA, MySQL (JWT authentication, role-based access).

  Quick start:
  ```bash
  mvn spring-boot:run
  ```
  Repository: https://github.com/aadhithya10112004/food-delivery-backend

- **food-delivery-frontend** — React + Vite frontend for the food delivery platform (customer and admin interfaces). Stack: React, Vite, React Router, Axios, Context API.

  Quick start:
  ```bash
  npm install
  npm run dev
  ```
  Repository: https://github.com/aadhithya10112004/food-delivery-frontend

- **AI-Resume-Analyzer** — Streamlit application that extracts resume text, vectorizes with TF‑IDF, and matches resumes to job descriptions. Stack: Python, Streamlit, scikit-learn, SQLite.

  Quick start:
  ```bash
  pip install -r requirements.txt
  streamlit run app.py
  ```
  Repository: https://github.com/aadhithya10112004/AI-Resume-Analyzer

- **EmotionVoiceAI** — Speech-to-text, emotion classification and TTS demo with analytics dashboards. Stack: Python, Streamlit, Transformers, Faster‑Whisper, Edge‑TTS.

  Quick start:
  ```bash
  pip install -r requirements.txt
  streamlit run app.py
  ```
  Repository: https://github.com/aadhithya10112004/EmotionVoiceAI

- **fridge_recipe** — React + Vite recipe recommender that suggests dishes based on available ingredients.

  Quick start:
  ```bash
  npm install
  npm run dev
  ```
  Repository: https://github.com/aadhithya10112004/fridge_recipe

- **portfolio-react** — Personal portfolio built with React (development scripts available in the repository).

  Repository: https://github.com/aadhithya10112004/portfolio-react

- **Smart_life** — Streamlit-based wellness application combining LLM chat, document summarization, news summarization, voice input, and a local SQLite store.

  Quick start:
  ```bash
  pip install -r requirements.txt
  streamlit run app.py
  ```
  Repository: https://github.com/aadhithya10112004/Smart_life

- **AI-Medical-Assistant (MediCap)** — Health assistant built with Streamlit offering medication information, basic disease prediction helpers, and a hospital finder. Includes a medical disclaimer.

  Quick start:
  ```bash
  pip install -r requirements.txt
  streamlit run app.py
  ```
  Repository: https://github.com/aadhithya10112004/AI-Medical-Assistant

- **agentic_rag-BriefSync** — Small RAG (retrieval-augmented generation) demo for PDF Q&A. Uses chunking, SentenceTransformers embeddings, Pinecone, and a local LLM (Ollama) for generation.

  Repository: https://github.com/aadhithya10112004/agentic_rag-BriefSync

---

## Notes and prerequisites

- Several projects require third-party services or API keys (for example, Pinecone, Ollama, NewsAPI, SerpAPI, and YouTube Data API). Check each repository's README for exact environment variables and configuration.
- Streamlit projects in this portfolio typically start with `streamlit run app.py` and expose a local web UI on port 8501.
- The food delivery application comprises two separate repositories (backend and frontend) and can be run end-to-end by starting the backend first and then the frontend.

---

## How to evaluate or run demos quickly

1. Streamlit demos (AI-Resume-Analyzer, EmotionVoiceAI, Smart_life, AI-Medical-Assistant) provide the fastest way to assess AI/ML work — they require minimal setup and run locally.
2. For a full-stack demonstration, run `food-delivery-backend` then `food-delivery-frontend` and verify the API integration.
3. For RAG or embedding experiments, review `agentic_rag-BriefSync` and follow the configuration instructions for Pinecone and Ollama.

---

## Opportunities & contact

I am actively seeking internship and early-career full‑time roles in backend engineering, full‑stack development, or applied AI engineering. For a project walkthrough, code review, or a short demo, please open an issue in the relevant repository or contact me via GitHub.

---

Made with care by Aadhithya S.