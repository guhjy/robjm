# robjm: An R Package for Robust Longitudinal and Joint Models
[Dynamic predictions of kidney graft survival in the presence of longitudinal outliers](https://arxiv.org/abs/1905.00816)

[Robust joint models](https://ozgurasar.netlify.com/post/robust_joint/)

Install and load using the following lines:

library(devtools)  
install_github("ozgurasarstat/robjm")  
library(robjm)  

TO DO:

- add rate of change to the survival model other than nor nor and mod3

- prediction for the models other than nor and mod3

- prediction for longitudinal data

- plot, summary, print etc

- develop general function for ld and jm, e.g. a function that is for nor, mod1, mod2, mod3, tv as a sinlge file 

- and make it or all functions efficient, eta1 and eta2, linpred removed, for loop for y is removed, 
for loop for B or Bstar is removed. loop for d_B etc is changed

- add last.time option

- looping over A[n] where A is an array is more fficienct than if A is a matrix (pp  325 of stan ref doc)

- add information criterion for number of knots

- make the codes more efficients
