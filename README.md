# 🌦 ChronoWeather

*ChronoWeather* is a sleek and intelligent weather forecasting web application designed to deliver real-time, location-based weather insights with an engaging user interface.  
It visualizes weather data over time ("Chrono") and adapts dynamically to different weather conditions to provide an immersive experience across web and mobile platforms.

---

## 🖼 Overview
 
ChronoWeather blends modern web technologies with weather intelligence APIs to create a responsive, data-driven app.  
Whether you’re checking today’s temperature, viewing hourly forecasts, or exploring changing conditions in real-time — ChronoWeather keeps you informed in style.

✨ Try it out here - https://chrono-weather-1e00496d.base44.app/

---

## ✨ Key Features

| Feature | Description |
|----------|-------------|
| 🌍 *Live Weather Updates* | Fetches current weather using APIs (like OpenWeatherMap). |
| 🕒 *Chronological Forecasts* | Shows weather trends across hours of the day. |
| 📍 *Auto Location Detection* | Uses device geolocation for instant, local forecasts. |
| 🎨 *Dynamic UI* | Backgrounds and icons change based on live weather conditions. |
| 📱 *Fully Responsive Design* | Works smoothly on phones, tablets, and desktops. |
| 💡 *Minimal Input, Maximum Output* | Clean UI for seamless user experience. |
| ⚡ *Fast & Lightweight* | Built with optimized HTML, CSS, and JavaScript. |
| 🌤 *PWA Ready* | Can be installed as a web app for offline access (optional). |

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/MS-Shamanth/ChronoWeather.git
cd ChronoWeather
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run the Development Server

```bash
npm run dev
```

The app will run at `http://localhost:3000`

---

## 🧩 Project Structure

```
chronoweather/
│
├── public/
│   └── images/           # Icons, weather illustrations
├── src/
│   ├── components/       # UI components
│   ├── pages/            # Main pages (Home, Simulator, Explorer)
│   ├── api/              # NASA + Base44 integration
│   └── utils/            # Data parsing and AI helper functions
├── package.json
└── README.md
```

---

## 🧰 Tech Stack Summary

| Layer         | Technologies                                                             |
| ------------- | ------------------------------------------------------------------------ |
| **Frontend**  | React.js, TailwindCSS, shadcn/ui, Framer Motion, React Leaflet, Recharts |
| **Backend**   | Node.js, Base44 APIs, JSON Schema validation                             |
| **AI/ML**     | Claude AI (InvokeLLM), custom analog matching logic                      |
| **NASA Data** | MERRA-2, SMAP, GPM IMERG, MODIS, AIRS, GES DISC, Worldview               |
| **Hosting**   | Base44 Full-stack deployment                                             |
| **Extras**    | Unsplash API, Geolocation API, Three.js visual layers                    |

---

## 🌐 Usage

1. **Select a Location and Date**
   Enter your city and the future date you want to analyze.

2. **AI Climate Twin Search**
   Claude AI finds your historical analog year using NASA data.

3. **Visual Forecast Dashboard**
   Explore route weather, comfort indices, and probability graphs.

4. **Download Data**
   Export weather subsets as `.csv` or `.json` with full NASA metadata.

---

## 🎯 Impact

ChronoWeather democratizes NASA’s climate data for everyone — from researchers to citizens.
It’s more than a weather tool — it’s a **climate time machine** helping us plan, prepare, and build resilience.

---

## 👩‍🚀 Team & Acknowledgements

Built by the **ChronoWeather Team** for the **NASA Space Apps Challenge 2025**.
Data and API support: [NASA Earthdata](https://earthdata.nasa.gov/)
AI infrastructure: [Base44](https://base44.app)
Visualization framework: React + Leaflet + Three.js

---

**⭐ Predict tomorrow by understanding yesterday.**
**ChronoWeather — Where AI meets NASA’s climate memory.**
