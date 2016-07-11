# cohens-kappa-matlab
This is a simple implementation of Cohen's Kappa statistic, which measures agreement for two judges for values on a nominal scale. See the Wikipedia entry for a quick overview, or you can get the original article from Sage Publications. Kappa has been used extensively in psychology, and has been more recently applied to land cover / land use changes and to assessments of accuracy for classification algorithms in Remote Sensing (Congalton, 1991; Jensen, 2005).


1	2	3
1	.44	.07	.09
2	.05	.20	.05
3	.01	.03	.06
Crosstabulated frequencies for two judges rating items as belonging to categories 1, 2, or 3. From Cohen (1960), Table 2. The calculated Kappa score for this table is 49.2%. 

Cohen's Kappa can be used to measure error rates in ground segmentation algorithms like SMRF.

Cohen, J. (1960). A Coefficient of Agreement for Nominal Scales. Educational and Psychological Measurement, 20(1), 37-46.
