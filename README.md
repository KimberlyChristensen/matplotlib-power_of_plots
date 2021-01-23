# Matplotlib - The Power of Plots

## Summary

The data includes study results for mice, measuring various features including general demographics (sex, age, weight) and test features (Drug Regimen, Tumor Volume, Number of Metastatic sites).  There were 249 mice in the original merged data.  Data was removed for one mouse as the data appeared to be unreliable. 

## Observations and Insights
After removing the data that appeared unreliable, the following insights were observed on this dataset:

* Of the nine drug regimens (and one placebo) included in the test, Ramicane had the lowest mean and median tumor volume, and lowest standard deviation, implying that it was potentially the most effective. The highest mean and median tumor volumes were observed with the Ketapril treatment, indicating that this treatment was potentially even less effective than the placebo.

* Of the mice included in the study, 51% were male and 49% were female, a nearly even distribution.

* Looking at a subset of the treatment regimens, Capomulin and Ramicane had similar outcomes, with Ramicane reflecting the lowest tumor volumes, with no outliers. Infubinol and Ceftamin had higher tumor volumes, though Infubinol results reflect one outlier in the range of the Ramicane median.

* Looking further at the Capomulin data for a single mouse, it appears that the treatment is associated with an increase in tumor volume initially, but the tumor volume decreases over time.  The data was taken over 45 days.  The tumor volume increased on average over days 35-45, though was significantly reduced from the start of the treatment.

* As might be expected, there is a strong positive relationship between tumor size and a mouse's weight (in grams).  The correlation between the mouse weight and average tumor volume is 0.84.



