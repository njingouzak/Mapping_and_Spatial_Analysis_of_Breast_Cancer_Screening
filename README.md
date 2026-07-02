# Mapping and Spatial Analysis of Breast Cancer Screening Uptake in Belgium, 2014 and 2017

---
## 📖 **Overview**

Breast cancer (BC) is the most common cancer and the leading cause of cancer death among women in Europe. The progression of this disease can be slowed down by early detection through mammography (EDM) and treatment at an early stage.

Organized mammography screening programs (SP) have been implemented in many European countries. According to European recommendations, to reduce BC mortality through EDM, programs must achieve a participation rate of 70% of the target population with regular screening attendance. In several Northern European countries, participation of around 80% has been achieved. However, in Belgium, despite efforts to facilitate access to breast cancer screening for women aged 50 to 69, national participation in the program remains below this threshold.

The use of a Geographic Information System (GIS) for mapping data is considered a powerful tool in public health. It allows for the identification of priority intervention areas and the targeting of specific campaigns aimed at increasing adherence to public health programs in vulnerable areas. Additionally, spatial analysis makes it possible to detect and better understand geographic disparities by mobilizing statistical approaches adapted to spatial data. These tools could be used to generate knowledge that can improve cancer screening programs.

---
## 🎯 **Objectives**

The two main objectives of this work are:  
- To map the uptake of breast cancer screening at the municipal level in Belgium  
- To identify clusters of municipalities with a significantly lower prevalence of participation in breast cancer screening and to explore explanatory factors

---
## 📊 **Data Source**

Breast cancer screening uptake data were extracted from the Intermutualistic Agency (IMA) atlas for 2014 and 2017. These data were collected through the organized national breast cancer screening program. This program is under the responsibility of the different regions.

---
## 🛠️ **Tools**

![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)  
![GeoDa](https://img.shields.io/badge/GeoDa-1F4E79?style=flat-square)  
![Stata](https://img.shields.io/badge/Stata-1A4D8F?style=flat-square)  
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)  

---
## ⚙️ **Project Workflow**

### **Mapping**

1- a) create an Excel file containing the project variables, b) import the municipal base map and the Excel file into QGIS, and c) join the two files

2- Create a professional map of the municipalities of Belgium allowing for the clear distinction of the different regions.

3- For year 2017, create a map of cancer screening participation at the municipal level for the following health indicators:  
a. Crude prevalence  
b. Age-standardized prevalence  
c. SMR (Standardized Morbidity Ratio)  
d. Difference in standardized prevalence between the 2 years (2017 – 2014)  

4- For year 2017, create a map, at the municipal level, that represents both cancer screening participation (standardized prevalence) and the average number of patients assigned per active general practice.

5- Use the map created in point 3 to propose answers to the following questions:    
a. Are there spatial configurations in screening participation?    
b. Is it conceivable to link the distribution of cancer screening participation and the average number of patients assigned per active general practice?    

### **Spatial Analysis**

6- For the 2 years separately, are there municipalities with an "abnormally" high or low SMR? Which municipalities present these "abnormal" values?

7- Considering the standardized prevalence (only): for the 2 years separately and for the difference, does a spatial phenomenon exist in the data (global and local spatial autocorrelation to be assessed for each year and for the difference)?

8- For year 2017, is there a spatial association between screening uptake and the average number of patients assigned per active general practice?

---
## 🏆 **Key Results**

- **Geographic Disparities in Screening Uptake:** Breast cancer screening participation in Belgium is not uniform. In 2017, participation rates were significantly higher in the northern and northwestern municipalities (the Flemish Region) and lower in the central and southern municipalities (Brussels and Wallonia).

- **Significant Spatial Clustering:** Both global and local spatial analyses revealed strong positive spatial autocorrelation. This confirms that municipalities with similar screening rates (either high or low) are clustered together geographically. High-uptake clusters were consistently found in the north/northwest, while low-uptake clusters were in the south, southwest, and center.

- **Stable Spatial Pattern with Some Negative Changes:** The spatial pattern of high uptake in the north and low uptake in the south remained consistent between 2014 and 2017. However, the analysis of the standardized prevalence difference (2017-2014) showed a more pronounced negative change (decrease in uptake) in municipalities located in the south and southwest of Belgium.

- **Positive Association with General Practice Caseload:** The spatial autoregressive model showed a statistically significant positive association between screening uptake and the average number of patients attributed per active general practice. This suggests that municipalities with a higher patient load per general practice tend to have higher screening participation rates.

- **Explanatory Power of the Spatial Model:** The spatial autoregressive model, which accounted for spatial dependence, explained 84.5% of the variability in screening uptake. This model was significantly better than a standard linear model, confirming that the spatial component is a crucial factor in understanding the distribution of screening participation.

---
## ✅ **Conclusion**

In conclusion, breast cancer screening uptake in Belgium exhibits a persistent spatial pattern, with significantly higher participation in northern Flanders and lower rates in southern Wallonia and Brussels. This geographic disparity is likely driven by regional differences in screening strategies, with Flanders relying more on the organized program. The identification of significant spatial clusters of low uptake highlights priority areas for intervention. Additionally, a positive association between screening uptake and patient caseload per general practice suggests that general practitioners play a key role in improving adherence. Therefore, future policies should adopt spatially targeted approaches and involve general practitioners more extensively to reduce inequalities and increase overall participation.

