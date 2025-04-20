## AI-Venture: GenAI Powered Travel Planner 🗺️


### 👾 | Overview

**AI-Venture** is an intelligent travel planning assistant powered by **Google's Gemini API** and **Generative AI** capabilities. Travel planning can be overwhelming, expensive, and time-consuming. To solve this, I built **AI-Venture** to offer personalized travel itineraries — powered by AI, and designed to save you time, money, and stress.

By integrating *structured function-calling, few-shot prompting, document understanding, embeddings + Vector Store and RAG* — AI-Venture offers a seamless notebook experience that delivers budget-conscious and experience-rich travel plans.

This project was built as part of the **"Gen-AI Intensive Course Capstone 2025Q1"** by Google and Kaggle, solving a real-world challenge: eliminating third-party travel broker fees by using AI to plan budget-conscious and experience-rich journeys.

---

### 🔍 | Key Features

  *  🧠 **Chatbot Travel Assistant** using **Gemini AI** with structured function calling.
  *  🏨 **Budget Motel Finder** based on price and rating.
  *  🍽️ **Food & Restaurant Recommender** by type, price range, or dietary preference.
  *  🗽 **Attraction Curator** matching traveler interests and family-friendly options.
  *  📄 **RAG (Retrieval-Augmented Generation)** from uploaded travel guides using **FAISS** and **Embeddings** for grounded answers.
  *  ✍️ **Few-shot Prompting** to guide **Gemini** for consistent itinerary planning.
  *  🧳 **Personalized Multi-city Itinerary Generator** with cost-awareness and activity spread.

---

### ✨ | Gen AI Capabilities Demonstrated

 *  🧾 **Structured Output & JSON Mode:** Dynamic and flexible outputs for itinerary planning.
 *  🧑‍🏫 **Few-Shot Prompting:** Use minimal examples to guide AI's responses.
 *  📑 **Document Understanding:** Analyze and understand large datasets or PDFs with AI.
 *  📚 **Retrieval-Augmented Generation (RAG):** Pull in relevant content from travel guides to improve the AI's answers.
 *  🧬 **Embeddings + Vector Store:** Map and store content semantically for easier querying.
 *  🎯 **Function Calling:** Trigger custom functions to calculate costs, search, and handle dynamic responses.

---

### 🛠️ | Technologies Used

This project relies on a variety of tools to deliver the best travel-planning experience possible. Here's how each one contributes:

 *  **Gemini AI:** Google’s powerful large language model (LLM) that powers the conversational abilities and reasoning behind **AI-Venture**.
 *  **Gemini Embeddings:** By embedding chunks of travel guides, **Gemini Embeddings** helps AI understand and analyze vast amounts of travel data.
 *  **FAISS:** A fast similarity search tool that ensures **AI-Venture** can quickly retrieve the most relevant travel information, offering you precise recommendations in real-time.
 *  **Pandas / NumPy:** Data wrangling and filtering tools that help process and organize data efficiently for easy use.
 *  **JSON:** Enables structured data management for smooth data reading and writing.
 *  **fitz (PyMuPDF):** Used to extract text and metadata from uploaded PDF travel guides, enabling **AI-Venture** to parse and work with external travel resources effectively.

---

### 🧳 | Sample Travel Queries

Here are some sample travel queries you can try with **Gemini**:
 *  “Show me motels in Paris under $50”
 *  “Find vegetarian restaurants in Rome”
 *  “What museums can I visit in Berlin?”
 *  “Find family friendly attractions in Barcelona”
 *  “Highly rated motels in Amsterdam with rating over 4.5”

![Screenshot 2025-04-20 135524](https://github.com/user-attachments/assets/173a6ef5-12c7-49e1-8592-f4bfb880788c)
![Screenshot 2025-04-20 135604](https://github.com/user-attachments/assets/934524ff-288e-4e75-bb0e-ffbef47e8c34)

Feel free to try these in the interactive notebook or change them according to your own preferences!

---

### 📂 | Notebook Highlights

The notebook is divided into sections, each designed to make your travel planning more intuitive:

| Section  | Description |
| ------------- | ------------- |
| 📌 **Setup & Gemini Configuration**  | Load APIs and authenticate securely  |
| 🧾 **PDF Parsing & Chunking**  | Parse uploaded guides into semantic chunks  |
| 🔎 **Function Calling Definitions**  | Enable **Gemini** to call Python logic  |
| 🧬 **Embeddings & Vector Store** | Embed content and search using **FAISS**  |
| 🧠 **Interactive Chat with Gemini**  | AI suggests functions & passes arguments  |
| 📊 **Results Rendering**  | Travel options displayed dynamically  |
| 🪶 **RAG-Based QA on Brochures**  | Use **FAISS** to retrieve relevant chunks and generate grounded answers  |

---

### 💪🏼 | Challenges Faced

Building **AI-Venture** came with its own set of challenges:

 *  **Embedding and Chunking Large PDFs:** Ensuring that the meaning of the content is preserved when splitting travel guides.
 *  **Maintaining Context Fidelity:** With multi-turn queries, it was crucial to keep track of user intent and provide consistent responses.
 *  **Balancing Precision vs Creativity:** Striking the right balance between AI's precise function-calling and its ability to creatively suggest unique options.
 *  **Cost-Efficiency:** Ensuring that travel plans stayed within budget while still offering rich and varied experiences.

---

### 🚀 | Getting Started

To get **AI-Venture** up and running, follow these steps:

**Prerequisites:**
 *  A **Google Cloud Project** with **Generative AI API** access.
 *  A **Kaggle** or **Colab** environment to run the notebook.
 *  Basic knowledge of **Python** & **Pandas** for smooth interaction.

**Setup Instructions:**
1. Clone the repo: `git clone https://github.com/Alverok/AI-Venture-Kaggle-Capstone-Project.git`
2. Open the notebook: `AI-Venture: Kaggle Gen-AI Capstone Project.ipynb`
3. Authenticate with Google Cloud.
4. Run all cells and interact with **Gemini**!

---

### 📣 | Future Enhancements

 *  🧭 Real-time integration with **Google Maps APIs** for navigation.
 *  ✈️ **Flight booking** and **weather API** integrations.
 *  🦾 **LangChain Agents** for dynamic routing and adaptive itinerary generation.
 *  🗂️ Save and export **full itineraries** as PDFs for offline use.

--- 

### 🤝 | Acknowledgments
Thanks to **Google Cloud**, **Kaggle**, and the **Gen AI Capstone Team** for providing this incredible learning opportunity and support throughout the project!

---

### 📌 | License
MIT License. Free to use, modify, and distribute with attribution.
