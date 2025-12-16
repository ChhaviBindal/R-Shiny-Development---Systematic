# Problem Statement
For the estimation of population mean, determine the required sample size in the presence of:
A given number of subgroups (strata)
A specified sampling bias (margin of error / precision level)
Expected cost of surveying each subgroup
Expected time required for surveying each subgroup
The objective is to design an optimal sampling plan and visualize the experimental design using R Shiny.

# Objectives of the Assignment
Determine the minimum total sample size required to estimate the population mean at a chosen confidence level
Allocate samples across subgroups using systematic and stratified sampling principles
Incorporate cost and time constraints into the sampling design
Apply Finite Population Correction (FPC) for accurate variance estimation
Visualize the sampling design and allocation using interactive plots in R Shiny

#Allocation Strategies Used
1. Proportional Allocation
Sample size proportional to subgroup population size
2. Neyman Allocation
Allocation based on subgroup size and variability
3. Optimum Allocation (Cost-Based)
Incorporates cost per observation in each subgroup
Minimizes total survey cost while maintaining precision
4. Optimum Allocation (Time-Based)
Uses time per observation instead of cost
Produces a time-efficient sampling design

# Finite Population Correction (FPC)
Since sampling is performed without replacement, FPC is applied to:
Adjust variance estimates

Prevent overestimation of uncertainty in finite populations
