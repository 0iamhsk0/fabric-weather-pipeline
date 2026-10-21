# fabric-weather-pipeline

Flow

Open-Meteo API → ingestion → raw JSON in ADLS Gen2 → OneLake shortcut → Lakehouse (Bronze → Silver → Gold) → semantic model → Power BI report, with orchestration, monitoring, and Git/deployment wrapped around all of it.
