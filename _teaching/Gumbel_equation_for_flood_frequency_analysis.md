---
title: "FLOOD FREQUENCY ANALYSIS USING GUMBEL’S DISTRIBUTION METHOD"
collection: teaching
type: "Graduate course"
permalink: /teaching/2024-Gumbel_equation_for_flood_frequency_analysis
venue: "Tribhuvan University, College of Applied Sciences-Nepal , Hydrology Department"
date: 2024-12-09
location: "Kathmandu, Nepal"

---


The Gumbel distribution, also referred to as the type-I generalized extreme value (GEV) distribution, is a statistical distribution widely used in hydrology, meteorology, and risk analysis. It models the probability of extreme events by focusing on the maximum (or minimum) values drawn from a set of observations or samples. These events often represent rare occurrences such as extreme rainfall, floods, heatwaves, or high winds.

The Gumbel distribution is particularly suitable for analyzing extreme values because it emphasizes the tail behavior of data, making it valuable for predicting the likelihood of events beyond the observed range. It is characterized by its cumulative distribution function (CDF) and probability density function (PDF), which describe the probability of extremes occurring within a given range.

In applications:

Maximum values are commonly studied for phenomena like peak discharge in river systems or maximum daily rainfall.
Minimum values can also be analyzed, for instance, in cases like drought conditions or minimum temperatures.
This distribution plays a critical role in risk management and design standards, such as determining the capacity of dams or the flood resilience of urban infrastructure.

## Equations for Gumbel Distribution

### Maximum Series

Mn = max {X1, X2, ..., Xn}

### Gumbel Equation

XT = mean + K * SD bar{x}

Where:
$$z_{1-\alpha/2}\sigma\sqrt{2/n}$$

\(\bar{x}\)

- SD = standard deviation
- K = frequency factor  
  \( K = (YT - Yn) / Sn \)

#### Components of \( K \)

1. YT = Reduced variate, a function of T:
   YT = -[ln(ln(T / (T - 1)))]  
   Or:  
   YT = -[0.834 + 2.303 * log(log(T / (T - 1)))]  

2. Yn = Reduced mean, a function of sample size N.  
3. Sn = Reduced standard deviation, a function of sample size N.
