![Demo Screenshot]("assets\Screenshot.png")

🤖 Gen AI Customer Support Assistant

This project demonstrates how Generative AI can be applied to customer support workflows. Using a dataset of mock support tickets, the notebook classifies issues, summarizes customer concerns, and drafts professional replies.

The goal of this project is to showcase practical Gen AI integration, data handling, and reproducibility in a portfolio-friendly way.

📊 Features

Ticket Classification → Labels tickets as Billing, Technical Issue, or Account.

Summarization → Generates 1-sentence summaries of customer issues.

Draft Reply Generation → Produces professional, polite responses.

CSV Export → Saves results (support_tickets_with_ai.csv) for further analysis.

🛠 Tools & Skills Demonstrated

Python (pandas, dotenv)

Jupyter Notebook for interactive workflows

OpenAI API integration (secure via .env)

Mock dataset creation for realistic scenarios

Portfolio-ready project structure and documentation

🔑 Running the Notebook (Fake Mode vs Real Mode)

This project supports two execution modes:

✅ Fake Mode (default, no credits required)

Runs without calling the OpenAI API.

Generates mock but realistic outputs so the workflow can be demonstrated by anyone.

Saves a CSV with example categories, summaries, and replies.

⚡ Real Mode (requires OpenAI API key + billing)

Calls the OpenAI API directly for true AI-generated results.

Produces authentic classifications, summaries, and replies.

Toggle between modes:

USE_FAKE_MODE = True   # Fake mode (free, safe for demos)
USE_FAKE_MODE = False  # Real mode (uses your OpenAI credits)

📂 Files in This Repo

support_tickets.csv → Input dataset of mock tickets.

notebook.ipynb → Jupyter Notebook with full pipeline.

support_tickets_with_ai.csv → Output dataset with AI (or mock) results.

.env (local only, not on GitHub) → Stores your API key securely.

🚀 How to Run

Clone this repo

Install dependencies:

pip install openai pandas python-dotenv


Create a .env file with your API key (if using Real Mode):

OPENAI_API_KEY=sk-xxxxxxx


Open the notebook in Jupyter:

jupyter notebook


Run all cells → results are saved to support_tickets_with_ai.csv.

🔮 Future Improvements

Add more ticket categories

Train a fine-tuned classification model

Deploy a simple Streamlit app for interactive demo

Connect to a live database of tickets instead of static CSV

🧠 About This Project

This project is part of a growing portfolio to demonstrate practical AI, analytics, and automation skills for real-world business use cases.
