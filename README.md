# VAERS Data Mining 
# Abstract 

## Objectives: 
(i) to implement three mainstream signal detection methods
(ii) to implement clustering and stratified PRR to deal with confounding
(iii) to compare drug-symptom pairs that are highlighted by PRR, for both unstratified and stratified data

## Methods: 
We applied PRR, ROR and  BCPNN data mining methods to data from the US Vaccine Adverse Event Reporting System (VAERS), and aggregated the results. We stratified PRR by age and sex using 2 clustering methods. To study the effects of stratification, we compared the unstratified PRR and stratified PRR
## Results: 

The signal detection results from these methods were somehow similar, but different in the ranking details. Therefore, an aggregated list of top signals based on distance metric optimization were generated. The final result of the aggregated top-ranked vaccine-event pairs showed that the majority of the detected signals were from Moderna COVID-19 vaccine, and half of the symptoms occurred at the vaccination site, which are basically similar to other vaccines that have already been widely used. Some of the detected signals are found to be mainly due to human errors or logistical issues, which indicates the need to improve the vaccine administration process in the future. Data quality issues are also implied by signals as well. Our findings may help guide improvements in future reporting data quality and data ingestion process.

Stratification not only changed the number of vaccine-event pairs that were highlighted, but it also changed which pairs were highlighted. There were 637 vaccine-event pairs that were highlighted by the unstratified PRR; 222 that were highlighted by the stratified PRR; and 190 that were highlighted by both. In addition, applying different clustering methods produces similar results with regards to the most significant drug-symptom combinations. 
