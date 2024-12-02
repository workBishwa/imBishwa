---
title: "Hydrological Modelling using HEC-HMS Introductory Class"
collection: teaching
type: "Graduate course"
permalink: /teaching/2024-hydrology-teaching-intro_HEC
venue: "Tribhuvan University, College of Applied Sciences-Nepal , Hydrology Department"
date: 2024-12-03
location: "Kathmandu, Nepal"

---

In this project, we will use HEC-HMS to analyze hydrological processes in the Balkhu Basin. The goal is to model runoff, precipitation, and streamflow, and apply methods such as the SCS Curve Number for losses and the SCS Unit Hydrograph for transforming runoff. Additionally, we will incorporate routing and time series data to simulate basin hydrology effectively.  
**Hydrology Project: Balkhu Basin**

## **Subbasin Information**

| **Subbasin** | **Area (km²)** | **Lag Time (min)** | **Loss Method**  | **Transform Method**   | **Ia** | **CN** | **Impervious** | **Graph Type**     |
|--------------|----------------|--------------------|------------------|------------------------|--------|--------|----------------|--------------------|
| S1           | 6.825          | 50                 | SCS Curve Number | SCS Unit Hydrograph    | 10     | 80     | 0.0            | Standard PRF       |
| S2           | 5.8278         | 52                 | SCS Curve Number | SCS Unit Hydrograph    | 10     | 80     | 0.0            | Standard PRF       |
| S3           | 6.3668         | 55                 | SCS Curve Number | SCS Unit Hydrograph    | 10     | 80     | 0.0            | Standard PRF       |
| S4           | 17.603         | 60                 | SCS Curve Number | SCS Unit Hydrograph    | 10     | 80     | 0.0            | Standard PRF       |

---

## **Routing Information**

| **Route** | **Routing Method** | **Initial Type**      | **Lag (min)** |
|-----------|---------------------|-----------------------|---------------|
| R1        | Lag                 | Discharge = Inflow    | 70            |
| R2        | Lag                 | Discharge = Inflow    | 70            |

---

## **Specified Hyetograph**

| **Subbasin** | **Gage** | **Total Depth (mm)** |
|--------------|----------|-----------------------|
| S1           | Gage 1   | 109.2                |
| S2           | Gage 1   | 109.2                |
| S3           | Gage 1   | 109.2                |
| S4           | Gage 1   | 109.2                |

---

## **Time Series Data: Rainfall Events**

| **Time (ddMMMYYYY, HH:mm)** | **Precipitation (mm)** | **Time (ddMMMYYYY, HH:mm)** | **Precipitation (mm)** |
|-----------------------------|-------------------------|-----------------------------|-------------------------|
| 25Sep2011, 14:00           |                        | 26Sep2011, 00:00           | 0.4                     |
| 25Sep2011, 15:00           | 1.8                    | 26Sep2011, 01:00           | 1.2                     |
| 25Sep2011, 16:00           | 0.8                    | 26Sep2011, 02:00           | 2.4                     |
| 25Sep2011, 17:00           | 0.4                    | 26Sep2011, 03:00           | 2.0                     |
| 25Sep2011, 18:00           | 0.9                    | 26Sep2011, 04:00           | 10.0                    |
| 25Sep2011, 19:00           | 1.2                    | 26Sep2011, 05:00           | 7.0                     |
| 25Sep2011, 20:00           | 2.4                    | 26Sep2011, 06:00           | 8.4                     |
| 25Sep2011, 21:00           | 2.0                    | 26Sep2011, 07:00           | 44.0                    |
| 25Sep2011, 22:00           | 1.2                    | 26Sep2011, 08:00           | 7.6                     |
| 25Sep2011, 23:00           | 0.4                    | 26Sep2011, 09:00           | 3.4                     |
|                           |                         | 26Sep2011, 10:00           | 3.0                     |
|                           |                         | 26Sep2011, 11:00           | 6.2                     |
|                           |                         | 26Sep2011, 12:00           | 3.6                     |
|                           |                         | 26Sep2011, 13:00           | 2.4                     |
|                           |                         | 26Sep2011, 14:00           | 0.2                     |

---

## **Notes for Students**

1. Subbasins **S1 to S4** have similar hydrological parameters, ensuring easier modeling consistency.
2. Routing methods (R1 and R2) use **Lag Routing**, with an identical lag time of 70 minutes.
3. Specified hyetograph uses **Gage 1** for all subbasins, with a consistent total depth of 109.2 mm.
4. Rainfall events follow a uniform time series format; ensure accurate input for temporal rainfall analysis.

## **Downloads**

[Balkhu Terrain File (*.tif*)📥](https://workbishwa.github.io/imBishwa/files/clip_balkhu111.tif)  
[projection_coordinate📥](https://workbishwa.github.io/imBishwa/files/balkhu_coordinate.prj)
