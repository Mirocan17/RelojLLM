# ⌚ Smart Second-Hand Watch Recommendation & Style Assistant (RelojLLM)

This project brings together data science, machine learning, and large language models (LLMs) to recommend the best second-hand watches matching users' budgets and criteria, while offering custom AI-powered style analysis.

## 🚀 Features
- **Vector Similarity (Cosine Similarity):** Converts user criteria such as brand, dial color, strap type, case size, and budget into a vector space to precisely find the closest watches in the dataset.
- **AI Style Advisor (Google Gemini API):** Sends the recommended watch results to the `gemini-3.6-flash` model to generate custom, fluent, and friendly expert commentary for the user.
- **Gradio Interface:** Turns the entire system into an interactive, sleek, and user-friendly web interface accessible via browser.

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy** (Data Processing)
- **Scikit-Learn** (MinMaxScaler & Cosine Similarity)
- **Google GenAI SDK** (LLM Integration)
- **Gradio** (Web Interface)

## ⚙️ Installation and Execution (Google Colab)
To run the project in your own Colab environment:
1. Upload the `Reloj.ipynb` file to Google Colab.
2. Add your API key obtained from Google AI Studio to Colab's **Secrets (Key)** section under the name `GEMINI_API_KEY`.
3. Run the cells sequentially to launch the Gradio interface (and its public shareable link).

---
*Developed by Miro*
