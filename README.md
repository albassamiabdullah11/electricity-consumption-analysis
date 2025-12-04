# ⚡ Saudi Electricity Consumption Analysis

## 📋 Overview
Comprehensive analysis of electricity consumption patterns in Saudi Arabia, exploring seasonal trends and temperature correlations.

## 🎯 Objectives
- Analyze electricity consumption patterns over 2 years
- Identify peak usage periods and seasonal variations
- Examine temperature-consumption relationship
- Provide actionable insights for energy planning

## 🛠️ Technologies Used
- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Statistical Analysis**

## 📊 Key Findings
1. **Peak Consumption**: Summer months (June-August) show highest consumption
2. **Temperature Correlation**: Strong positive correlation (0.85) between temperature and consumption
3. **Weekly Patterns**: Weekend consumption is 8% higher than weekdays
4. **Average Consumption**: 18,500 MW daily average

## 📈 Visualizations
The project generates 4 comprehensive visualizations:
- Time series analysis of consumption patterns
- Monthly average consumption comparison
- Temperature vs consumption scatter plot with trend line
- Weekday vs weekend consumption analysis

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Analysis
```bash
python electricity_analysis.py
```

### Output
The script generates:
- 4 PNG visualization files
- 1 CSV summary report
- Statistical analysis in console

## 📁 Project Structure
```
electricity-consumption-analysis/
│
├── electricity_analysis.py      # Main analysis script
├── consumption_timeseries.png   # Time series visualization
├── monthly_consumption.png      # Monthly patterns
├── temperature_correlation.png  # Temperature correlation
├── weekday_weekend_comparison.png
├── analysis_summary.csv         # Summary statistics
└── README.md                    # This file
```

## 📝 Data Source
⚠️ **Note**: This project currently uses **synthetic data** generated for demonstration and learning purposes.

### Synthetic Data Generation
- Electricity consumption patterns simulated using NumPy
- Realistic seasonal and weekly variations applied
- Random noise added for authenticity

### Future Enhancements
In a production environment, this would be replaced with:
- Real data from Saudi Electricity Company (SEC)
- Public datasets from ECRA (Electricity & Cogeneration Regulatory Authority)
- Open data from government sources

## 🎓 Skills Demonstrated
Despite using synthetic data, this project demonstrates:
- ✅ Data analysis workflows and methodologies
- ✅ Statistical analysis and correlation studies
- ✅ Professional data visualization
- ✅ Python programming best practices
- ✅ Understanding of domain-specific patterns
- ✅ Clear documentation and reporting

## 🔮 Future Improvements
- [ ] Integrate real SEC data via API
- [ ] Implement predictive models (ARIMA, Prophet)
- [ ] Add regional analysis (Central, Eastern, Western)
- [ ] Create interactive dashboard using Streamlit
- [ ] Add forecasting capabilities
- [ ] Include cost analysis

## 👤 Author
**Abdullah Saad Al-Bassami**
- 🎓 Computer Science Graduate | King Khalid University
- 💼 Aspiring Data Scientist
- 📧 Email: albassamiabdullah11@gmail.com
- 💼 LinkedIn: [linkedin.com/in/abdullah-albassami](https://linkedin.com/in/abdullah-albassami)
- 🐱 GitHub: [github.com/abdullah-albassami](https://github.com/abdullah-albassami)

## 📄 License
This project is licensed under the MIT License - see below for details.

---

**Note**: This is an educational project demonstrating data science skills and techniques.
