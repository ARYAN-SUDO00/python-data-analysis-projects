# Road Traffic Accident Data Analysis

### Description
This project analyzes a dataset of 12,000+ road traffic accidents to identify patterns and severity distributions.

### Dataset
* **Name:** Road Traffic Accidents
* **Source:** [Kaggle](https://www.kaggle.com/datasets/saurabhshahane/road-traffic-accidents)
* **File Used:** `RTA_dataset.csv`

### Tasks Performed
* Handled missing values across 32 columns using categorical imputation (filling with "Unknown").
* Converted raw time strings into 24-hour integers to visualize accident spikes.
* Visualized the accident trend from Monday to Sunday, identifying a steady increase toward the weekend.
* Used an "Exploded" Pie chart to emphasize the critical 'Fatal' injury category.

### Key Findings
* **The Friday Peak:** Accidents peak on Fridays, likely due to a combination of work-week fatigue and increased traffic volume.
* **The 5 PM Spike:** A clear surge in accidents occurs during the evening rush hour (3 pm - 6 pm) peaking at 5 p.m.
* **The Safety Pyramid:** 84.3% of accidents result in 'Slight' injuries, while 'Fatal' cases are a small but critical 1.3%.

### Tools Used
* **Python** 
* **Pandas**
* **Matplotlib** 
* **Seaborn** 