#  Google Play Store Data Analysis

This project involves analyzing and visualizing Google Play Store data to uncover patterns, trends, and user sentiments. Using data analytics and visualization techniques, we aim to derive meaningful insights into app performance, user preferences, and market dynamics.

## Dataset

- **apps.csv**: Contains app metadata such as name, category, rating, installs, type, price, etc.
- **user_reviews.csv**: Includes user sentiment reviews and polarity information.

## 📌 Objectives

1. Clean and preprocess raw data for consistency and accuracy.
2. Explore app distribution across categories.
3. Analyze app ratings, reviews, install counts, and pricing.
4. Perform sentiment analysis based on user reviews.
5. Visualize key insights using Matplotlib, Seaborn, and Plotly.

## 📊 Exploratory Data Analysis & Insights

### 1. App Distribution Across Categories
- The `Family`, `Game`, and `Tools` categories dominate the Play Store.
- Niche categories like `Beauty`, `Events`, and `Parenting` are underrepresented.

### 2. App Price vs Rating
- Most apps are free and receive high ratings (4.0–4.8).
- Expensive apps (up to $400) do not necessarily have better ratings, indicating pricing does not equate to higher user satisfaction.

### 3. User Sentiment Distribution
- **Positive reviews** are the most frequent, showing high satisfaction.
- **Negative reviews** exist in a significant number, pointing to improvement areas.
- **Neutral reviews** are the least common, suggesting users tend to express strong opinions.

### 4. Sentiment Distribution by Category

- **Games** category has the highest number of total reviews, especially with a dominant count of **positive sentiments**, indicating strong user engagement and satisfaction.
- **Health and Fitness**, **Communication**, and **Social** apps also show a significant number of **positive reviews**, reflecting good user experience.
- **Books & Reference**, **Medical**, and **Weather** have lower review volumes, suggesting less user interaction or niche usage.
- Categories like **Finance** and **Dating** have visible **negative sentiment**, possibly pointing to usability issues or unmet user expectations.

#### 5.App Ratings by Category

- Most app categories show an average rating between **3.5 to 4.5**, indicating general user satisfaction.
- Categories such as **Libraries and Demo**, **Comics**, and **Events** have consistently **high ratings**, suggesting strong performance in smaller user groups.
- Categories like **Medical** and **Dating** display wide **rating variation**, indicating inconsistency in app quality or diverse user expectations.
