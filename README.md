
# 🎵 Spotify Tracks Exploratory Data Analysis  

## 📌 Introduction  
The **Spotify Tracks Analysis** project explores and visualizes a dataset containing information about various **Spotify tracks**. The primary goal is to gain insights into song characteristics, identify patterns, and analyze feature correlations. The analysis is conducted using **Python** and popular data analysis libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**.  

---

## 📂 Data Loading and Cleaning  
The dataset, stored in a **CSV file**, includes information such as:  
- **Track ID, Name, Popularity, Duration, Artists, Release Date, and Musical Features**  

To ensure **data quality**, missing values are identified using `pd.isnull()` and `info()`. The **duration**, originally in milliseconds, is converted to **seconds** for better interpretation, and the **"duration_ms"** column is removed.  

---

## 📊 Exploratory Data Analysis  

### 🔹 1. 10 Least Popular Songs  
- Identifies and displays the **10 least popular** songs in the dataset.  
- Sorted by **popularity** in ascending order.  

### 🔹 2. 10 Most Popular Songs (Popularity > 90)  
- Showcases the **10 most popular** songs with a **popularity score greater than 90**.  

### 🔹 3. Most Popular Artist  
- Identifies the **most popular artist** based on overall **track popularity**.  

### 🔹 4. Top 10 Songs by the Most Popular Artist  
- Lists the **top 10 tracks** by the artist with the highest average popularity.  

### 🔹 5. Most Danceable Songs  
- Identifies **songs with the highest danceability scores**.  
- Highlights tracks that are considered the best for dancing.  

---

## 📈 Visualization  

### 🔹 Correlation Heatmap  
A **correlation heatmap** visualizes relationships between numerical variables. It helps identify strong correlations between features.  
![Image](https://github.com/user-attachments/assets/22f3836d-6c1b-4b30-a641-2994092ef015) 

---

### 🔹 Key Correlation Analyses  

#### 📌 1. **Loudness vs Energy Correlation**  
- Analyzes the relationship between **loudness** and **energy**, showing a strong positive correlation.  

#### 📌 2. **Energy vs Acousticness Correlation**  
- Explores how **energy** and **acousticness** interact, revealing an inverse relationship.  

![Image](https://github.com/user-attachments/assets/b9e363eb-e00f-4570-847a-ef34ad420981)
![Image](https://github.com/user-attachments/assets/e06c6b5c-1a49-4697-acf8-cfdd72b60068) 

---

### 🔹 Duration of Songs Over the Years  
- **Bar plot** to track how the average **song duration** has changed over time.  
- Helps understand trends in **song length evolution**.  

![Image](https://github.com/user-attachments/assets/8b49df0b-5fd5-43c3-938d-80ab0738ac21)

---

## 🎯 Conclusion  
The **Spotify Tracks Analysis** project provides **valuable insights** into song characteristics, trends, and correlations. Through **exploratory data analysis and visualizations**, we gain a deeper understanding of:  
✅ Popularity distribution of tracks and artists  
✅ Danceability trends in music  
✅ Feature correlations like **Energy vs Acousticness** and **Loudness vs Energy**  
✅ The evolution of song duration over the years  

This project **enhances our understanding of music trends** and can be further extended for **predictive modeling** or **music recommendation systems**.  

---

⭐ **If you found this project insightful, don't forget to star the repository!** ⭐  
