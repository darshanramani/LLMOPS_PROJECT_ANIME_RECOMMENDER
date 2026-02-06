# 🎌 Anime Recommender System (LLM + MLOps)

This project is an **AI-powered Anime Recommendation System** that suggests anime based on **natural language preferences** like:

> *“Anime with continuous fights between best friends”*

Instead of using fixed filters, the system understands the **meaning** of the user’s query and recommends anime accordingly.

---

## 🔍 What does this project do?

* Takes **user input in plain English**
* Searches anime data using **semantic similarity**
* Uses a **Large Language Model (LLM)** to generate clear and personalized recommendations
* Displays results through a **simple web interface**

---

## 🧠 How does it work? (Simple Flow)

1. **Anime data** (CSV file) is cleaned and combined into meaningful text
2. Text is converted into **vector embeddings** and stored in a vector database
3. User query is also converted into an embedding
4. Relevant anime data is retrieved using **similarity search**
5. An **LLM** generates final recommendations with explanations
6. Results are shown in a **Streamlit web app**

---

## 🧩 Project Structure (High Level)

```
ANIME RECOMMENDER
│
├── app/                → Streamlit UI (user interface)
├── src/                → Core recommendation logic
├── pipeline/           → End-to-end recommendation pipeline
├── data/               → Anime CSV datasets
├── chroma_db/          → Vector database storage
├── utils/              → Logging and error handling
├── config/             → API keys and model settings
├── Dockerfile          → Containerization
├── llmops-k8s.yaml     → Kubernetes deployment
```

---

## 🛠️ Technologies Used (Beginner Friendly)

* **Python** – Core programming language
* **Streamlit** – Web interface for user interaction
* **LangChain** – Connects LLMs with retrieval logic
* **ChromaDB** – Stores and searches vector embeddings
* **HuggingFace Embeddings** – Converts text into vectors
* **Groq LLM** – Generates human-like recommendations
* **Docker** – Packages the app into containers
* **Kubernetes (Minikube)** – Runs containers reliably
* **Grafana** – Monitors system and resource usage

---

## 📊 Monitoring & Observability

* Integrated **Grafana dashboards** to monitor:

  * Pods and containers
  * CPU & memory usage
  * Cluster health and cost visibility

This helps understand how the system behaves in production.

---

## 🎯 Why this project?

* Learn **LLM-based recommendation systems**
* Practice **real-world MLOps workflows**
* Understand **Docker + Kubernetes deployment**
* Gain hands-on experience with **observability tools**

---

## 🚀 How to Run (High Level)

1. Build vector database using the pipeline
2. Start the Streamlit app
3. Enter anime preferences in the UI
4. Get AI-generated recommendations

---

## 📌 Future Improvements

* Add user login and history
* Improve recommendation accuracy
* Deploy on cloud with public access
* Add CI/CD pipeline

---

## 🤝 Author

**Darshan Ramani**
Master’s in Computer Science | AI & MLOps Enthusiast

🔗 GitHub: *https://github.com/darshanramani*
🔗 LinkedIn: *https://www.linkedin.com/in/darshan-ramani/*

