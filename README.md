# L1-Sensitivity-For-Threshold-Query
Udacity & Facebook Private AI Challenge Scholarship 

The task is to measure sensitivity when people are removed from a database (one different sample per dataset).

In this repo are reported solutions for this project (Lesson 4-Evaluating Privacy of a Function). 
The database comprises of an input dataset from which all other datasets are originated by removing one sample only (e.g. different sample every time) per dataset.

Sensitivity is calculated for sum, mean and threshold query functions. Such query functions have different level of sensitivity but they are not differentially private.

Sensitivity is finally evaluated for the simplest attack: differencing attack. The attack is carried out using a certain query function on 

-the full database vs,
-the database minus a specific person (e.g. row 10 is removed). 

This helps to undertstand what's the actual value of the sample removed (e.g. row 10).

The differencing attack is carried out using the sum, mean and threshold query functions.

