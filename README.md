# Comprehensive-Health-Data-Analytics-Patient-Monitoring-and-Trend-Analysis

This project involved an in-depth analysis of a diverse health monitoring dataset containing records from 500 patients. The primary objective was to extract meaningful insights from various health metrics and identify patterns that could inform patient care strategies.

## Key components of the project included:

### Data Preprocessing and Exploration:
• Handled missing data in body temperature and oxygen saturation columns using median imputation.
• Conducted initial statistical analysis to understand the distribution and central tendencies of key health metrics.
• Visualized the distribution of numerical health indicators including age, heart rate, respiratory rate, body temperature, and oxygen saturation.

### Demographic Analysis:
• Examined the gender distribution in the dataset, finding a near-even split with a slight majority of male patients (51.2%).
• Investigated potential differences in heart rate and oxygen saturation between genders, revealing minimal variation.

### Vital Sign Analysis:
• Analyzed heart rate variations across different activity levels (resting, walking, running).
• Examined blood pressure distributions, identifying common systolic readings around 120 mmHg and 140 mmHg.
• Investigated the relationship between sleep quality, stress levels, and vital signs such as heart rate and oxygen saturation.
• Assessed how respiratory rate and body temperature changed with different activity levels.

### Patient Categorization:
• Developed a custom categorization system to group patients based on:
  - Age: Young (≤35), Middle-aged (36-55), Senior (>55)
  - Blood Pressure: Normal, Elevated, Hypertension Stage 1, Hypertension Stage 2
  - Heart Rate: Low (<60 bpm), Normal (60-100 bpm), High (>100 bpm)
  - Oxygen Saturation: Normal (≥94%), Low (<94%)
• Visualized the distribution of patients across these categories to identify prevalent health patterns.

### Key Findings:
• The majority of patients maintained normal oxygen saturation levels (≥94%).
• Blood pressure readings showed significant variability, with common peaks at 120 mmHg and 140 mmHg for systolic pressure.
• Respiratory rate showed a clear increase with activity level, rising from resting to walking to running states.
• Sleep quality and stress levels had minimal impact on heart rate and oxygen saturation in this dataset.
• The dataset included a higher proportion of seniors compared to young and middle-aged individuals.

### Visualization and Reporting:
• Created over 10 data visualizations including histograms, box plots, and heatmaps to illustrate health trends and patterns.
• Generated summary statistics and correlation matrices to support findings.

This project demonstrated proficiency in data analysis, statistical interpretation, and data visualization using Python and libraries such as Pandas, Matplotlib, and Seaborn. It showcased the ability to derive actionable insights from complex health data, which could be valuable for healthcare providers in patient monitoring and developing personalized care strategies.
