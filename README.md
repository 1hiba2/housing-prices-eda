# 🏠 Housing Prices – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a housing dataset using Python.

The main objective is to explore housing prices, understand the relationships between property characteristics, and identify which factors are associated with variations in house prices.

Through statistical analysis and data visualization, this project provides insights into the housing market and the characteristics that influence property prices.

## 🎯 Objectives

- Explore and understand the housing dataset.
- Analyze the distribution of housing prices and property areas.
- Investigate relationships between house prices and property features.
- Examine the influence of bedrooms, bathrooms, air conditioning, and furnishing status.
- Identify numerical variables correlated with housing prices.
- Visualize patterns and trends using statistical plots.

## 🛠️ Technologies & Libraries

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Google Colab / Jupyter Notebook** – Development environment.

## 📂 Dataset Description

The dataset contains housing information, including:

| Feature | Description |
|---|---|
| price | House price |
| area | Property area |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of floors |
| mainroad | Main road accessibility |
| guestroom | Guestroom availability |
| basement | Basement availability |
| hotwaterheating | Hot water heating availability |
| airconditioning | Air conditioning availability |
| parking | Number of parking spaces |
| prefarea | Preferred area |
| furnishingstatus | Furnishing status |

## 📊 Exploratory Data Analysis

The project includes the following visualizations and analyses:

1. **Housing Price Distribution:** Histogram with KDE to understand price distribution.
2. **Area Distribution:** Exploring the distribution of property sizes.
3. **Bedrooms and Bathrooms:** Analyzing the frequency of bedrooms and bathrooms.
4. **Area vs. Price:** Scatter plot to investigate the relationship between property area and price.
5. **Bedrooms vs. Price:** Box plot to compare prices according to the number of bedrooms.
6. **Air Conditioning vs. Price:** Comparing housing prices based on air conditioning availability.
7. **Furnishing Status vs. Price:** Exploring price differences between furnished, semi-furnished, and unfurnished properties.
8. **Correlation Heatmap:** Visualizing correlations between numerical variables.
9. **Correlation with Price:** Ranking numerical variables according to their correlation with housing prices.

## 💡 Key Findings

- Housing prices show a right-skewed distribution, with a limited number of properties having very high prices.
- Larger properties generally tend to have higher prices.
- Most houses have three bedrooms and one bathroom.
- Housing prices generally increase with the number of bedrooms, although the relationship is not always consistent.
- Houses with air conditioning tend to have higher prices.
- Furnished houses generally have higher prices than semi-furnished and unfurnished houses.
- Property area and number of bathrooms show the strongest positive correlations with price among the numerical variables analyzed.

### Correlation with Housing Prices

| Feature | Correlation |
|---|---:|
| Area | 0.536 |
| Bathrooms | 0.518 |
| Stories | 0.421 |
| Parking | 0.384 |
| Bedrooms | 0.366 |

## 📁 Project Structure

```text
housing-prices-eda/
│
├── Housing.csv
├── TP2_EDA_Housing.ipynb
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/housing-prices-eda.git
```

2. Navigate to the project directory:

```bash
cd housing-prices-eda
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the notebook:

```bash
jupyter notebook TP2_EDA_Housing.ipynb
```

Alternatively, upload the notebook to Google Colab and upload `Housing.csv` when prompted.

## 📚 What I Learned

Through this project, I strengthened my understanding of:

- Data exploration and analysis using Pandas.
- Working with numerical and categorical variables.
- Creating meaningful visualizations.
- Understanding correlation between variables.
- Extracting insights from datasets.
- Using Python libraries for data analysis.

## 👩‍💻 Author

Hiba Gourram

Aspiring Data Analyst | Python | Data Analytics | Data Science
⭐ If you find this project interesting, feel free to explore the notebook!# housing-prices-eda
Exploratory Data Analysis of Housing Prices using Python, Pandas, Matplotlib and Seaborn. Python Data Analysis EDA
