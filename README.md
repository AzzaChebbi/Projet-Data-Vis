# Projet-Data-Vis
Interactive Data Visualization with LLM

Overview

This project provides an interactive data visualization platform using Streamlit and a Large Language Model (LLM) to dynamically generate visualizations based on user queries. 

The goal is to enable users to explore their datasets effortlessly without requiring extensive coding expertise.

🎯 Features

-Upload CSV files and preview the dataset.

-Query in natural language to generate visualizations.

-Automated chart generation using an LLM.

-Preprocessing for better data interpretation.

-Real-time interactivity with an intuitive UI.

-Safe execution of generated code.

# Project Structure

📁 app/

│-- main.py                             # Streamlit app entry point

│-- llm_integration.py                  # Handles LLM queries and visualization generation

│-- helpers.py                          # Statistics functions

│-- .env                                # API keys and configurations (not included in repo)

📜 requirements.txt                     # Dependencies list

# Setup & Installation
git clone [https://github.com/AzzaChebbi/Projet-Data-Vis](https://github.com/AzzaChebbi/Projet-Data-Vis)

python -m venv venv

.\venv\Scripts\activate

pip install -r requirements.txt

create a .env file to add your api key

streamlit run main.py

# Usage Instructions
1️⃣ Upload a CSV file.

2️⃣ Enter a natural language query (e.g., "Show me a bar chart of sales by category").

3️⃣ View the dynamically generated visualization.   

# Future Improvements

Support for multi-modal data (images, text, etc.)

Advanced customization for generated charts

Fine-tuned LLM for better visualization insights
