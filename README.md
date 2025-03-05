# SuperStore EDA Dashboard

This Streamlit application provides an interactive Exploratory Data Analysis (EDA) dashboard for the SuperStore dataset. Users can upload their dataset, filter data dynamically, and visualize insights through various charts and graphs.

## Features
- **Upload File**: Supports CSV, TXT, XLSX, and XLS formats.
- **Date Range Selection**: Filters data based on selected order date range.
- **Region, State, and City Filters**: Enables data filtering by geographic location.
- **Visualizations**:
  - Bar Chart: Category-wise sales analysis.
  - Pie Charts: Region-wise, segment-wise, and category-wise sales.
  - Line Chart: Monthly time-series sales trends.
  - TreeMap: Hierarchical sales view across regions, categories, and sub-categories.
  - Scatter Plot: Relationship between sales and profit.
  - Data Tables: Summary tables for month-wise sub-category sales.
- **Data Download**: Provides options to download filtered and summarized datasets.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Dependencies
Ensure you have the following Python packages installed:
- `streamlit`
- `plotly`
- `pandas`
- `numpy`

Install them using:
```bash
pip install streamlit plotly pandas numpy
```

## Usage
1. Upload the `SampleSuperstore.csv` dataset or any compatible file.
2. Select the required date range using the date picker.
3. Apply filters based on region, state, and city.
4. Explore interactive visualizations and download insights as CSV files.

## Folder Structure
```
/your-repo-name
│── app.py                  # Main Streamlit application
│── SampleSuperstore.csv     # Sample dataset
│── README.md                # Project documentation
```

## License
This project is open-source and available under the [MIT License](LICENSE).


