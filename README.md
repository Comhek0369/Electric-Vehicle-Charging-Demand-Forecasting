# ⚡ Electric Vehicle Charging Demand Forecasting (Power BI Dashboard)

This repository contains a Power BI dashboard project designed to forecast and visualize **Electric Vehicle (EV) charging demand** using data-driven insights. The dashboard is equipped with interactive slicers and visualizations to support informed decisions in urban planning, energy infrastructure, and sustainability efforts.

Dashboard Template :-<a href= "https://github.com/Comhek0369/Electric-Vehicle-Charging-Demand-Forecasting/blob/main/EV%20charging%20stations.pbix">Power BI Template </a>

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `EV charging stations.pbix` | Power BI dashboard project file |
| `Screenshot (340).png` | Final dashboard overview |
| Development CSV. files | Visual evolution and filter setup |

---

## 🎯 Objective

Forecast EV charging demand based on:
- **Day of the week**
- **Weather conditions (Humidity, Temperature)**
- **Traffic volume**

The goal is to provide actionable insights for optimizing EV infrastructure and grid demand management.

---

## 📊 Dashboard Features

### 🔎 Slicers (Interactive Filters)

- **Day Of Week**: Filter demand by specific weekday.
- **Humidity**: Range slider for filtering based on humidity levels.
- **Day Type**: Weekday vs Weekend comparison.
- **Traffic Volume**: Range slider (if data cleaned/interpolated).

### 📈 Visualizations

| Visualization | Description |
|---------------|-------------|
| **Forecast Demand in a Week** | Bar chart comparing demand across weekdays. |
| **EV Charging Stations Map** | Geospatial view of station distribution. |
| **Forecast vs Actual Demand (Traffic Volume)** | Demand segmented by traffic and weekday. |
| **Weekly Demand Table** | Matrix summary with weekday/weekend split. |

---

## 🌐 Data Sources

Dataset: `tableau_ready_ev_forecast`

Includes:
- `ForecastDemand`
- `DayOfWeek`, `DayType`, `Hour`
- Weather metrics: `Humidity`, `Temperature`, `WindSpeed`
- `TrafficVolume`

---

## 🛠 Tools & Technologies

- [Power BI Desktop](https://powerbi.microsoft.com/)
- DAX for calculated columns/measures
- Power Query for ETL
- Geospatial mapping with Bing Maps
- Custom visuals and slicers

---

## 🚀 Getting Started

1. Clone or download the repo.
2. Open `EV charging stations.pbix` in **Power BI Desktop**.
3. Explore the dashboard with interactive slicers.
4. Analyze demand patterns for EV charging infrastructure planning.

---

## 📷 Preview
-<a href= "https://github.com/Comhek0369/Electric-Vehicle-Charging-Demand-Forecasting/commit/242ef8fb30450047bb5a5901c41117a9895f2e3c">Screenshort</a>
### Final Dashboard Overview

Dashboard in PDF:-<a href= "https://github.com/Comhek0369/Electric-Vehicle-Charging-Demand-Forecasting/blob/main/EV%20charging%20stations.pdf"> PDF</a>

---

## 📌 Key Insights

- **Highest demand** on Tuesdays and Mondays.
- **Humidity and traffic volume** influence EV charging patterns.
- Visual and data-driven planning tool for smart mobility infrastructure.

---

## 🧠 Potential Enhancements

- Integrate real-time traffic/weather APIs.
- Extend filters for other environmental metrics.
- Add predictive models via Python or Azure ML.
- Embed dashboard in web apps with Power BI Embedded.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a new branch, and submit a pull request for any improvements, bug fixes, or feature additions.

---

## 📬 Contact

Feel free to open an issue for feedback or questions.

---

*Made with 💡 using Power BI to power smarter mobility.*

