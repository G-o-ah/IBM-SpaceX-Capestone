# Applied Data Science Capstone

This Capstone represents the final (10th) course in the **IBM Data Science Professional Certificate** specialization. It serves as a comprehensive project that integrates and demonstrates the knowledge and skills acquired throughout the program.

---

## Project Background

SpaceX is currently the leading company in the commercial space industry, known for making space travel more cost-effective. The company promotes Falcon 9 rocket launches at a cost of approximately 62 million dollars, compared to over 165 million dollars by other providers. A significant portion of this cost efficiency is attributed to the reusability of the rocket's first stage.

If it is possible to predict whether the first stage will land successfully, the cost of a launch can also be estimated. This project leverages publicly available data and machine learning models to predict the likelihood of SpaceX reusing the first stage.

---

## Research Questions

- How do factors such as payload mass, launch site, number of flights, and orbit type influence the success of the first stage landing?  
- Has the success rate of first stage landings improved over time?  
- Which machine learning algorithm performs best for binary classification in this scenario?

---

## Methodology

### 1. Data Collection
- Data retrieved using the SpaceX REST API  
- Supplementary data obtained via web scraping from Wikipedia

### 2. Data Preparation and Wrangling
- Filtering and cleaning of raw data  
- Handling of missing values  
- One-Hot Encoding applied for categorical variables to enable binary classification

### 3. Exploratory Data Analysis (EDA)
- Performed using SQL queries and visualizations to uncover trends and relationships

### 4. Interactive Visual Analytics
- Geographic and analytical insights visualized through **Folium maps** and **Plotly Dash dashboards**

### 5. Predictive Modeling
- Development, tuning, and evaluation of classification models to identify the most accurate prediction method

---

