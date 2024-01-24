The Current Population Survey (CPS) datasets, sourced from Francis X. Diebold's "Econometric Data Science: A Predictive Modeling Approach," comprise 1323 observations. These include variables such as AGE, FEMALE (1 for female, 0 otherwise), NON-WHITE (1 for nonwhite, 0 otherwise), UNION (1 for union members, 0 otherwise), EDUC (years of schooling), EXPER (potential working experience), and WAGE.

EDUC is derived from the CPS's PEEDUCA (educational attainment), while EXPER, not directly available in the CPS, is calculated as AGE minus EDUC minus 6, representing potential work experience.

WAGE is determined from hourly earnings (PRERNHLY) for those paid by the hour. For non-hourly workers (PRERNHLY=0), WAGE is calculated by dividing gross weekly earnings (PRERNWA) by usual working hours per week (PEHRUSL1). Missing values in WAGE, indicating missing earnings, are excluded from the dataset.

