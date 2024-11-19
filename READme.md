# Customer Satisfaction Analysis

This repository contains an exploratory analysis project focusing on customer satisfaction data. The objective is to identify factors influencing customer satisfaction and provide actionable insights for improving service quality.

## Project Overview

Customer satisfaction is a crucial metric for evaluating business success. This project analyzes key factors such as product quality, delivery time, customer service, website ease of use, and other parameters to understand their impact on customer satisfaction.

### Key Objectives:
- Analyze customer satisfaction data.
- Identify areas with low ratings and potential improvement.
- Visualize trends and distributions of key metrics.

---

## Repository Structure

- **`customer_satisfaction_analysis.ipynb`**: Main Jupyter Notebook containing the data analysis process, visualizations, and findings.
- **`data.csv`**: Sample dataset used for the analysis. *(Ensure sensitive data is anonymized before sharing publicly.)*
- **`.gitignore`**: Lists files and directories ignored by Git.

---

## Key Features

1. **Data Preprocessing**:
   - Binning age into groups for demographic insights.
   - Handling missing values and standardizing the dataset.

2. **Exploratory Data Analysis**:
   - Histograms for visualizing the distribution of numeric variables.
   - Identification of low-rated metrics for targeted improvements.

3. **Mean Ratings Analysis**:
   - Grouped analysis based on age groups and gender.
   - Key insights into demographics and preferences.

4. **Visualization**:
   - Clear and intuitive plots to highlight trends and distributions.
   - Ratings comparison across different categories.

---

## Usage

### Prerequisites:
Ensure the following are installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries (`pandas`, `matplotlib`, etc.)

### Steps to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/RohanV01/Customer-Satisfaction-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Customer-Satisfaction-Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook customer_satisfaction_analysis.ipynb
   ```

---

## Dataset

The dataset (`data.csv`) includes anonymized customer satisfaction data with columns such as:
- **Age**: Age of the customer.
- **ProductQualityRating**: Rating for product quality.
- **DeliveryTimeRating**: Rating for delivery time.
- **CustomerServiceRating**: Rating for customer service.
- **WebsiteEaseOfUseRating**: Rating for website usability.
- **PurchaseFrequency**: Frequency of purchases by the customer.
- **ReturnRate**: Percentage of items returned by the customer.

---

## Insights and Observations

### Sample Findings:
- Product quality and delivery time have the greatest influence on overall satisfaction.
- Younger customers (18-29) tend to rate website ease of use higher compared to older demographics.

*(More detailed findings can be found in the notebook.)*

---

## Future Work

- Incorporate machine learning models to predict customer satisfaction.
- Integrate additional datasets for cross-category comparisons.
- Enhance visualizations with interactive dashboards.