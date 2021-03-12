## Profitable Hospital Project 
Extracted three years of hospital data from the Centers for Medicare & Medicaid Services. These data rich files provide revenue, net income and key operating information on more than 6000 US based hospitals. Performed machine learning to identify the key drivers of net income performance and then built an interactive map and a series of performance dashboards to enable a CXX of a hospital to compare their performance to their peers. Key analyst actions included:
* []()Extracting multiple files (years) of data from data.cms.gov
* []()Built and ran a Google Maps API to append latitude and longitude information to support an interactive map
* []()Appended the certificate of need requirement status to each record so that performance could be evaluated on this frequently argued dimension
* []()Transformed the dataset through a series of steps adding 20 additional calculated fields to better evaluate and compare performance
* []()Ran four machine learning models to determine which model would provide the best predictive strength. Ultimately landing on logistic regression.
* []()Utilized recursive feature elimination (RFE) to rank and prioritize the key performance metrics that drive net income performance landing on seven (7) KPI’s that provided the optimal logistic regression score
* []()Build an interactive map in Tableau to provide quick access to high level information and foster user engagement with the data
* []()Built three interactive performance dashboards designed around the seven (7) highest ranked indicators identified in the RFE process and other closely related metrics


## The project files and Tableau output are located at:
The project git hub site: [https://github.com/rodgerskent/profitableHospital-project]

The Tableau presentation is located at: [https://public.tableau.com/profile/kent.rodgers#!/]


## Key Insights
The following key insights were brought to life in the assessment.
* []()It is important to confirm the presenters definition of Net Income Percent if a topic of discussion. Net Income Percent is very different depending upon whether Gross Revenue or Net Patient Revenue is utilized to calculate. This is due the wide range of payor contracts and the high discount structure. 
* []()Having an exception to or a requirement for a certificate of need does not appear to be a key driver of net income performance. In general hospitals operating in states that require a certificate of need perform better on some metrics this does not necessarily translate to enhanced net income performance. 
* []()The predictive models can be made more accurate and efficient through the use of recursive feature elimination. 

## Reference Items & Data source
The key website where the main data was source is located at: [https//data.cms.gov/browse?q=Medicare%20Hospital%20Cost&sortBy=relevance]
