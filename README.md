![Olympic](./Olympics.jpg)
# 🏅 EDA on Olympic Dataset

This project performs an **Exploratory Data Analysis (EDA)** on the Olympic Games dataset to uncover insights, trends, and interesting visualizations related to athletes' performances, participating countries, medal tallies, and historical data over time.

---

## 📂 Dataset

The analysis is based on the [Kaggle Olympic Athletes Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results), which contains detailed records from 1896 to 2016. There are two datasets:

1. `athlete_events.csv`: contains **271116 rows** and **15 columns**. Each row corresponds to an individual athlete competing in an individual Olympic event.
- The columns are:

|        ID         |        Name         |        Sex         |        Age         |        Height         |        Weight         |        Team         |        NOC         |        Games         |        Year         |        Season         |        City         |        Sport         |        Event         |        Medal         |
|-------------------|---------------------|--------------------|--------------------|-----------------------|-----------------------|---------------------|--------------------|----------------------|---------------------|-----------------------|---------------------|----------------------|----------------------|----------------------|
|Unique number for each athlete|Athlete's name|M or F|Integer|In centimeters|In kilograms|Team name|National Olympic Committee 3-letter code|Year and season|Integer|Summer or Winter|Host city|Sport|Event|Gold, Silver, Bronze, or NA| 
|1	|A Dijiang	|M	|24.0	|180.0	|80.0|	China	|CHN|	1992 |Summer	|1992	Summer	|Barcelona	|Basketball	|Basketball Men's Basketball	|NaN|
|2	|Gunnar Nielsen Aaby|	M	|24.0|	NaN	|NaN	|Denmark	|DEN	|1920| Summer	|1920	Summer	|Antwerpen	|Football	|Football Men's Football|	NaN|
|3	|Edgar Lindenau Aabye|	M	|34.0|	NaN|	NaN|	Denmark/Sweden|	DEN	|1900 |Summer|	1900	Summer|	Paris	|Tug-Of-War	|Tug-Of-War Men's Tug-Of-War|	Gold|

<br>

2. `noc_regions.csv`: contains **203 rows** and **3 columns**. Each row consist of NOC Code and the respective region.
- The columns are:
  
|NOC|region|notes|
|----|------|------|
|National Olympic Committee 3-letter code|States|Other information about the region|
|AFG	|Afghanistan	|NaN|
|AHO	|Curacao	|Netherlands Antilles|
|ALB|	Albania|	NaN|

---

## 📊 Features

- Data Cleaning and Preprocessing
- Gender Distribution and Trends
- Top Performing Countries and Sports
- Medal Analysis by Year and Country
- Interactive Visualizations using **Plotly**
- Word Cloud for common sports and events
- Geolocation-based insights using **GeoPy**
- Automated profiling using **ydata_profiling**

## 🛠️ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `wordcloud`, `geopy`
- `ydata_profiling`

## 📸 Sample Visualizations
![Visualization Graphs](./Visualization%20Graphs.png)

## 🔎 Future Work

- Does having a home advantage provide nations a benefit in terms of medals?
- We can additionally include the Paralympics data.
- Does the nation's Olympic accomplishment rely on its wealth (GDP)?
- How do a country's Olympics and climate relate to one another?
- Instead of tallying every individual for a team event we can count it as one medal.

- ## 🧑‍💻 Technologies & Tools Used

[![My Skills](https://skillicons.dev/icons?i=py,vscode)](https://skillicons.dev)
