# Marketing A/B Testing Analysis

This project evaluates the effectiveness of an advertising campaign using A/B testing. It analyzes user behavior, calculates conversion lift, and estimates the revenue impact of ads.

## Dataset
- **Source**: Kaggle [Marketing A/B Testing Dataset](https://www.kaggle.com/faviovaz/marketing-ab-testing)
- **Columns**:
  - `user id`: Unique user identifier
  - `test group`: Indicates if the user saw an ad or PSA
  - `converted`: Conversion status (True/False)
  - `total ads`: Number of ads seen by the user
  - `most ads day`: Day with the highest ad exposure
  - `most ads hour`: Hour with the highest ad exposure

## Key Findings
- **Lift in Conversion Rate**: 43.09%
- **Additional Revenue**: $24,324,836.19
- **High-Impact Periods**: Fridays and weekends show the highest ad exposure.

## Files
- `analysis.ipynb`: Jupyter notebook with the full analysis.
- `marketing_AB.csv`: Dataset used in the analysis.

## Tools and Libraries
- Python
- pandas, numpy, matplotlib, seaborn
- statsmodels

## Usage
Clone the repository and run the analysis using Python or Jupyter Notebook:
```bash
git clone https://github.com/your-username/Marketing_AB_Testing.git
cd Marketing_AB_Testing
jupyter notebook analysis.ipynb



## Analysis Steps
1. **Data Exploration**:
   - Understand the structure and summary of the dataset.
   - Check for missing values or anomalies.
2. **Conversion Rate Analysis**:
   - Compare conversion rates between the ad and PSA groups.
3. **Statistical Testing**:
   - Perform a two-proportion Z-test to assess the significance of the observed differences.
4. **Lift and Revenue Calculation**:
   - Quantify the impact of ads on conversion rates and revenue.
5. **Ad Exposure Analysis**:
   - Explore user behavior by day and hour to identify high-impact periods.
6. **Segmentation**:
   - Group users by engagement levels and analyze conversion behavior.

## How to Run
Clone the repository and run the analysis locally:

```bash
# Clone the repository
git clone https://github.com/your-username/Marketing_AB_Testing.git

# Navigate into the project folder
cd Marketing_AB_Testing

# Open the analysis notebook
jupyter notebook analysis.ipynb



