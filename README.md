# RDC_microcredential
CU Boulder research data camp microcredential materials

# Nuclear area as a function of cell line

The question: Is the mean nuclear area different among six different celll lines?

Test: ANOVA test on six groups 

large F statistic supports the alternative hypothesis


Response variable: Area of cell nucleus. This is a continuous variable.


Predictor variable: Cell line, A-F . This is a categorical variable as there are 6 discrete categories.


Parameters and hypotheses

  $\mu_A$ = Cell line 'BC_N_FN_A' 
  
  $\mu_B$ = Cell line 'BC_N_FN_B' 
   
  $\mu_C$ = Cell line 'BC_LM_FN_A' 
    
  $\mu_D$ = Cell line 'BC_LM_FN_B' 
 
  $\mu_E$ = Cell line 'BC_HM_FN_A'
 
  $\mu_F$ = Cell line 'BC_HM_FN_B'
  

Null Hypothesis: There is no difference between the average nuclear area among the 6 cell liens cell lines. 

 $H_0$: $\mu_A$ = $\mu_B$ = $\mu_C$ = $\mu_D$ = $\mu_E$ = $\mu_F$ 
 
Alternative hypothesis: One or more of the cell lines has a significantly different average nuclear area.
   
 $H_A$: $\mu_A$ ≠ $\mu_B$ ≠ $\mu_C$ ≠ $\mu_D$ ≠  $\mu_E$ ≠ $\mu_F$
 
The data: This data was collected by fellow lab mates at Colorado State Univeristy in the lab of Dr. Ashok Prasad. 

This script: This code was written by Rosaline A. Danzman, PhD student in the lab of Dr. Ashok Prasad, Department of Chemical and Biological Engineering at Colorado State University.
