# WhatsApp-Political-Sentiment-Analysis
WhatsApp Political Narrative Analyzer
Overview
This project is a powerful analytical tool designed to parse WhatsApp chat exports, analyze the content for political sentiment and public opinion, and generate an insightful, interactive dashboard. It is specifically tuned to understand the nuances of "Hinglish" (a mix of Hindi and English) and uses a custom sentiment lexicon to accurately gauge political narratives.

This tool moves beyond simple word counting and provides a deep, data-driven look into the dynamics of group conversations, making it ideal for political analysts, researchers, and campaign managers.

Features
Multi-File Upload: Process multiple WhatsApp chat .zip exports in a single run.

Robust Parsing: Handles various date/time formats and multi-line messages.

Hinglish & Hindi Support: Accurately processes and cleans Hindi (Devanagari) and Hinglish (Romanized Hindi) text.

Custom Political Sentiment: Uses a specialized lexicon (dictionary) to score sentiment based on politically relevant keywords (e.g., 'रोजगार', 'पलायन', 'ब बदलाव'), providing far more accuracy than generic tools.

Topic Modeling: Automatically discovers the main underlying themes and narratives in the conversation.

Interactive Dashboard: Generates a comprehensive dashboard with Plotly, including:

Language Distribution

Political Sentiment Over Time

Top 10 Most Active Users

Hinglish-aware Word Cloud

Weekly Reports: Provides a text-based summary of the most recent week's activity.

How to Use
1. Setup
Create the folder structure:
On your computer, create a main folder called whatsapp-political-analyzer. Inside it, create two more folders: assets and sample_data.

Download and place the files:

Download all the files from this session.

Place analyzer.py, demo.ipynb, requirements.txt, and .gitignore directly inside whatsapp-political-analyzer.

Download the NunitoSans.ttf font (you can find a link in analyzer.py) and place it inside the assets folder.

Install the required libraries:
Open a terminal or command prompt in the whatsapp-political-analyzer folder and run:

pip install -r requirements.txt

2. Prepare Your Data
Chat Files: Place your WhatsApp chat export .zip files inside the sample_data folder.

3. Run the Analysis
The easiest way to run the analysis is by opening and running the demo.ipynb Jupyter Notebook. It provides a step-by-step guide to loading your data and generating the dashboard.

Project Structure
whatsapp-political-analyzer/
├── .gitignore          # Ignores unnecessary files
├── README.md           # You are here
├── requirements.txt    # Project dependencies
├── analyzer.py         # The core analysis class and logic
├── demo.ipynb          # A notebook to demonstrate usage
└── assets/
    └── NunitoSans.ttf  # Font for displaying Hindi in word clouds
