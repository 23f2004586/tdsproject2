📌 What Is This?
----------------

Meet the **Data Analyst Agent**---an AI-driven assistant designed to eliminate tedious data crunching.

Upload your dataset and queries to instantly receive:

-   📊 Visual reports

-   🧠 AI-generated insights

-   ⚙️ Automated workflows

This tool is perfect for:

-   Analysts 🧾

-   Researchers 🔬

-   Startups & Businesses 📈

-   Anyone who loves turning raw data into knowledge

* * * * *

✨ Key Highlights
----------------

| Feature | Why It's Awesome 🚀 |
| --- | --- |
| 🤖 **AI-Powered Insights** | Leverages Google's Generative AI to deeply understand your data. |
| 📊 **Rich Visualizations** | Creates publication-ready plots with **Seaborn & Matplotlib**. |
| 🌍 **Web Scraper Mode** | Fetches and analyzes live data directly from URLs. |
| 📂 **Multi-Format Friendly** | Natively supports CSV, Excel, JSON, Parquet, and TXT. |
| 🔄 **Batch Questioning** | Processes multiple questions at once for comprehensive reports. |
| 🖥️ **Simple-to-Use Interface** | An intuitive and beginner-friendly experience. |

Export to Sheets

* * * * *

🚀 Getting Started
------------------

### 1️⃣ Clone the Repository

Bash

```
git clone https://github.com/your-username/data-analyst-agent.git
cd data-analyst-agent

```

### 2️⃣ Install Dependencies

Bash

```
pip install -r requirements.txt

```

### 3️⃣ Configure API Keys

Create a `.env` file in the project's root directory and add your key:

Code snippet

```
GEMINI_API_KEY="your_google_api_key"
LLM_TIMEOUT_SECONDS=240

```

### 4️⃣ Launch the Application

Bash

```
python -m uvicorn app:app --reload

```

Now, navigate to `http://localhost:8000/` in your browser. 🌐

* * * * *

🧑‍💻 How It Works
------------------

1.  **Prepare Your Questions** Create a plain `.txt` file listing your questions, one per line. For example: *What is the monthly revenue growth?* or *Correlate user age with purchase frequency.*

2.  **Upload Your Files** Use the web interface to upload your dataset (CSV, Excel, etc.) and your questions file.

3.  **Receive Your Analysis** The AI processes your request and instantly generates a complete report with summaries, insights, and visualizations.

* * * * *

🛠️ Tech Stack
--------------

-   **Backend:** FastAPI, LangChain, Google Generative AI, Pandas, NumPy

-   **Data Visualization:** Seaborn, Matplotlib

-   **Frontend:** HTML5, CSS, JavaScript (with a modern, Bootstrap-inspired UI)

✍️ Author
---------

-   **Jha Sumitkumar Gangadhar**

-   B.Sc. Student, IIT Madras

-   **GitHub:** '[@Sumit G Jha](https://github.com/23f2004586)'
-   **Linkedin:** https://www.linkedin.com/in/sumigjha

- Special Thanks to '[@sameer Thakur](https://github.com/23f2003673)'
* * * * *

📜 License
----------

This project is licensed under the **MIT License** -- free for personal and commercial use.