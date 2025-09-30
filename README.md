# Cloud Data Pipeline

ETL pipeline that fetches weather data from OpenWeatherMap, transforms and cleans it into CSV, loads it into SQLite, and visualizes it with an interactive Streamlit dashboard. Perfect for learning API ingestion, data transformation, and dashboarding in Python.

A pipeline that:
1. Fetches weather data from the OpenWeatherMap API
2. Transforms raw JSON into a clean CSV
3. Loads data into a SQLite database
4. Visualizes results with a Streamlit dashboard

---


## Quickstart

1. **Clone the repo**  
```bash
git clone https://github.com/YOUR-USERNAME/cloud-data-pipeline.git
cd cloud-data-pipeline
pip install -r requirements.txt
setx OPENWEATHER_API_KEY "your_api_key_here"  # Windows
python src/run_pipeline.py
streamlit run src/app/dashboard.py


Features
- Fetch live weather data
- Clean and transform JSON → CSV
- Load data into SQLite
- Interactive dashboard with Streamlit

