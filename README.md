# ForecastedLifeExpectancy
AIM: To forecast the distribution of ISU Alumni Population Profile based on different age groups in 2050

This project focuses on the analysis and prediction of the alumni population profile from Iowa State University in 2050. The research problem was posed by the Associate Vice President, Information Technology and Donor Compliance Services, Iowa State University Foundation, Rosa Unal. ISU Foundation was interested in knowing the ages of ISU living alumni by age group, to the year 2050, so that they could use this data for estimating the future donations and also plan out their future fundraising campaigns. They had a huge database of ISU’s Alumni collected since the year 1872. However, they were lacking the expertise to make meaningful predictions out of that data. Hence, to resolve the unanswered questions that ISU Foundation had, the first milestone was to predict the total number of Alumni that ISU will have each year starting 2017 to 2050. Second milestone was to find out the number of Alumni that would be deceased by 2050. Three different types of forecasting models, Exponential Smoothing, Holt’s Trend Forecasting and, Autoregressive Forecasting, were created to predict new alumni each year from 2017. This analysis also involved the use of two third-party datasets. First, the enrollment data which was utilized to estimate the instate ratio. Second, life expectancy by birth data of the US to make assumptions about the life expectancy of the ISU alumni. Iowa State University’s alumni were categorized into 4 sub-groups: Instate Male, Instate Female, Outstate Male and Outstate Female. Various simulations to predict the sex ratio and the instate ratio for the year 2017-2050 were performed. This project highlights on how to forecast future trend by making reasonable assumptions on the current data and the publicly available data. It was expected that margins of error would increase as the time frame for projections is increased.

The data included records of 283,400 alumni, who graduated from Iowa State University since the year 1872. It had 9 attributes - ID, BITRTHDATE, FIRSTDEG, DEGREECOLLEGE, DECEASED_IND, DECEASEDATE, Gender, Place_Of_Origin, and Ethnicity. ISU Foundation was interested in knowing the projections of the ages of ISU living alumni by age group, in the year 2050, using the current information. It was a challenging problem as the data consists of a lot of missing, unknown and inconsistent values. This would limit us in diversifying our predictions. 

In order reach our landmark of predicting the Iowa State University Alumni Population Profile by the year 2050, we needed to seek answer to a lot of questions:

•	What does the data tell us about the past enrollment and graduation rates at ISU?

•	Are there any patterns?

•	Are there any possible sub-groups within the ISU alumni population?

•	How can we study the life expectancy of the ISU alumni based on these sub-groups?

•	Is there a need of any third-party datasets? If yes, what kind of third party datasets might be needed to fulfill the gap left by the original data?

•	What kind of assumptions need to be made while generating forecasting models?

•	How do we choose the most efficient model to forecast the alumni in the upcoming years?

•	Are there any key determinants that would drive our forecasting results?

A mix of available modern day analytical tools were used to answer these questions. Results obtained should help ISU Foundation in setting up a realistic funding targets based for each upcoming years. This would eventually impact every experience at Iowa State University - from funding scholarships for young men and women who will become tomorrow’s leaders, to advancing knowledge through faculty teaching and research, to maintaining programs and facilities that provide an unparalleled education.

Environment: SAS, MS Excel, IBM Watson Analytics
