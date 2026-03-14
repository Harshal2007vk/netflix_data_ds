# Netflix Data Analysis

Exploratory Data Analysis (EDA) of Netflix movies and TV shows dataset to uncover trends, patterns, and insights.

---

## Dataset

| Property | Details |
|---|---|
| File | `NetflixData.csv` |
| Rows (after cleaning) | ~25,779 |
| Columns | `Release_Date`, `Title`, `Overview`, `Popularity`, `Vote_Count`, `Vote_Average`, `Original_Language`, `Genre`, `Poster_Url` |

---

## Project Structure

```
Netflix-Data-Analysis/
├── NetflixData.csv
├── Netflix_Data_Analysis__2_kk.ipynb
└── README.md
```

---

## Analysis Steps

1. **Data Loading** — Load dataset into a Pandas DataFrame
2. **Data Preview & Structure** — Inspect rows, columns, data types, and shape
3. **Statistical Summary** — Descriptive statistics for numerical columns
4. **Data Quality Check** — Identify and remove duplicates and missing values
5. **Data Preprocessing** — Extract year from dates, drop irrelevant columns, explode multi-genre rows
6. **Data Visualization** — 5 key questions answered with interactive Plotly charts

---

## Key Questions Explored

| # | Question |
|---|---|
| 1 | Which genre appears most often? |
| 2 | Which movies have the highest popularity? |
| 3 | How has movie production changed over time? |
| 4 | Which genres have the highest average popularity? |
| 5 | What is the distribution of popularity scores? |

---

## Key Findings

- **Drama** is the most common genre on Netflix.
- **Spider-Man: No Way Home** has the highest popularity score, followed by *The Batman*, *No Exit*, and *Encanto*.
- Movie releases increased significantly **after 2000**, reflecting the growth of the streaming era.
- **Adventure** movies have the highest average popularity among all genres; Action and Science Fiction also rank highly.
- Popularity scores are **heavily right-skewed** — most movies are average, while only a few become blockbuster hits.

---

## Technologies Used

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| pandas | Data manipulation and cleaning |
| plotly.express | Interactive visualizations |
| Google Colab / Jupyter | Notebook environment |

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Netflix-Data-Analysis.git
   cd Netflix-Data-Analysis
   ```

2. Install dependencies (if running locally):
   ```bash
   pip install pandas plotly
   ```

3. Open and run the notebook:
   ```
   Netflix_Data_Analysis__2_kk.ipynb
   ```

> **Note:** If running locally (not on Google Colab), update the dataset path in the notebook:
> ```python
> df = pd.read_csv('NetflixData.csv')
> ```

---

## Author

GitHub: [@your-username](https://github.com/your-username)
