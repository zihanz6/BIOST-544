### Overview
This project aims to 1) evaluate the association between enterolactone (ENL) and concentration of different bile acids, and 2) evaluate the association between enterodiol (END) and concentration of different bile acids. The results of this project might bring us valuable insights into possible physiological pathways through which the two major diet-derived polyphenol metabolites can affect metabolic signaling and ultimately influence cancer risk.

### Data Source
The data came from the Carbohydrate and Related Biomarkers (CARB) Study, a randomized controlled crossover feeding trial (conducted from June 2016 to July 2009) investigating the effect of diet high in whole grain vs. refined grain on circulating bile acids. The trial involved 80 healthy adults (40 men/40 women, 18-45 years) from the great Seattle Area, with equal numbers of normal weight and overweight/obese individuals.

### Method
Linear mixed models were used to assess the association between each bile acid and ENL level, as well as the association between each bile acid and END level. We adjusted age, sex, race, and dietary intervention as fixed effects and participant ID as the random effect. Benjamin-Hochberg procedure was applied to control for multiple comparisons at a false discovery rate of 10%.  

### Result
ENL excretion was positively associated with Murocholic acid (p = 0.048), and negatively associated with Deoxycholic acid (p = 0.01) and Ursodeoxycholic acid (p = 0.011). END excretion was associated linearly with Taurocholic acid (p = 0.014). However, none of these associations satisfy the FDR threshold of q < 0.1 after BH adjustment.

### Discussion
A notable advantage of this project is that the data comes from a controlled feeding trial. The closely regulated diet substantially reduces the confounding effect of diet on our association of interest. Besides, this project examines multiple associations at one time, which is an effective way of utilizing the trial data. A limitation is the moderate sample size, which might lead to insufficient power to detect true associations. Another limitation is that there was no way to fully supervise participants’ eating behavior outside the laboratory setting, so we cannot rule out the possibility of residual confounding effect by inter-individual variation in diet. Furthermore, causal inference cannot be drawn given the cross-sectional nature of the analysis.
