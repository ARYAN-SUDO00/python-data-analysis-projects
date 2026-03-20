# Mobile Phone Price Analysis

### Description
This project analyzes a mobile phone price dataset to identify how RAM influences market pricing. The study focuses on understanding the distribution of smartphone costs and the direct correlation between hardware power and retail price.

### Dataset
* **Name:** Mobile Phone Price
* **Source:** [Kaggle - Mobile Phone Price Dataset](https://www.kaggle.com/datasets/rkiattisak/mobile-phone-price)
* **File Used:** `Mobile phone price.csv`

### Tasks Performed
* Cleaned and pre-processed the price column by removing currency symbols and converting to numeric types.
* Performed a Correlation Analysis between RAM and Price using a Strip Plot.
* Created a Histogram to visualize the price distribution across the entire market.
* Grouped data by brand to ensure the RAM-to-Price relationship was consistent across different manufacturers.

### Key Findings
* **The RAM-Price Correlation:** The Scatter Plot reveals a clear "staircase" trend—as RAM increases from 4GB to 12GB, there is a consistent and significant jump in the retail price bracket.
* **Market Concentration:** The Histogram shows that the majority of smartphones in this dataset fall into the "Mid-range" budget ($200–$500), with only a small percentage of "Premium" flagship devices.
* **Price Skewness:** The price distribution is "Right-Skewed," meaning there are many affordable options and fewer ultra-expensive models, reflecting a competitive global market.
* **Hardware Standardization:** 6GB and 8GB RAM have become the most common configurations for mid-to-high-tier devices.

### Tools Used
* Python
* Pandas
* Seaborn & Matplotlib