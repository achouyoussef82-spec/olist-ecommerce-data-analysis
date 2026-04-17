# 📊 E-Commerce Business Performance Analysis (Olist Dataset)

## 📌 Project Overview
This project provides a comprehensive analysis of the Brazilian E-Commerce public dataset by **Olist**. 
The goal is to analyze sales performance, identify seasonal trends, and evaluate customer satisfaction to provide actionable business insights.

---

## 🛠️ Methodology (CRISP-DM)
This project follows the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework:
1.  **Business Understanding**: Focus on sales volume and growth drivers.
2.  **Data Understanding**: Exploration of a relational database (9 tables).
3.  **Data Preparation**: Merging datasets, handling missing values, and datetime formatting.
4.  **Exploratory Data Analysis (EDA)**: Temporal analysis, Pareto distribution, and satisfaction mapping.

---

## 🔑 Key Business Questions
- What is the monthly sales trend?
- Which product categories dominate the volume of sales?
- Is there a correlation between delivery time and customer satisfaction scores?

---

## 🚀 Technical Stack
- **Language**: Python 3.x
- **Libraries**: 
  - `Pandas`: Data manipulation and cleaning.
  - `Matplotlib` & `Seaborn`: Advanced data visualization.
- **Environment**: Kaggle / Jupyter Notebook.

---

## 📈 Key Insights
- **Seasonality**: A massive spike in sales is observed every November due to **Black Friday** in Brazil.
- **Top Categories**: 20% of product categories (Bed_Bath_Table, Health_Beauty) account for nearly 50% of total sales volume.
- **Customer Satisfaction**: Late deliveries are the #1 driver for review scores below 3 stars.

---

## 📂 Project Structure
```text
├── data/                   # (Optional) Link to Kaggle dataset
├── notebooks/
│   └── olist_analysis.ipynb # Main analysis notebook
├── output/
│   └── visualizations/     # Exported charts
└── README.md               # Project documentation

C'est la touche finale qui transforme un simple exercice en un atout de recrutement. Un recruteur ne passera pas plus de 30 secondes sur ton GitHub : il doit comprendre immédiatement ce que tu as fait, comment tu l'as fait et ce que tu as trouvé.

Voici une structure professionnelle pour ton fichier README.md (en anglais, car c'est le standard dans la Data, mais je peux te le traduire si tu préfères).

Contenu du fichier README.md
Markdown
# 📊 E-Commerce Business Performance Analysis (Olist Dataset)

## 📌 Project Overview
This project provides a comprehensive analysis of the Brazilian E-Commerce public dataset by **Olist**. 
The goal is to analyze sales performance, identify seasonal trends, and evaluate customer satisfaction to provide actionable business insights.

---

## 🛠️ Methodology (CRISP-DM)
This project follows the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) framework:
1.  **Business Understanding**: Focus on sales volume and growth drivers.
2.  **Data Understanding**: Exploration of a relational database (9 tables).
3.  **Data Preparation**: Merging datasets, handling missing values, and datetime formatting.
4.  **Exploratory Data Analysis (EDA)**: Temporal analysis, Pareto distribution, and satisfaction mapping.

---

## 🔑 Key Business Questions
- What is the monthly sales trend?
- Which product categories dominate the volume of sales?
- Is there a correlation between delivery time and customer satisfaction scores?

---

## 🚀 Technical Stack
- **Language**: Python 3.x
- **Libraries**: 
  - `Pandas`: Data manipulation and cleaning.
  - `Matplotlib` & `Seaborn`: Advanced data visualization.
- **Environment**: Kaggle / Jupyter Notebook.

---

## 📈 Key Insights
- **Seasonality**: A massive spike in sales is observed every November due to **Black Friday** in Brazil.
- **Top Categories**: 20% of product categories (Bed_Bath_Table, Health_Beauty) account for nearly 50% of total sales volume.
- **Customer Satisfaction**: Late deliveries are the #1 driver for review scores below 3 stars.

---

## 📂 Project Structure
```text
├── data/                   # (Optional) Link to Kaggle dataset
├── notebooks/
│   └── olist_analysis.ipynb # Main analysis notebook
├── output/
│   └── visualizations/     # Exported charts
└── README.md               # Project documentation
🔗 How to run
Clone this repository.

Download the data from Kaggle.

Run the Jupyter Notebook olist_analysis.ipynb.

👨‍💻 Author
Ton Nom Ton LinkedIn | Ton Portfolio


---

### Conseils pour rendre ton GitHub irrésistible :

1.  **Ajoute des images :** Dans ton README, tu peux insérer les graphiques les plus parlants (le graphique temporel et le Top 10) en utilisant la syntaxe : `![Description](lien_de_l_image.png)`. Un README visuel est 10x plus lu.
2.  **Le fichier `requirements.txt` :** Ajoute un petit fichier nommé `requirements.txt` à la racine de ton projet contenant juste :
    ```text
    pandas
    matplotlib
    seaborn
    ```
    Cela montre que tu sais comment gérer les dépendances d'un projet.
3.  **Le résumé "Executive Summary" :** En haut du README, juste sous le titre, écris deux phrases sur l'impact financier de ton analyse. Exemple : *"Cette analyse a permis d'identifier que 15% des retards de livraison pourraient être évités en optimisant la logistique dans l'État de São Paulo."*

### Pour Kaggle (L'Introduction) :
Sur Kaggle, dans la cellule Markdown tout en haut de ton notebook, utilise ce texte plus court :

> **Welcome to the Olist Sales Analysis!** 🛒
> In this notebook, I dive deep into the Brazilian E-commerce landscape. Moving beyond simple charts, I use a structured **CRISP-DM approach** to uncover hidden patterns in sales seasonality and customer behavior. 
> **Goal:** Turn raw transactional data into strategic business recommendations.
