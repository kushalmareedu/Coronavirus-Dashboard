# COVID-19 Dashboard  

## 📌 Project Overview  

The **COVID-19 Dashboard** is an interactive web-based visualization tool designed to track and analyze the spread of COVID-19 worldwide. The dashboard is implemented using **Jupyter Notebook** and powered by **Voilà**, making it accessible as a standalone web application. It provides real-time insights into **confirmed cases, recoveries, and fatalities** using various data analysis and visualization libraries in Python.  

---

## 🚀 Features  

✅ **Live COVID-19 Data**: Fetches real-time COVID-19 statistics from reliable sources like John Hopkins University.  
✅ **Interactive Dashboard**: Uses **Voilà** to transform Jupyter Notebooks into a web-based UI.  
✅ **Data Visualizations**: Interactive graphs and plots using **Plotly, Seaborn, and Matplotlib**.  
✅ **Geospatial Mapping**: Displays global COVID-19 spread using **Folium**.  
✅ **Country-Specific Analysis**: Compare COVID-19 trends across different countries.  
✅ **Trend Analysis**: Visual representation of confirmed, recovered, and death cases over time.  
✅ **User-Friendly Interface**: Simple, responsive, and easy-to-navigate interface.  

---

## 🛠️ Technologies Used  

- **Python 3.7+**  
- **Jupyter Notebook** (for interactive coding)  
- **Voilà** (to convert notebooks into a web app)  
- **NumPy, Pandas** (data manipulation)  
- **Matplotlib, Seaborn, Plotly** (data visualization)  
- **Folium** (map-based visualization)  
- **IPyWidgets** (interactive UI components)  

---

## 📂 Installation & Setup  

### 🔹 Prerequisites  
Ensure you have **Python 3.7+** and **Jupyter Notebook** installed on your system.  

### 🔹 Install Required Dependencies  

```sh
pip install voila numpy pandas matplotlib seaborn plotly folium ipywidgets
```

🔹 Run the Dashboard

```sh
voila covid_dashboard.ipynb
```
By default, Voilà will serve the notebook as a web application at http://localhost:8866/.

# COVID-19 Dashboard  

## 📊 Data Sources  

The COVID-19 data is sourced from **Johns Hopkins University**:  

- [Confirmed Cases Dataset](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)  
- [Deaths Dataset](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)  
- [Recovered Cases Dataset](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv)  

---

## 📌 Functionalities  

### 1️⃣ Data Processing  
- **Data Cleaning & Formatting**  
- **Summarization of global confirmed, death, and recovered cases**  

### 2️⃣ Data Visualization  
- **Bar Charts**: Top 10 worst-hit countries  
- **Line Graphs**: Trends in confirmed and death cases over time  
- **World Map**: COVID-19 spread visualization using **Folium**  

### 3️⃣ Interactive Features  
- **Country Selection**: View country-wise COVID-19 statistics  
- **Dynamic Graphs**: Adjust the number of displayed countries  


