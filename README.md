
# GooglePlay_EDA

This project performs an **Exploratory Data Analysis (EDA)** on the Google Play Store Apps dataset. The goal is to understand the distribution of app ratings, reviews, categories, and other numerical features, using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

## Dataset

- The dataset contains information about apps available on Google Play, including:
  - App Name
  - Category
  - Rating
  - Reviews
  - Size
  - Installs
  - Content Rating
  - Type (Free/Paid)
  - Price
  - Last Updated
  - Genres
  - Current Version
  - Android Version

- Missing values in numerical columns are filled with **mean**, and categorical columns are filled with **mode**.

## Analysis & Visualization

The analysis includes:

1. **Distribution of App Ratings**  
   - Histogram and KDE plot to see how ratings are spread.
2. **Number of Apps per Category**  
   - Count plot to visualize which categories have the most apps.
3. **Rating vs Reviews**  
   - Scatter plot to explore the relationship between ratings and the number of reviews.
4. **App Size vs Rating**  
   - Scatter plot to see if app size affects user rating.
5. **Correlation Heatmap**  
   - Shows correlation between numerical features like Rating, Reviews, Installs, and Size.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/YourUsername/GooglePlay_EDA.git
