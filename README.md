# 🌍 AirAware: AI-Driven Spatial Super-Resolution AQI Mapping

AirAware is an intelligent GIS air quality platform designed for high-resolution interactive mapping. By marrying automated real-time web extraction with dynamic machine learning downscaling, the application predicts hyper-local Air Quality Index (AQI) values across granular urban micro-grids instead of relying strictly on distant regional telemetry.

# Public App Link:
https://air-aware-hyperlocal-mapping-tinyfish.streamlit.app/

## 🚀 Core Features
* **TinyFish API Automation Layer:** Automated, real-time web searching agent to scrap live CPCB baseline AQI benchmarks from the web.
* **On-the-Fly Scikit-Learn Engine:** Trains an active `RandomForestRegressor` live during the interface script rendering loop based on dynamic user sliders.
* **Granular GIS Plotting Canvas:** Leverages Plotly's modern street-level mapping frameworks mapped to highly refined dark-matter UI presentation components.

## 📦 Local Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   cd air-aware
   ```

2. **Install Required Environment Infrastructure:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Verify the Indian Boundaries Dataset:** Ensure `india_state.geojson` resides securely in the primary project directory root.

4. **Boot Up Frontend Framework:**
   ```bash
   streamlit run app.py
   ```

## 🧠 Technology Stack
* **UI/UX Architecture:** Streamlit Framework (Dark-Theme Core Embeds)
* **Interactive Mapping Engine:** Plotly Graphing Libraries (`go.Scattermap`)
* **AI/ML Infrastructure:** Scikit-Learn Data Processing Suite
* **Mandatory Automation:** TinyFish Python Client SDK
