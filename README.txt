Project Title: Fetal Health Classification based on Cardiotocogram (CTG) Data - Comparison of Classification Model Performance

Description and Objectives: The objective of our project will be to compare classification models to classify the outcome of Cardiotocogram (CTG) exam in order to reduce child mortality rates.

Background: 

The reduction in child and maternal mortality rates serve as key indicators of societal progress. In 2019, the United Nations International Children’s Fund (UNICEF) reported a mortality rate of 38/1000 for under-five deaths, which is when a child passes away between birth and exactly five years of age. 

This rate translates to approximately 5.2 million under-five-deaths worldwide from countries reporting their data. In tandem to under-five-deaths, the World Health Organization (WHO) reported that 295,000 women have died during and after pregnancy and childbirth in 2017. 

With the use cardiotocograms (CTGs), which are cost efficient fetal heart monitors, healthcare professionals are able to take preventative action and reduce the chances of child and maternal mortality. For this study, we aim to use cardiotocogram data to classify CTG features into three health rates, with the motivation to improve child and parent survival rates.  



Team Members: 
1. Payal Muni
2. Bikram Gill
3. Aubrey Barrett



Name of Your Selected Dataset and Programming Language: Fetal Health Classification in R

Description of Your Selected Dataset (data source, number of variables, size of dataset, etc.): 

Our dataset was obtained from Kaggle. The dataset, named fetal_health.csv, contains 22 columns and 2126 rows.
Variables: 
Data Column						Definition
baseline value						Baseline Fetal Heart Rate (FHR)
accelerations						Number of accelerations per second
fetal_movement						Number of fetal movements per second
uterine_contractions					Number of uterine contractions per second
light_decelerations					Number of LDs per second (heart rate)
severe_decelerations					Number of SDs per second (heart rate)
prolongued_decelerations					Number of PDs per second (heart rate)
abnormal_short_term_variability				Percentage of time with abnormal short term variability (heart rate)
mean_value_of_short_term_variability			Mean value of short term variability (heart rate)
percentage_of_time_with_abnormal_long_term_variability	Percentage of time with abnormal long term variability (heart rate)
mean_value_of_long_term_variability			Mean value of long term variability (heart rate)
histogram_width						Width of heart rate measuremeant histogram (pulse)
histogram_min						Min of heart rate measuremeant histogram (pulse)
histogram_max						Max of heart rate measuremeant histogram (pulse)
histogram_number_of_peaks					Number of peaks in heart rate measuremeant histogram (pulse)
histogram_number_of_zeroes				Number of zeroes in heart rate measuremeant histogram (pulse)
histogram_mode						Mode heart rate measuremeant histogram (pulse)
histogram_mean						Mean of heart rate measuremeant histogram (pulse)
histogram_median						Median of heart rate measuremeant histogram (pulse)
histogram_variance					Variance of heart rate measuremeant histogram (pulse)
histogram_tendency					Tendency of heart rate measuremeant histogram (pulse)
fetal_health						Tagged as 1 (Normal), 2 (Suspect) and 3 (Pathological)




Full code for this classification comparison can be found on: https://github.com/bikramgill3/ADS502


References: 

