# Enhancing the Hospitality Experience for Foreign Guests in South Korean Hotels: Insights from Online Reviews
## 📖 About the Project
This repository contains the code and dataset analysis for the research paper:

**📝 Enhancing the Hospitality Experience for Foreign Guests in South Korean Hotels: Insights from Online Reviews**

This study analyzes 50,175 hotel reviews from TripAdvisor using Text Mining, Sentiment Analysis (VADER), LDA Topic Modeling, and Cluster Analysis to extract insights that can help improve hospitality services for foreign guests in South Korea.

**📖 Presented at the 2023 19th International Conference on Natural Computation, Fuzzy Systems and Knowledge Discovery (ICNC-FSKD).** 
[🔗 Read the Full Paper on IEEE Xplore](url)

## 📌 How this study contributes?
1. Explores the accommodation attributes important to English Speaking Tourists in South Korea
2. Suggestions in the line of targeted marketing including hotel-country groups and the distribution of topics (service attributes) across the countries
3. To provide actionable insights for hotel managers to improve their services and competitiveness.

## 📂 Dataset
Source: TripAdvisor

Total Reviews Scraped: 50,175

Hotels Covered: 240 Best Value Hotels in Seoul (as of March 6, 2023)

Features Extracted: Hotel Name, Reviewer Name, Country, Rating, Date of Stay, Date of Review, Cleaned Review Text

### Significance of this dataset
1. More than 60% of consumers consult online reviews before finalizing their purchase
2. Online Travel Agencies (OTAs): Main source to book accommodation when travelling
3. TripAdvisor- Total number of user reviews and opinions reaching approximately one billion 

## 🔬 Methodology

### Data Collection

Reviews were scraped using Selenium and processed using pandas and geopy.

Non-English characters and irrelevant text were removed.

### Exploratory Data Analysis (EDA)
![Num_Reviews_Yearly](https://github.com/user-attachments/assets/f840abcf-9c2b-4582-a551-dbc697b0b047)

![image](https://github.com/user-attachments/assets/1ffa93a2-e4ad-45ea-b990-8312b26d7ef0)


### Sentiment Analysis

Used VADER Sentiment Analyzer to classify reviews into positive, neutral, and negative sentiments.

Point-biserial correlation was used to compare sentiment scores with review ratings.

### Topic Modeling

Used Latent Dirichlet Allocation (LDA) to extract key themes in reviews.
Optimal number of topics selected using coherence scores.
Key topics identified:

1. Staff Quality and Service
2. Hotel Amenities and View
3. Dealing with Emergencies (Taxi/Shuttle Facility)
4. Luxury Services for Business Travelers
5. Hotel Surroundings & Accessibility
6. Room Service & Check-In/Out Experience

### Cluster Analysis

1. Hierarchical clustering was used to group hotels based on guest preferences.
2. Calculated the percentage of reviews per topic for each hotel and country.
3. Used a correlation matrix to measure similarity in guest preferences.
4. Applied Hierarchical Clustering (Ward’s Method) to group similar hotels & countries.
5. Interpreted clusters to provide actionable insights for the hospitality industry.


## 🎯 Key Findings

Hotels in Myeongdong and Gangnam had higher positive reviews.

Language barriers and staff friendliness significantly impact guest satisfaction.

Airport transportation services emerged as a crucial aspect of guest experience.

9 key hotel service dimensions were extracted using Latent Dirichlet Allocation (LDA).

Hierarchical clustering grouped hotels and countries based on guest preferences.

![image](https://github.com/user-attachments/assets/8c84ce66-fff3-4f12-9219-e9454ec89213)

![image](https://github.com/user-attachments/assets/d844996e-c685-484f-9d5e-2fca5c282806)

## Conclusions
1. Service, Staff, Location, and Breakfast were talked about in most of the reviews.
2. Unique words: “Myeongdong”, and “Gangnam” complimenting the fact that these areas have more foreigners as compared to other places.
3. Most positive reviews had “Clean”, “Friendly”, “Helpful”, “Myeondong”, “Courteous”, “Gangnam”, “Close”, “Convenient”,” Restaurant”, “Floor”,” Spacious”, “Shopping”, “Gym”, etc
4. smell”, “window”, “noise”, “coffee”, “Korean”, “request”, “luggage”, “airport”, “ask”, “problem”, “time”, “taxi”, “speak”, “rude”, etc. appeared in the Negative Sentiment Word Cloud.
5. Sentiment analysis of reviews is a better approach for understanding guests’ mindsets effectively than just ratings. 
6. Topic Modelling gave us 9 dimensions guests care about including Staff Quality and Service; Hotel Amenities and View; Dealing with Emergencies (+Taxi/Shuttle Facility); Luxury Services + Business Trips; Complaints; Hotel Surroundings; Hotel Accessibility; Room Service; and Check In/Out Services. 
7. Cluster analysis will make it possible to make personalized suggestions and provide services to the guests
8. “Hotel Surroundings” was the most representative topic label for 5 clusters out of 9 indicating that hotel surroundings play an important role in defining the perceived image of the hotel

**All Reviews WordCloud**
   
![overall-WC](https://github.com/user-attachments/assets/efed1c62-dd66-43e6-a7ad-e17abcd160d3)

**Top 1000 Negative Reviews WordCloud**

![top1000_negative-WC](https://github.com/user-attachments/assets/4d868c85-930b-46b3-aaaf-efd03d5672e5)

**Top 1000 Positive Reviews WordCloud**

![top1000_positive-WC](https://github.com/user-attachments/assets/06080fd9-9a95-42b7-9f73-eab32026ecb9)


## 🛠 Tech Stack

✅ Python
✅ Jupyter Notebook
✅ Pandas, NumPy – Data Processing
✅ NLTK, VADER – Sentiment Analysis
✅ Gensim, pyLDAvis – Topic Modeling
✅ Scikit-learn, SciPy – Clustering
✅ Matplotlib, Seaborn – Data Visualization

## 🔗 Citation

If you find this research useful, please cite it as follows:

K. Shafi and S. Jin, "Enhancing the Hospitality Experience for Foreign Guests in South Korean Hotels: Insights from Online Reviews," 2023 19th International Conference on Natural Computation, Fuzzy Systems and Knowledge Discovery (ICNC-FSKD), Harbin, China, 2023, pp. 1-6, doi: 10.1109/ICNC-FSKD59587.2023.10280882. 



