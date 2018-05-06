# Poisson model for Epilepsy in rate of Seizures

The goal of this analysis is to model the number of seizures suffered by patients, alongside their age and a treatment. Thus, the core goal is to measure the effectiveness of the treatment, Progabide, against the placebo group, in reducing the number of seizures.

# Analysis Summary

Based on the poor fit found under Model Fit, it seems like overdispersion is an issue. As shown in section titled Overdispersion, a Negative Binomial model indicates a much better fit. 
Overall, there is an interaction effect between the age and treatment, which means that the treatment, Progabide, might be more effective for older patients than for younger patients. 
