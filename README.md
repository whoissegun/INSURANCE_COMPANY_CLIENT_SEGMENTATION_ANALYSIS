# INSURANCE_COMPANY_CLIENT_SEGMENTATION_ANALYSIS


This repository contains a data analysis project on client segmentation based on an insurance company's data. The primary goal of the project is to understand the client base of the company by segmenting them based on Age, Annual Income, and Education (Graduate or Not), followed by insightful data interpretation.

Data Source
The data used in this analysis can be found at: https://www.kaggle.com/datasets/sellingstories/travel-company-insurance-prediction?select=Travel+Company+Old+Clients.csv


Segmentation:

Age
Clients are segmented into different age groups using the pd.cut function in pandas. The age groups used for segmentation are 25-28, 28-31, 31-34, and 34-37.

Annual Income
Clients are also segmented based on their income. I used pd.cut to divide clients into different income ranges. The income ranges are 0-300,000, 300,000-600,000, 600,000-900,000, 900,000-1,200,000, 1,200,000-1,500,000, and 1,500,000-1,800,000.

Education
I analyzed the 'GraduateOrNot' column to segment the clients based on their education. Clients are divided into two categories: Graduates and Non-Graduates.

Visualization and Interpretation
After segmentation, I visualized the distribution of clients in each segment using pie charts. The pie charts show the percentage of clients in each age group, income range, and education category.

I also provide a comprehensive interpretation of each distribution, discussing the company's client base characteristics and giving some insights that might be useful for the company's strategy
