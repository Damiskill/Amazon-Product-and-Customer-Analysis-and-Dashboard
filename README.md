[![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)]()
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Analytics-blue?style=flat-square)]()
[![Dashboard](https://img.shields.io/badge/Dashboard-Visualization-orange?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)]()
[![Made with ❤️ by Damiskill](https://img.shields.io/badge/Made%20with-❤️%20by%20Damiskill-critical?style=flat-square)]()


## 📘 Project Overview  

![Excel Dashboard Preview](https://github.com/yourusername/Amazon-Excel-Dashboard/blob/main/dashboard_preview.png)

**Tool Used:** Microsoft Excel (Pivot Tables, Calculated Columns, and Dashboards)  

This project analyzes **Amazon product and customer review data** to generate insights that can help sellers optimize pricing, marketing, and customer satisfaction.  
The dashboard summarizes discounts, ratings, revenue potential, and product performance across multiple categories.

## 🧾 Dataset Description  

The dataset was scraped from Amazon product pages and contains **1,465 records** and **16 fields**, including:

- 🏷️ **Product details:** Name, Category, Price, Discount, and Ratings  
- 🧍 **Customer engagement:** Review titles, content, and counts  
- 📦 **Each record** represents one unique product with aggregated reviewer information.


## 🎯 Analysis Objectives  

The following questions guided the analysis:

1. What is the average discount percentage by product category?  
2. How many products are listed under each category?  
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings?  
5. What is the average actual price vs. discounted price by category?  
6. Which products have the highest number of reviews?  
7. How many products have a discount of 50% or more?  
8. What is the distribution of product ratings?  
9. What is the total potential revenue by category?  
10. How many unique products fall into each price range bucket?  
11. How does rating relate to discount levels?  
12. How many products have fewer than 1,000 reviews?  
13. Which categories have the highest discount totals?  
14. Identify the top 5 products in terms of ratings and reviews combined.  


## 📊 Key Findings & Insights  

### 1️⃣ Average Discount Percentage by Product Category  

| Product Category | Average Discount |
|------------------|------------------|
| Home Improvement | **57.5%** |
| Computers & Accessories | 53.2% |
| Health & Personal Care | 53.0% |
| Electronics | 49.9% |
| Musical Instruments | 46.0% |
| Home & Kitchen | 40.1% |
| Car & Motorbike | 42.0% |
| Office Products | 12.4% |
| Toys & Games | 0.0% |
| **Overall Average** | **46.7%** |

💡 **Insight:** Home Improvement and Computer Accessories have the most aggressive discount strategies, suggesting strong price competition.


### 2️⃣ Product Distribution by Category  

| Category | Product Count |
|-----------|----------------|
| Electronics | 490 |
| Home & Kitchen | 448 |
| Computers & Accessories | 375 |
| Office Products | 31 |
| Others (combined) | 7 |
| **Total** | **1,351** |

💡 **Insight:** Electronics dominate the dataset, making up ~36% of all listed products.


### 3️⃣ Total Reviews by Category  

| Category | Total Reviews |
|-----------|----------------|
| Electronics | 490 |
| Home & Kitchen | 448 |
| Computers & Accessories | 375 |
| Office Products | 31 |
| **Total** | **1,351** |

💡 **Insight:** Customer engagement aligns closely with product volume, with Electronics and Home & Kitchen leading.


### 4️⃣ Highest Rated Products  

| Product | Rating |
|----------|---------|
| Syncwire LTG to USB Cable | ⭐ 5.0 |
| REDTECH USB-C to Lightning Cable | ⭐ 5.0 |
| Amazon Basics Wireless Mouse | ⭐ 5.0 |

💡 **Insight:** High-rated products are mostly low-cost accessories with consistent user satisfaction.


### 5️⃣ Average Actual vs. Discounted Price by Category  

| Category | Avg. Actual Price | Avg. Discounted Price |
|-----------|------------------|------------------------|
| Electronics | ₹10,418 | ₹6,226 |
| Home & Kitchen | ₹4,162 | ₹2,331 |
| Computers & Accessories | ₹1,858 | ₹947 |
| Health & Personal Care | ₹1,900 | ₹899 |
| **Overall** | ₹5,691 | ₹3,305 |

💡 **Insight:** Electronics remain the highest-value items, even after discounts.


### 6️⃣ Top Reviewed Product  

- **Fire-Boltt Ninja Call Pro Plus Smart Watch** — ⏱️ **5 reviews**  
💡 Indicates the brand’s popularity and strong visibility within its category.


### 7️⃣ Discount Bucket Distribution  

| Discount Range | Product Count |
|----------------|----------------|
| <50% | 689 |
| ≥50% | 662 |

💡 **Insight:** Discounts are nearly evenly split across the dataset, showing competitive pricing.


### 8️⃣ Product Rating Distribution  

![Ratings Distribution](https://github.com/yourusername/Amazon-Excel-Dashboard/blob/main/ratings_distribution.png)

| Rating | Count |
|--------|--------|
| 4.1 | 225 |
| 4.3 | 209 |
| 4.2 | 207 |
| 4.0 | 159 |
| 3.9 | 114 |
| ... | ... |

💡 **Insight:** Most products fall within the **4.0–4.3 rating range**, indicating generally positive customer feedback.


### 9️⃣ Total Potential Revenue by Category  

| Category | Revenue |
|-----------|----------|
| Electronics | ₹91.3B |
| Computers & Accessories | ₹11.6B |
| Home & Kitchen | ₹10.4B |
| Others | <₹0.5B |
| **Total** | **₹113.6B** |

💡 **Insight:** Electronics dominate potential revenue, highlighting their importance to Amazon’s product ecosystem.


### 🔟 Price Range Distribution  

| Price Range | Product Count |
|--------------|----------------|
| < ₹200 | 159 |
| ₹200–₹500 | 342 |
| > ₹500 | 850 |

💡 **Insight:** Most Amazon products are priced above ₹500, targeting mid-to-premium buyers.


### 11️⃣ Rating vs Discount  

| Discount Bucket | Avg. Rating |
|-----------------|---------------|
| 0–10% | 4.2 |
| 81–90% | 3.9 |
| 91–100% | 4.2 |

💡 **Insight:** Extremely high discounts (81–90%) do not always lead to higher satisfaction — a sign of perceived quality issues.


### 12️⃣ Products with <1,000 Reviews  

| Review Range | Count |
|---------------|--------|
| < 1,000 | 310 |
| > 1,000 | 1,041 |

💡 **Insight:** Over 75% of products are well-reviewed, reflecting Amazon’s massive engagement base.


### 13️⃣ Categories with Highest Discounts  

| Category | Share of Total Discount |
|-----------|-------------------------|
| Electronics | 38.8% |
| Computers & Accessories | 31.6% |
| Home & Kitchen | 28.5% |

💡 **Insight:** These three categories make up **over 98%** of all discount activity.


### 14️⃣ Top 5 Combined Rated Products  

| Product | Combined Rating |
|----------|-----------------|
| Amazon Basics HDMI Cable (6ft) | 431 |
| Amazon Basics HDMI Cable (6ft, 2-Pack) | 431 |
| AmazonBasics Premium HDMI Cable (3ft) | 431 |
| boAt Bassheads 100 (Pink) | 368 |
| boAt Bassheads 100 (Red) | 368 |

💡 **Insight:** Amazon Basics and boAt brands dominate in customer satisfaction and engagement.


## 📈 Dashboard Snapshot  

> Below is a preview of the interactive Excel Dashboard summarizing the above findings:

![Amazon Excel Dashboard](https://github.com/yourusername/Amazon-Excel-Dashboard/blob/main/amazon_dashboard.png)


## 🧰 Tools & Skills Used  

- Microsoft Excel (Pivot Tables, Charts, Calculated Fields, Dashboard Design)  
- Data Cleaning & Transformation  
- E-commerce Performance Analysis  
- Data Visualization & Storytelling  


## 💡 Key Takeaways

* Electronics drive the highest sales and engagement.
* Discounts are heavily concentrated in tech-related categories.
* Ratings remain strong despite deep discounting, reflecting customer trust.
* Excel’s built-in analytics tools are powerful enough for meaningful e-commerce insights.


## 🧠 Lessons Learned

> This project improved my proficiency in:

* Data cleaning and transformation in Excel
* Creating interactive dashboards with slicers and visuals
* Deriving insights from structured e-commerce datasets


## 📬 Connect with Me

👤 **Emmanuel Philip (Damiskill)**
📧 [e-mail](mailto:emmanuelphilip685d@gmail.com)
🌐 [LinkedIn Profile](https://linkedin.com/in/PhilipEmmanuel)
📊 [GitHub Portfolio](https://github.com/Damiskill)


⭐ **If you found this project helpful, please consider giving it a star on GitHub!**
