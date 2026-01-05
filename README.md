# Olympics Data Analysis Web App 🏅

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![MIT License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

An interactive Exploratory Data Analysis (EDA) dashboard built with **Streamlit** to visualize and analyze over 120 years of Olympic history (from Athens 1896 to Rio 2016).

## 🚀 Live Demo
 [View Live App]([https://your-app-link.streamlit.app/](https://olympics-analysis-web-app-0v23.onrender.com/))

## 📌 Project Overview
The **Olympics Data Analysis Web App** is a data science project that transforms raw historical data into actionable insights. By using interactive visualizations, users can explore how the Olympic Games have evolved, which countries dominate specific sports, and how athlete demographics have changed over a century.

## ✨ Features

### 1. Medal Tally 🥇
- View the total Gold, Silver, and Bronze medals for every country.
- Filter results by specific **Year** and **Country** to see historical performance.

### 2. Overall Analysis 📊
- **Key Metrics:** View total editions, host cities, participating nations, and athletes.
- **Growth Trends:** Interactive line charts showing the increase in participating nations and events over time.
- **Sport Heatmap:** A visualization showing the number of events held in each sport across all Olympic editions.

### 3. Country-wise Analysis 🏳️‍🌈
- **Medal Timeline:** Track a specific country's medal count across the years.
- **Sport Proficiency:** A heatmap showing which sports a country is most successful in.
- **Top Athletes:** A list of the most successful athletes from a chosen country.

### 4. Athlete-wise Analysis 🏃‍♂️
- **Age Distribution:** Probability density plots (KDE) showing the age of medalists across different sports.
- **Height vs. Weight:** Scatter plots correlating physical attributes with medal success.
- **Gender Participation:** A line chart comparing Men vs. Women participation trends.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** [Streamlit](https://streamlit.io/)
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Plotly, Seaborn, Matplotlib

## 📂 Dataset
The project utilizes the **120 years of Olympic history: athletes and results** dataset from Kaggle.
* `athlete_events.csv`: Detailed information on every athlete and their results.
* `noc_regions.csv`: Mapping of National Olympic Committees to country names.

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rudraprasadrout/Olympics_analysis_web_app.git](https://github.com/rudraprasadrout/Olympics_analysis_web_app.git)
   cd Olympics_analysis_web_app
   ```
2. **Create a virtual environment:**

   ```bash
   python -m venv venv

   # Activate on Windows:
   venv\Scripts\activate

   # Activate on Mac/Linux:
   source venv/bin/activate
   ```
3.**Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```
4.**Run the app:**

   ```bash
   streamlit run app.py
   ```
### 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/rudraprasadrout/Olympics_analysis_web_app/issues).

### 📜 License
This project is **MIT** licensed.

---
**Developed by [Rudra Prasad Rout](https://github.com/rudraprasadrout)**
