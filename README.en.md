# ConnectaTel Customer Analysis

[Español](README.md) | English

## Project objective

Analyze data from **4,000 customers** and **40,000 call and message records** from ConnectaTel in 2024 to assess data quality, identify usage patterns and outliers, build customer segments, and develop business insights.

## Datasets

| File | Contents |
|---|---|
| `plans.csv` | Features, allowances, prices, and additional charges for the Básico (Basic) and Premium plans. |
| `users_latam.csv` | Customer demographics, city, registration date, subscription plan, and cancellation date. |
| `usage.csv` | Call and message records, including dates, call duration, and message length. |

The CSV files are not included in this repository. To run the analysis, upload them manually to Google Colab using the filenames listed above.

## Analysis workflow

1. Load and explore the datasets.
2. Assess missing values, sentinel values, and inconsistent dates.
3. Clean and validate the affected variables.
4. Build a historical usage profile for each customer.
5. Analyze distributions and outliers.
6. Segment customers by age and usage level.
7. Explore relationships between age, usage, plan, and recorded cancellations.
8. Develop business conclusions and recommendations.

## Open and run the notebook

1. Open [Google Colab](https://colab.research.google.com/).
2. Select **File → Open notebook → GitHub**.
3. Enter the repository URL:

   ```text
   https://github.com/DA-Maximiliano-Berrelleza/telecom_customer_analysis
   ```

4. Select `telecom_customer_analysis.ipynb`.
5. Upload `plans.csv`, `users_latam.csv`, and `usage.csv` to the session's working directory.
6. Select **Runtime → Run all**.
7. Confirm that the cells run in order without errors.

## Reproducibility notes

- Use Python 3 with `pandas`, `numpy`, `matplotlib`, and `seaborn`. These libraries are available in Google Colab.
- Keep the original filenames for all three CSV files.
- Place the datasets in the notebook's working directory.
- Run all cells from top to bottom to reproduce the cleaning, visualizations, segmentation, and business analysis.
