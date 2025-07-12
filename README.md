# Recommender System for E-Commerce

This project is part of the 45-day internship by YBI Foundation. It implements a simple recommender system using collaborative filtering techniques.

## 📌 Project Features
- User-Item Collaborative Filtering
- Item-Item Collaborative Filtering
- Data visualization using Heatmap
- Similarity score calculation using Cosine Similarity

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (cosine similarity)
- Seaborn and Matplotlib (for data visualization)

## 📂 Dataset
A simulated dataset is used for user-product purchase interaction.

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/madhavan4905/E-commerce-Recommender-system.git
   ```

2. Open the `.ipynb` file using Jupyter Notebook or Google Colab.

3. Run the cells step by step to see the recommendations.

## 🖼️ Sample Output

### Heatmap of User vs Product Interaction
![Heatmap](assets/user_product_heatmap.png)

### User Similarity Matrix (Output Snippet)
```
   1     2     3     4     5     6
1  1.00  0.50  0.87  0.00  0.87  0.50
2  0.50  1.00  0.50  0.50  0.50  0.00
...
```

## 📃 Internship Credit
This notebook was created as a part of an internship project under **YBI Foundation**.

## 📜 License
This project is open-sourced under the [MIT License](LICENSE).