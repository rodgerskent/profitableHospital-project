## US Hospital Profitability
Extracted three years of hospital data from the Centers for Medicare & Medicaid Services. These data rich files provide revenue, net income and key operating information on more than 6,000 US based hospitals. Performed machine learning to identify the key drivers of net income performance and then built an interactive map and a series of performance dashboards to enable a hospital executive or department head to compare their performance to their peers. Key analyst actions included:
* []()Extracting multiple files (years) of data from data.cms.gov
* []()Built and ran a Google Maps API to append latitude and longitude information to support an interactive map
* []()Appended the certificate of need requirement status to each record so that performance could be evaluated on this highly debated topic
* []()Transformed the dataset through a series of steps adding 20 additional calculated fields to better evaluate and compare performance
* []()Ran four machine learning models and identified the one with the best predictive strength, i.e. logistic regression.
* []()Utilized recursive feature elimination (RFE) to rank and prioritize the key performance metrics that drive net income performance. Landed on seven (7) key performance indicators (KPI’s) that provided the optimal logistic regression score
* []()Built an interactive map in Tableau to provide quick access to high level information and foster user engagement with the data
* []()Built three interactive performance dashboards designed around the seven (7) highest ranked indicators identified in the RFE process and other closely related metrics

![Overview](https://github.com/rodgerskent/us-hospital-profitability/blob/main/overviewimage.jpg?raw=true)

## Check out the interactive map and dashboards:
On Tableau Public: [https://public.tableau.com/profile/kent.rodgers#!/]

The project details and workbooks are on Git Hub at: [https://github.com/rodgerskent/profitableHospital-project]

## Key Insights
The following key insights were brought to life in the assessment.
* []()The large variation in payor/contract rates and published Net Income definitions can be misleading. It is important to confirm if Gross or Net Patient Revenue is being utlized when evaluating a hospitals net income percent performance.  
* []()Whether a hospital (or surgery center) is subject to state certificate of need requirements does impact performance. The impact on net income percent is not statistically significant. 
* []()The predictive models can be made more accurate and efficient through the use of recursive feature elimination. 

## Reference Items & Data source
The key website where the main data was source is located at: [https://data.cms.gov/browse?q=Medicare%20Hospital%20Cost&sortBy=relevance]
