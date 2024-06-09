---

## Project Title: Customer Segmentation Model Based on RFM Values

## Project Description

This project focuses on customer segmentation using Recency, Frequency, and Monetary (RFM) values. By applying clustering algorithms to these RFM metrics, the project aims to identify distinct customer segments. This segmentation helps businesses tailor their marketing strategies, improve customer retention, and increase overall profitability.

## Features

- **RFM Analysis**: Calculation of Recency, Frequency, and Monetary values for each customer.
- **Clustering Algorithm**: Application of clustering algorithms to segment customers based on RFM values.
- **Visualization**: Development of visualizations to display customer segments and their characteristics.
- **Insights and Actions**: Deriving actionable insights from the segments to inform business strategies.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Clustering Algorithms**: K-Means, DBSCAN, Hierarchical Clustering

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-rfm.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-segmentation-rfm
   ```
3. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**:
   - Place your customer transaction data in the `data/` directory.
   - Run the data preprocessing script to clean and prepare the data:
     ```bash
     python preprocess_data.py
     ```

2. **RFM Calculation**:
   - Calculate the RFM values for each customer:
     ```bash
     python calculate_rfm.py
     ```

3. **Customer Segmentation**:
   - Apply the clustering algorithm to segment the customers based on RFM values:
     ```bash
     python segment_customers.py
     ```

4. **Visualization**:
   - Generate visualizations to analyze and interpret the customer segments:
     ```bash
     python visualize_segments.py
     ```

## Project Structure

```
customer-segmentation-rfm/
│
├── data/
│   └── transactions.csv
│
├── models/
│   └── customer_segments.pkl
│
├── notebooks/
│   └── exploratory_data_analysis.ipynb
│
├── scripts/
│   ├── preprocess_data.py
│   ├── calculate_rfm.py
│   ├── segment_customers.py
│   └── visualize_segments.py
│
├── visuals/
│   └── rfm_clusters.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

## Key Scripts

- **preprocess_data.py**: Handles data cleaning and preparation for RFM analysis.
- **calculate_rfm.py**: Calculates Recency, Frequency, and Monetary values for each customer.
- **segment_customers.py**: Applies clustering algorithms to segment customers based on RFM values.
- **visualize_segments.py**: Generates visualizations to interpret and analyze customer segments.

## Visualization

- **RFM Distribution**: Visual representation of the distribution of RFM values across customers.
- **Customer Segments**: Visualizations of the customer segments, highlighting key characteristics and behaviors.
- **Actionable Insights**: Graphical representation of insights derived from the segments to inform business strategies.

## Insights and Actions

- Identify high-value customers and tailor marketing strategies to retain them.
- Recognize at-risk customers and develop retention plans.
- Understand the spending behavior of different customer segments to optimize product offerings.

## Contributors

- Harshal Dhandrut - [GitHub](https://github.com/harshal-96)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
