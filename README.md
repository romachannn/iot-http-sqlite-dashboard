
# IoT Sensor Data Collection & Visualization

## Project Description
This project demonstrates a simple IoT data pipeline using HTTP communication.
A simulated IoT sensor sends temperature and humidity data to a Flask server.
The data is stored in a SQLite database and visualized using a live Plotly dashboard.

## Architecture
Sensor Simulator → HTTP (Flask API) → SQLite Database → Plotly Dashboard

## Assignment Requirements
- IoT sensor data (temperature & humidity)
- HTTP protocol
- Database storage (SQLite)
- Data visualization (Plotly)
- Dashboard + GitHub + Report

## Endpoints
### GET /health
Checks if server is running.

### POST /ingest
Receives sensor data.

Example JSON:
```json
{
  "device_id": "sim1",
  "temperature": 22.5,
  "humidity": 45.2
}
```

## How to Run in Google Colab
1. Upload the notebook `Assignment2_IoT_HTTP_SQLite.ipynb`
2. Run cells step by step:
   - Install dependencies
   - Start Flask server
   - Run sensor simulator
   - Open dashboard cell
3. Observe live data updates

## Screenshots
See `screenshots/` folder.
