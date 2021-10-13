# Confidence Intervals

It is well-documented in Agresti and Caffo, 2000 and Agresti & Coull, 1998 that
 the 95% confidence intervals for one and two sample tests derived from Wald 
 tests have poor performance in terms of coverage rates, with the actual 
 coverage probability being much lower than intended. 

The purpose of this project was to replicate and expand the findings of the 
above research. The result in the paragraph above matches with our simulations 
comparing the coverage rates of different confidence intervals with both one 
sample and two samples. In addition, we wanted to investigate the performance 
of the adjusted Plus-4 intervals at other common levels of significance, α = 0.1 
and α = 0.01 in comparison with other confidence intervals noted in the articles.

View the full paper: **Plus_4_Interval.pdf**. This paper was done in 
collaboration with Vanessa Yang and Zhening Zhang. 

**confidence_int_sim.rmd** simulates the coverage rates of these confidence 
intervals in practice using R. Running it produces a pdf file showing coverage 
rates in visualizations, which were used in the paper above. This file is 
solely my work.










