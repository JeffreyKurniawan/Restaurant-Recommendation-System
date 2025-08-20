# Restaurant Recommendation System 🍽️  

This project builds a **content-based recommendation system** that suggests restaurants similar to a given restaurant by analyzing attributes such as cuisines, cost, type, services, and more. The system leverages **text vectorization (TF-IDF)** and **cosine similarity** to identify relevant alternatives effectively.  

---

## 🔗 Dataset Attributes  

1. **url** – the restaurant’s Zomato URL  
2. **name** – the restaurant’s name  
3. **online_order** – whether the restaurant accepts online orders (yes/no)  
4. **book_table** – whether the restaurant allows table booking (yes/no)  
5. **rate** – overall rating (0–5)  
6. **votes** – number of votes received  
7. **location** – restaurant’s location  
8. **rest_type** – type of restaurant (e.g., Quick Bites, Casual Dining)  
9. **cuisines** – types of cuisines served  
10. **approx_cost (for two people)** – average meal cost for two (₹)  
11. **listed_in(type)** – category of restaurant (delivery, dine-out, etc.)  
12. **sell_beverages** – whether beverages are sold  
13. **sell_chinese_food** – whether Chinese food is offered  
14. **sell_thai_food** – whether Thai food is offered  
15. **sell_indian_food** – whether Indian food is offered  
16. **sell_mediterranean_food** – whether Mediterranean food is offered  
17. **sell_fast_food** – whether fast food is offered  
18. **sell_desserts** – whether desserts are offered  

---

## 🔧 Features  

### Data Preprocessing  
- Encoding categorical features with **OrdinalEncoder** and **OneHotEncoder**  
- Normalization with **MinMaxScaler**  
- Text vectorization of cuisines using **TF-IDF Vectorizer**  

### Recommendation Engine  
- **Cosine Similarity** to measure similarity between restaurants  
- **Content-based filtering** using restaurant attributes and cuisines  
- Custom function to recommend top-N similar restaurants to a given input  

### Visualization & Insights  
- Distribution plots of ratings, cost, and votes  
- Cuisine frequency analysis using Seaborn/Matplotlib  
- Example recommendations for test cases (e.g., similar restaurants to *iSpice Resto Cafe*)  

---

## 🧠 Concepts Used  
- Content-based recommendation systems  
- **TF-IDF Vectorization** for text features (cuisines)  
- **Cosine Similarity** for measuring restaurant similarity  
- Encoding & scaling of categorical and numerical features  
- Exploratory data analysis for customer insights  

---
