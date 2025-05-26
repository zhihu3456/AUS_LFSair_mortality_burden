# AUS_LFSair_mortality_burden
Landscape fire sourced-air pollution(PM2.5 and O3) related mortality burden and economic loss at community level in Australia from 2016 to 2019.

A shinyApp online can be accessed at https://qr5g6g-zhihu-xu.shinyapps.io/LFSairShiny/

after unzipping file, the csv file mainly including following variables:
region: Australia, States/Territory, SA2s
year: 2016,2017,2018,2019, 2016-2019
death: death number
pop: population
type: 
1. Total_ori: short-term burden + long-term burden(risk estimates from all-source air pollution)
2. Total_global: short-term burden + long-term burden(risk estimates from all-source air pollution but calibrated by global short-term ratios)
3. Total_aus: short-term burden + long-term burden(risk estimates from all-source air pollution but calibrated by Australian short-term ratios)
4. Short-term PM2.5
5. Short-term O3
6. Long-term PM2.5_ori: all-source association
7. Long-term PM2.5_global: all-source association but calibrated by global study
8. Long-term PM2.5_aus: all-source association but calibrated by Australian study
9. Long-term O3_ori: all-source association
10. Long-term O3_global: all-source association but calibrated by global study
11. Long-term O3_aus: all-source association but calibrated by Australian study
12. Short-term PM2.5+O3
13. Long-term PM2.5+O3_ori: all-source association
14. Long-term PM2.5+O3_global: all-source association but calibrated by global study
15. Long-term PM2.5+O3_aus: all-source association but calibrated by Australian study
an: attributable number
af: attributable fraction
amr: attributable mortality rate (per 100 000 residents per year)
vsl_us: value of statistical life at 2015 USD price
vsl_aus: value of statistical life at 2015 AUD price
