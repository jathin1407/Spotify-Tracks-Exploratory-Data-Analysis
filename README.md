
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
![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/7fcca6ad-ce75-45f9-b4e5-88c93a3d49d6)  

---

### 🔹 Key Correlation Analyses  

#### 📌 1. **Loudness vs Energy Correlation**  
- Analyzes the relationship between **loudness** and **energy**, showing a strong positive correlation.  

#### 📌 2. **Energy vs Acousticness Correlation**  
- Explores how **energy** and **acousticness** interact, revealing an inverse relationship.  

![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/d6891b87-166a-4dce-a2bc-6497e74ca0b2)  
![Image](https://github.com/user-attachments/assets/e06c6b5c-1a49-4697-acf8-cfdd72b60068) 

---

### 🔹 Duration of Songs Over the Years  
- **Bar and line plots** track how the average **song duration** has changed over time.  
- Helps understand trends in **song length evolution**.  

![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/f52731f2-fe76-48d5-bbe5-2df0f44f0dfe)  
![image](https://github.com/no37no37/spotify_tracks_eda/assets/132648428/c1afae7e-0944-4a28-ba0c-d9ce496bcc81)  

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
