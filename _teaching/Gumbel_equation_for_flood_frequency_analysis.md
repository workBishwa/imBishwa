---
title: "FLOOD FREQUENCY ANALYSIS USING GUMBEL’S DISTRIBUTION METHOD"
collection: teaching
type: "Graduate course"
permalink: /teaching/2024-Gumbel_equation_for_flood_frequency_analysis
venue: "Tribhuvan University, College of Applied Sciences-Nepal , Hydrology Department"
date: 2024-12-09
location: "Kathmandu, Nepal"

---


## Equations for Gumbel Distribution

### Maximum Series
\[
M_n = \max \{ X_1, X_2, \dots, X_n \}
\]

### Gumbel Equation
\[
X_T = \text{mean} + K \cdot SD
\]

Where:
- \( SD = \text{standard deviation} \)
- \( K = \text{frequency factor} \)
  
The frequency factor \( K \) is given by:
\[
K = \frac{Y_T - Y_n}{S_n}
\]

#### Components of \( K \):
1. \( Y_T \) = Reduced variate, a function of \( T \):
   \[
   Y_T = -\ln(\ln(\frac{T}{T-1}))
   \]
   Or:
   \[
   Y_T = -[0.834 + 2.303 \cdot \log(\log(\frac{T}{T-1}))]
   \]
   
2. \( Y_n \) = Reduced mean, a function of sample size \( N \).  
3. \( S_n \) = Reduced standard deviation, a function of sample size \( N \).