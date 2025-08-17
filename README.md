PhonePe Pulse Data Visualization Project
📌 Overview

The PhonePe Pulse Data Visualization Project is a Streamlit-based interactive dashboard that provides insights into UPI transactions and user adoption trends across India.

PhonePe, a leading digital payments platform, publishes open data on its PhonePe Pulse GitHub. This project extracts, stores, and visualizes that data to help identify:

Transaction behavior across states, quarters, and categories

Regional adoption trends in users and brands

Areas of growth, stagnation, or decline

This dashboard enables data-driven decision-making for financial inclusion, regional campaigns, and product strategies.

⚙️ Tech Stack

Programming Language: Python

Framework: Streamlit

Database: SQLite (phonepe_data.db)

Visualization: Plotly, Pandas

Deployment:

Locally using Streamlit CLI

Google Colab (with ngrok)

Streamlit Cloud

📂 Project Structure
📁 phonepe-pulse-project
│── app.py                 # Streamlit app
│── phonepe_data.db        # SQLite database with aggregated data
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
│── notebooks/             # (Optional) ETL/Exploration notebooks
│── data/                  # (Optional) raw PhonePe JSON files

🚀 Features
🟢 Transactions Dashboard

Filters: State, Year, Quarter, Transaction Type

Metrics:

Total transaction count

Total transaction amount

Average transaction value

Visualizations:

Line chart (trend over quarters)

Pie chart (transaction type share)

Choropleth map (state-wise distribution)

🔵 Users Dashboard

Filters: State, Year, Quarter

Metrics:

Registered users

App opens

Brand adoption percentages

Visualizations:

Choropleth map for state-wise users

Bar chart for top brands

Line chart for adoption trend

🟣 Insurance Dashboard (optional)

Analysis of insurance-related transactions over time

🟡 About Tab

Project description

Data source: PhonePe Pulse GitHub

Business use cases

📊 Business Use Cases

Identify top-performing states & transaction categories

Spot underperforming regions → targeted campaigns

Understand UPI adoption trends

Support strategic decision-making for leadership

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/<your-username>/phonepe-pulse-project.git
cd phonepe-pulse-project

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit app
streamlit run app.py

4️⃣ Access Dashboard

Open the provided localhost URL in your browser.

📦 Dependencies

Create a requirements.txt with:

streamlit
pandas
plotly
sqlite3-binary

📖 Data Source

PhonePe Pulse GitHub Repository: https://github.com/PhonePe/pulse

📜 License

This project is for educational and analytical purposes only.
All data belongs to PhonePe Pulse.

✨ Developed with ❤️ using Python, Streamlit & Plotly.
