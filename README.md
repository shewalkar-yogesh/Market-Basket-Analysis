# 🛒 Market Basket Analysis for Product Recommendation

This project implements Market Basket Analysis using the Apriori algorithm to uncover frequently purchased item combinations. It is aimed at helping retail businesses enhance cross-selling, product bundling, and personalized recommendation strategies.

---

## 🔍 Project Summary

- **Objective:** Identify frequent itemsets and generate association rules from transactional data to suggest product combinations.
- **Business Impact:** Increase average cart value and revenue by leveraging product affinities and consumer purchase patterns.
- **Approach:** Data Preprocessing → Itemset Mining (Apriori) → Rule Generation → Visualization → Insights

---

## 🧰 Tools & Technologies Used

- **Language:** Python  
- **Libraries:** Pandas, mlxtend, Seaborn, Matplotlib  
- **Techniques:** Association Rule Mining, Apriori Algorithm, Support, Confidence, Lift  
- **Other Concepts:** One-hot encoding, Transaction format conversion, EDA

---

## 📊 Key Highlights

- Performed exploratory data analysis to understand item frequency and co-occurrence  
- Converted transactional data into appropriate format for the Apriori algorithm  
- Generated **frequent itemsets** and mined **association rules** using `mlxtend`  
- Calculated support, confidence, and lift to evaluate rule strength  
- Visualized top rules and item pairs using heatmaps and bar plots

---

## 📈 Sample Association Rules Output

| Rule                  | Support | Confidence | Lift  |
|-----------------------|---------|------------|-------|
| {Bread} → {Butter}    | 0.25    | 0.70       | 1.5   |
| {Milk, Bread} → {Eggs}| 0.18    | 0.65       | 1.8   |
| {Diapers} → {Beer}    | 0.20    | 0.60       | 1.6   |

> These rules suggest bundling opportunities and promotions for commonly bought items.

---

## 💡 Business Insights

- Frequently bought-together products identified to inform bundling strategies  
- Suggested product placements to increase cross-sell effectiveness  
- Lift metric helped prioritize rules with meaningful customer behavior signals

---

## 🚀 Future Enhancements

- Add filtering options for high-lift and high-confidence rules  
- Deploy with a Streamlit UI for interactive exploration  
- Integrate with inventory and pricing systems to suggest real-time offers  
- Extend to time-series-based market basket analysis (sequential patterns)

---

## 👤 Author

**Yogesh Shewalkar**  
📧 [yogeshshewalkar02@gmail.com](mailto:yogeshshewalkar02@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/shewalkar-yogesh) | [GitHub](https://github.com/shewalkar-yogesh)

---

## 📄 License

This project is intended for academic and portfolio purposes.  
You are welcome to fork, reference, or build upon it.
