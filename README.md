# Market Basket Analysis Using Association Rule Mining

Market Basket Analysis is a data mining technique used to discover relationships between items frequently purchased together. This project demonstrates the implementation of three popular association rule mining algorithms:

- 🔹 Apriori Algorithm
- 🔹 ECLAT Algorithm
- 🔹 FP-Growth Algorithm

The objective is to identify frequent itemsets and generate meaningful association rules that can help businesses improve product placement, cross-selling strategies, and customer recommendations.

---

## 📂 Project Structure

```bash
Market-Basket-Analysis-using-Association-rule-Mining/
│
├── Market_Basket_Analysis_using_Apriori_Algorithm.ipynb
├── Market_basket_analysis_using_Eclat_Algorithm.ipynb
├── Market_basket_analysis_using_F_P_Growth.ipynb
└── README.md
```

---

## 🚀 Algorithms Implemented

### 1️⃣ Apriori Algorithm
Apriori is one of the most widely used algorithms for mining frequent itemsets and generating association rules.

**Key Features:**
- Uses support-based pruning
- Generates candidate itemsets iteratively
- Suitable for small to medium-sized datasets

---

### 2️⃣ ECLAT Algorithm
ECLAT (Equivalence Class Clustering and Bottom-Up Lattice Traversal) uses a depth-first search strategy to find frequent itemsets efficiently.

**Key Features:**
- Faster than Apriori for dense datasets
- Uses transaction ID (TID) sets
- Reduces database scans

---

### 3️⃣ FP-Growth Algorithm
FP-Growth (Frequent Pattern Growth) avoids candidate generation by constructing an FP-Tree.

**Key Features:**
- High efficiency for large datasets
- Reduced computational complexity
- Faster frequent pattern mining

---

## 📊 Technologies Used

- Python 🐍
- Jupyter Notebook
- Pandas
- NumPy
- Mlxtend
- Matplotlib
- Seaborn

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Market-Basket-Analysis-using-Association-rule-Mining.git
```

Navigate to the project directory:

```bash
cd Market-Basket-Analysis-using-Association-rule-Mining
```

Install the required dependencies:

```bash
pip install pandas numpy mlxtend matplotlib seaborn
```

---

## ▶️ How to Run

1. Open Jupyter Notebook:

```bash
jupyter notebook
```

2. Run any of the notebooks:
   - Apriori Notebook
   - ECLAT Notebook
   - FP-Growth Notebook

3. Analyze:
   - Frequent Itemsets
   - Support Values
   - Confidence Scores
   - Lift Metrics
   - Association Rules

---

## 📈 Evaluation Metrics

The generated association rules are evaluated using:

| Metric | Description |
|----------|------------|
| Support | Frequency of occurrence of an itemset |
| Confidence | Probability that item B is purchased when item A is purchased |
| Lift | Strength of association between items |
| Conviction | Measure of implication strength |

---

## 💡 Applications

- Product Recommendation Systems
- Retail Store Analysis
- Customer Purchase Behavior Analysis
- Cross-Selling & Up-Selling
- Inventory Management
- E-commerce Analytics

---

## 🎯 Learning Outcomes

By completing this project, you will understand:

- Association Rule Mining concepts
- Frequent Itemset Generation
- Apriori Algorithm implementation
- ECLAT Algorithm implementation
- FP-Growth Algorithm implementation
- Evaluation of association rules using Support, Confidence, and Lift

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author

**Anshif**

If you found this project useful, consider giving it a ⭐ on GitHub!
