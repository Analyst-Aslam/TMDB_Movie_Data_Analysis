# TMDB_Movie_Data_Analysis

##  Project Overview  
This project analyzes data of **top-rated movies** retrieved from **The Movie Database (TMDB) API**. It explores trends in **popularity and release patterns** to gain insights into the movie industry.  

##  Dataset Description  
The dataset contains key details about top-rated movies, including:  

-  **title** 
-  **release_date**  
-  **overview** (Short movie description)  
-  **popularity** 
-  **vote count**
-  **vote_average**

##  Analysis Conducted
### **1️ Data Cleaning & Preprocessing**
- Converted and formatted date values for time-based analysis.
- Removed Null values for effective analysis.

### **2️ Exploratory Data Analysis AND Visualization**
- Examined the latest and earliest year.
- Classified the movies into Year range.
- Created a **bar graph** to visualize the distribution of top-rated movies across different year ranges.
- Found the **Top 5** popular movies from the dataset for every decade.
- Understood how the the popularity changes over time.

##  Key Insights

###  Increase in Top-Rated Movies Over Time  
- The number of top-rated movies has **steadily increased since the 1970s**, with a **peak in the 2010-2019** decade (**2,939 movies**).  
- The decline after 2020 is because the data only goes up to **early 2025**.
###  Popularity Trends Among Top-Rated Movies  
- **Older classics (pre-2000) have lower popularity** compared to modern movies, suggesting that **newer movies dominate audience engagement**.  
- **Movies from 2020 onward show a massive spike in popularity**, indicating that recent top-rated movies receive more attention, likely due to:  
  -  **Streaming services (Netflix, Disney+, Prime Video, etc.)**  
  -  **Social media influence (TikTok, Twitter, YouTube, etc.)**  
###  Most Popular Top-Rated Movies by Era  
### Shift in Audience Preferences  
- **Modern top-rated movies gain significantly more popularity than older classics.**  
- Audience engagement is now driven by:  
  -  **Accessibility** (*streaming platforms*)  
  -  **Marketing strategies** (*social media, trailers, online discussions*)  


##  Technologies Used
- **Python** (pandas, seaborn, matplotlib)
- **Jupyter Notebook** for analysis and visualization
- **Seaborn & Matplotlib** for data visualization

##  How to Run the Project
### **1️ Install Required Libraries**
```bash
pip install pandas numpy matplotlib seaborn
```
### **2️ Open Jupyter Notebook**
```bash
jupyter notebook
```
### **3️ Run the Notebook**
Download the Dataset.
Change the Dataset directory to the location of the dataset.
Execute each cell sequentially to load the dataset and perform the analysis.

##  Conclusion
This analysis provides valuable insights into trends in popularity and release patterns within the movie industry. 
