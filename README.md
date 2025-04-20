## AI-Venture: GenAI Powered Travel Planner 🗺️


### 👾 | Overview

**AI-Venture** is an intelligent travel planning assistant powered by **Google's Gemini API** and **Generative AI** capabilities. It dynamically creates personalized travel itineraries by integrating *structured function-calling, few-shot prompting, document understanding, embeddings + Vector Store and RAG* — all within a seamless interactive notebook experience.

This project was built as part of the **"Gen-AI Intensive Course Capstone 2025Q1"** by Google and Kaggle, solving a real-world challenge: eliminating third-party travel broker fees by using AI to plan budget-conscious and experience-rich journeys.

---

### 🔍 | Key Features

  *  🧠 Chatbot Travel Assistant using Gemini AI with structured function calling.
  *  🏨 Budget Motel Finder based on price and rating.
  *  🍽️ Food & Restaurant Recommender by type, price range, or dietary preference.
  *  🗽 Attraction Curator matching traveler interests and family-friendly options.
  *  📄 RAG (Retrieval-Augmented Generation) from uploaded travel guides using FAISS and embeddings.
  *  ✍️ Few-shot Prompting to guide Gemini for consistent itinerary planning.
  *  🧳 Personalized Multi-city Itinerary Generator with cost-awareness and activity spread.

---

### ✨ | Gen AI Capabilities Demonstrated

 *  🧾 Structured Output & JSON Mode
 *  🧑‍🏫 Few-Shot Prompting
 *  📑 Document Understanding
 *  📚 Retrieval-Augmented Generation (RAG)
 *  🧬 Embeddings + Vector Store
 *  🎯 Function Calling

---

### 🛠️ | Technologies Used

| Technology  | Purpose |
| ------------- | ------------- |
| Gemini AI  | LLM-powered conversation and reasoning  |
| Gemini Embeddings  | Embedding travel guide chunks  |
| FAISS  | Fast Approximate Nearest Neighbors Search  |
| Pandas / NumPy  | Data wrangling & filtering  |
| JSON  | Reading/writing structured data  |
| fitz (PyMuPDF)  | Extracting text and metadata from PDFs  |

---

### 🧳 | Sample Travel Queries

Try asking Gemini:
 *  “Show me motels in Paris under $50”
 *  “Find vegetarian restaurants in Rome”
 *  “What museums can I visit in Berlin?”
 *  “Find family friendly attractions in Barcelona”
 *  “Highly rated motels in Amsterdam with rating over 4.5”

---

### 📂 | Notebook Highlights

| Section  | Description |
| ------------- | ------------- |
| 📌 Setup & Gemini Configuration  | Load APIs and authenticate securely  |
| 🧾 PDF Parsing & Chunking  | Parse uploaded guides into semantic chunks  |
| 🔎 Function Calling Definitions  | Enable Gemini to call Python logic  |
| 🧬 Embeddings & Vector Store | Embed content and search using FAISS  |
| 🧠 Interactive Chat with Gemini  | AI suggests functions & passes arguments  |
| 📊 Results Rendering  | Travel options displayed dynamically  |
| 🪶 RAG-Based QA on Brochures  | Use FAISS to retrieve relevant chunks and generate grounded answers  |

---

### 💪🏼 | Challenges Faced

 *  Embedding and chunking large PDFs without losing semantic meaning.
 *  Maintaining context fidelity in multi-turn user queries.
 *  Balancing function-calling precision vs model creativity.
 *  Ensuring cost-efficient solutions within the user's constraints.

---

### 🚀 | Getting Started

Prerequisites:
 *  Google Cloud Project with Generative AI API access
 *  Kaggle or Colab environment
 *  Basic knowledge of Python & Pandas

Setup Instructions:
1. Clone the repo: `git clone https://github.com/yourusername/ai-venture.git`
2. Open the notebook: `ai-venture-gen-ai-powered-travel-planner.ipynb`
3. Authenticate with Google Cloud
4. Run all cells and interact with Gemini!

---

### 📣 | Future Enhancements

 *  🧭 Real-time integration with Google Maps APIs
 *  📦 Flight booking and weather APIs
 *  🧠 LangChain Agents for dynamic routing
 *  🗂️ Save and export full itineraries as PDF

--- 

### 🤝 | Acknowledgments
Thanks to **Google Cloud**, **Kaggle**, and the **Gen AI Capstone Team** for providing this incredible learning opportunity and support.

---

### 📌 | License
MIT License. Free to use, modify, and distribute with attribution.
