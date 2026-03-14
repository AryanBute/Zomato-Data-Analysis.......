# Zomato Data Analysis Project

An exploratory data analysis (EDA) project on Zomato restaurant data, uncovering insights about restaurant types, ratings, votes, pricing, and online ordering trends.

## Project Overview

This notebook analyzes a dataset of 148 Zomato restaurants across 7 features to answer key business questions:

- What types of restaurants are most common?
- Which restaurant type receives the most votes?
- What is the rating distribution across restaurants?
- What is the typical spending for couples?
- Does offering online ordering affect a restaurant's rating?
- How does online ordering availability vary across restaurant types?

## Dataset

**File:** `Zomato data (1).csv`

**Shape:** 148 rows × 7 columns

| Column | Description |
|--------|-------------|
| `name` | Restaurant name |
| `online_order` | Whether online ordering is available (Yes/No) |
| `book_table` | Whether table booking is available (Yes/No) |
| `rate` | Restaurant rating (e.g., `4.1/5`) |
| `votes` | Number of votes received |
| `approx_cost(for two people)` | Approximate cost for two people (INR) |
| `listed_in(type)` | Restaurant category (Buffet, Dining, Cafes, etc.) |

## Key Findings

1. **Restaurant Types:** The majority of restaurants fall in the **Dining** category.
2. **Votes by Type:** Dining restaurants receive the **maximum votes**.
3. **Rating Distribution:** Most restaurants are rated between **3.5 and 4.0**.
4. **Couple Spending:** The majority of couples prefer restaurants with an approximate cost of **₹300**.
5. **Online Orders & Ratings:** Restaurants that accept online orders tend to receive **higher ratings**.
6. **Heatmap Insights:** Online ordering availability varies significantly across restaurant listing types.

## Visualizations

- **Count plot** — Distribution of restaurant types
- **Line plot** — Total votes per restaurant type
- **Histogram** — Rating frequency distribution
- **Count plot** — Approximate cost distribution for couples
- **Box plot** — Rating vs. online order availability
- **Heatmap** — Restaurant type vs. online order availability

## Project Structure

```
.
├── Zomato_DA.ipynb        # Main Jupyter Notebook
├── Zomato data (1).csv    # Dataset
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or Google Colab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/zomato-data-analysis.git
   cd zomato-data-analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Zomato_DA.ipynb
   ```

   Or upload to [Google Colab](https://colab.research.google.com/) and run directly.

## Technologies Used

- **Python** — Core language
- **Pandas** — Data loading and manipulation
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization

## License

This project is open-source and available under the [MIT License](LICENSE).
