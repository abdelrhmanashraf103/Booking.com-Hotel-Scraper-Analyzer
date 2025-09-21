# 🏨 Booking.com Hotel Scraper & Analyzer

## 📌 About the Project
This project is a **web scraping + data analysis pipeline** built with **Python, Selenium, Pandas, and Matplotlib**.  
It allows you to extract **hotel data from Booking.com** (name, location, price, rating, reviews, link), store it in a CSV file, and then perform **statistical analysis & visualization**.

---

## 🎯 Problem
When planning a trip, it's often difficult to:
- Compare hotel prices across multiple listings.
- Identify which hotels have the **best value for money** (good rating vs low price).
- Visualize trends (price distribution, top-rated hotels, etc.).

---

## 💡 Solution
This project solves the problem by:
1. Scraping hotel data from Booking.com using **Selenium**.
2. Cleaning and structuring the data with **Pandas**.
3. Generating **visual insights** using **Matplotlib**:
   - Price distribution histogram 📊
   - Rating distribution histogram ⭐
   - Price vs Rating scatter plot 💰➡️⭐
   - Top 10 hotels by rating 🏆

---

## ⚙️ How It Works
1. User provides:
   - Booking.com search **URL**
   - Output **CSV file name**
2. Script runs Selenium to scrape hotel details.
3. Data is saved in a structured CSV format.
4. Pandas cleans the data.
5. Matplotlib visualizes key insights.

---

## 📊 Example Visualizations
### 🔹 Price Distribution
![Price Distribution](hotel_analysis.png)

### 🔹 Top 10 Hotels by Rating
*(Bar chart of the highest-rated hotels with their names)*

---

## 🚀 Tech Stack
- **Python **
- **Selenium** – Web scraping
- **Pandas** – Data cleaning & analysis
- **Matplotlib** – Data visualization

---

## 🏆 Key Insights (Sample Run)
- Average hotel price: **$120/night**
- Average rating: **8.5/10**
- Best Value: Small boutique hotels often score higher than luxury ones for the same price.

---

## 📌 Future Improvements
- Integrate **Seaborn/Plotly** for more interactive dashboards.
- Automate scraping across multiple cities.
- Deploy as a **Flask/Django web app**.
- Store results in a **database** (MySQL/PostgreSQL).

---

## 👨‍💻 Author
Developed by **[ِAbdelrhman Haroun](https://www.linkedin.com/in/abdelrhman-ashraf-455aa930a)**  
👉 If you like this project, give it a ⭐ on GitHub!
