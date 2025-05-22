 # This is a 10 Academy KAIM Week 0 task
 In Windows, a virtual environment can be created and activated as follows
 python -m venv virtual_name # creation
 virtual_name\Scripts\activate # activation
  deactivate #activation
 deactivate #deactivation
# Solar Data Analysis and EDA
 A data analysis project focused on exploring and cleaning solar irradiance and weather data from multiple African countries (Benin, Togo, Sierra Leone). The goal is to uncover trends, detect anomalies, and prepare data for future modeling.

## Folder Structure
├── data/                  # Cleaned CSV files (not committed; see .gitignore)
├── Notebook/              # Jupyter notebooks for each country
│   ├── benin-eda.ipynb
│   ├── togo-eda.ipynb
│   └── sierraleone-eda.ipynb
├── plots/                 # Output visualizations (optional)
├── README.md              # Project documentation
├── requirements.txt       # Dependencies (if any)
└── .gitignore             # Specifies ignored files (e.g., CSVs)
## How to Run

1. Clone the repository.
2. Set up your environment:
   ```bash
   pip install -r requirements.txt

---

### 5. **Key Features**
```markdown
## Key Features

- Cleaning and preprocessing of raw solar and weather data.
- Handling missing values and outliers.
- Exploratory Data Analysis (EDA):
  - Line, bar, and bubble plots
  - Correlation heatmaps
  - Wind rose and histograms
- Comparison across countries using ANOVA and summary stats.
## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- scipy
## Contributing

Feel free to fork this repo and submit pull requests for improvements or country extensions.

