---
title: "Sample Size Calculation for RMNCH Survey for Myanmar Migrants"
bibliography: references.bib 
link-citations: TRUE
author: "Kaung Myat Khant"
date: "2024-12-30"
output: 
    word_document:
        keep_md: TRUE
---



### Sampling Design

We are collecting the data on contraceptive utilization or accessibility among the Myanmar migrants at Thailand-Myanmar border. Since they are marginalized or hidden populations, we decided to used **Snowball Sampling** [@ahmed_how_2024]. For a non-probability sampling method, a sample size of **larger than 30 and smaller than 500** is enough for most of the research [@sekaran_research_2003]. Nevertheless, for our cross-sectional descriptive study, with the available information from knowledgeable sources, we will use

-   *Cochran's sample size formula for initial sample size* or
-   *Yamane's formula*

### Sample Size Calculation Based on **Contraceptive Prevalence Rate**

According to *Htoo et al*, the contraceptive prevalence rate was 0.801 [@soe_utilization_2008]. Sample size was calculated using *Cochran's formula*: 

$$ n_0 = Z^2 \cdot \frac{p(1-p)}{E^2} $$  
where:  

-   $n_0$ = initial sample size for infinite population,  
-   Z = z-value (1.96 for 95 % confidence),  
-   p = Estimated population proportion,  
-   E = margin of error



With a 95% confidence interval and margin of error of *0.05*, the sample size based on contraceptive prevalence rate of 0.801 is **245**.

### Sample Size Calculation Based on **Unmet Need for Family Planning**

According to *Thein 2020*, the unmet need for family planning was 0.158 [@thein_unmet_2020]. we calculated the sample size using *Cochran's formula*: 

$$ n_0 = Z^2 \cdot \frac{p(1-p)}{E^2} $$  

where:  

-   $n_0$ = initial sample size for infinite population,  
-   Z = z-value (1.96 for 95 % confidence),  
-   p = Estimated population proportion,  
-   E = margin of error  



With a 95% confidence interval and margin of error of *0.05*, the sample size based on proportion for unmet need of family planning 0.158 is **204**.  

### Sample Size Based on Population Information from IOM

According to a brief report by International Organization of Migration, Overview of Myanmar Nationals in Thailand, the number of registered Myanmar migrants is **2,308,166** and **51%** are women [@iomthailand_overview_2024]. We used  *Yamane's formula*:  

$$ n = \frac{N}{1+N(e^2)} $$   

where:  

-   n = sample size,  
-   N = population size  
-   e = margin of error  



With a margin of error 0.05, the required sample size based on the female  migrant population data (51% of 2,308,166) is **400**.

### References
