# online_retail_data_analysis
Exploratory data analysis and customer segmentation on online retail data.

## 📦 Dataset Note
The dataset used in this project is too large to be hosted on GitHub.

You can download the original dataset here:
- Online Retail Dataset (UCI Machine Learning Repository)

After downloading, place the file in the `data/` directory before running the notebook.
# Save a 5% sample of the cleaned data
df.sample(frac=0.05, random_state=42).to_csv(
    "online_retail_sample.csv", index=False
)
This repository includes a small sample of the dataset for demonstration purposes.
