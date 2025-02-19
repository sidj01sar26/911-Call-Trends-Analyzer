# 🚨 911 Call Trends Analyzer

## 📌 Project Overview
The **911 Call Trends Analyzer** is a data-driven project aimed at analyzing emergency call data to uncover patterns, trends, and insights into public safety needs. By leveraging real-world data, this project provides valuable insights into when and why people call 911, helping to enhance emergency response strategies.

## 📊 Dataset Details
The dataset used in this project comes from [Kaggle](https://www.kaggle.com/mchirico/montcoalert) and contains emergency call records from Montgomery County. The data includes various features that allow for in-depth analysis of the frequency, reasons, and geographical distribution of 911 calls.

### 📂 Key Features in the Dataset:
- **lat** : Latitude of the call location
- **lng** : Longitude of the call location
- **desc** : Description of the emergency call
- **zip** : Zipcode where the call originated
- **title** : Title indicating the type of emergency
- **timeStamp** : Date and time of the emergency call
- **twp** : Township name
- **addr** : Address of the incident
- **e** : Dummy variable (always 1)

## 🚀 Project Goals
- Identify the **most common reasons** for emergency calls
- Analyze the **geographical distribution** of calls
- Examine **time-based patterns** to determine peak hours and days
- Visualize data trends using **heatmaps and clustering techniques**

## 📌 Key Insights
- **Traffic, Fire, and EMS** are the major categories for emergency calls
- Calls peak during **specific hours and days of the week**
- Certain **townships and zip codes** report significantly more incidents
- Seasonal and monthly variations impact emergency call frequency

## 📊 Visualizations & Analysis
The project employs various visualization techniques to highlight trends and patterns in emergency calls. This includes:
- **Bar charts** to display top zip codes and townships
- **Time series plots** to track call frequency over time
- **Heatmaps** to analyze the distribution of calls across days and hours
- **Clustermaps** to identify correlations between different time periods

## 🛠️ Technologies Used
- **Python** for data processing and analysis
- **Pandas & NumPy** for handling and transforming data
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for exploratory data analysis

## 📅 Time-Based Analysis
By extracting the date, hour, and day of the week from the timestamps, this project identifies significant patterns in emergency call activity. The analysis reveals:
- Higher call volumes on **Fridays and weekends**
- A surge in **traffic-related calls during rush hours**
- Monthly variations in emergency service demand

## 🌍 Geospatial Trends
Mapping the locations of 911 calls provides insights into high-risk areas. This helps authorities deploy resources more effectively and take **preventative measures** to reduce incidents.

## 📈 Future Improvements
- Incorporating **machine learning** for call volume prediction
- Exploring **seasonal patterns** using additional datasets
- Enhancing **interactive dashboards** for real-time monitoring

## 🔗 References
- Dataset: [Kaggle - MontcoAlert](https://www.kaggle.com/mchirico/montcoalert)
- Matplotlib Documentation: [https://matplotlib.org/](https://matplotlib.org/)
- NumPy Documentation: [https://numpy.org/](https://numpy.org/)
- Pandas Documentation: [pandas.pydata.org](https://pandas.pydata.org/)
- Seaborn Documentation: [seaborn.pydata.org](https://seaborn.pydata.org/)
