# British Airways Data Science Forage Program – Task 1 & Task 2

This repository contains my solutions to both tasks in the **British Airways Data Science Forage program**, designed to simulate real-world data science challenges at a major airline.

- **Task 1**: Scraping and analyzing customer reviews from Skytrax
- **Task 2**: Building a predictive model to determine whether a customer completes their flight booking

---

## 🎯 Objectives

### ✅ Task 1: Customer Feedback Analysis
The goal was to:
- Scrape customer reviews from [Skytrax](https://www.airlinequality.com/ )
- Clean and analyze the text data using NLP techniques
- Visualize sentiment trends, frequent words, and topics
- Summarize findings into a single PowerPoint slide

### ✅ Task 2: Predictive Modeling of Customer Bookings
The goal was to:
- Explore and prepare customer booking data
- Train a machine learning model to predict if a customer completes a booking
- Evaluate performance using metrics like accuracy, precision, recall, and ROC AUC
- Visualize feature importance
- Present findings in a single PowerPoint slide

---

## 🧰 Tools & Technologies Used

| Tool/Technology | Purpose |
|------------------|---------|
| Python           | Web scraping, NLP, ML modeling |
| Requests / BeautifulSoup | Scraping Skytrax reviews |
| Pandas           | Data manipulation |
| TextBlob / VADER | Sentiment analysis |
| WordCloud        | Visualizing frequent words |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn     | Machine Learning |
| Random Forest    | Model training and feature importance |
| Jupyter Notebook / Google Colab | Interactive development |
| python-pptx      | Automated PowerPoint creation |

---


---

## 📊 Key Insights

### ✅ Task 1: Customer Feedback
- High overall sentiment scores indicate general customer satisfaction.
- Frequent positive mentions: "friendly crew", "good service".
- Common complaints: flight delays, food quality, seating comfort.
- Wordclouds and sentiment distributions highlight key themes.

### ✅ Task 2: Booking Prediction
- Trained a Random Forest classifier with ~90% accuracy.
- Top predictors:
  - `purchase_lead` (how early the customer booked)
  - `wants_extra_baggage`
  - `wants_in_flight_meals`
- Customers who added extra services were more likely to complete bookings.
- ROC AUC score of ~0.89 shows strong predictive power.

---

## 🖼️ Visualizations Included

### Task 1
- Sentiment distribution histogram
- Wordcloud of most frequent words
- Review length distribution
- Top positive/negative words

### Task 2
- Feature importance bar chart
- Confusion matrix heatmap
- ROC curve (optional)

---

## 📝 How to Run

### Step 1: Clone the repo
```bash
git clone https://github.com/your-username/british-airways-forage.git 
cd british-airways-forage

```
---
### Step 2: Install dependencies
```bash
pip install requests beautifulsoup4 pandas textblob wordcloud matplotlib scikit-learn seaborn python-pptx
```
### Step 3: Run the notebooks
Open either:

- notebooks/scrape_and_analyze_reviews.ipynb (for Task 1)
- notebooks/booking_model.ipynb (for Task 2)
Run all cells to reproduce results and generate visuals and summary slides.

📬 Contact
If you have any questions or want to collaborate on similar tasks, feel free to reach out!

Gmail: fouziaashfaq0298@gmail.com
