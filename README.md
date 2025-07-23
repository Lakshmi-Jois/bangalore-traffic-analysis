🚦 Bengaluru Traffic Analysis Dataset

This dataset contains detailed traffic-related data collected from various intersections in Bengaluru, India. It is intended for analyzing traffic volume, congestion patterns, environmental impact, and related factors across different weather conditions, road activities, and time periods.

---

📁 Dataset Summary

| Column Name              | Description |
|--------------------------|-------------|
| `Date`                   | Date of observation (YYYY-MM-DD) |
| `Time`                   | Time of observation |
| `Traffic Volume`         | Total volume of vehicles recorded |
| `Average Speed`          | Average speed of traffic (km/h) |
| `Congestion Level`       | Measured congestion index (0 to 1 scale) |
| `Travel Time Index`      | Ratio of actual travel time to free-flow travel time |
| `Incident Reports`       | Count of reported traffic incidents |
| `Parking Usage`          | Percentage of parking capacity used |
| `Environmental Impact`   | Calculated environmental burden score |
| `Public Transport Usage` | Number of commuters using public transport |
| `Weather Conditions`     | Categorical: Clear, Rain, Fog, Windy, Overcast |
| `Day Type`               | Categorical: Weekday / Weekend |
| `Roadwork`               | Boolean: True if roadwork/construction activity is present |

---

🧪 Potential Analyses

- Traffic volume variation by **weather** and **day type**
- **Impact of roadwork** on congestion and travel time
- Correlation between **public transport usage** and **traffic volume**
- Hypothesis testing: does **parking usage** affect congestion?
- ANOVA test: impact of **weather conditions** on **incident reports**

---

 🛠️ Tools Recommended

- Python: `pandas`, `plotly`, `scipy`, `statsmodels`, `seaborn`, `matplotlib`
- Visualization: Plotly for interactive plots
- Statistical Tests: T-test, ANOVA, Pearson correlation

---

📌 License

This dataset is provided for educational and research purposes. Please credit the original source when used in publications or projects.
