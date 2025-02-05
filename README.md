# COVID-19-US-Dashboards

In today’s world, Business Intelligence, or BI as it is better known, is a keyword in the Industry. Business Intelligence deals with the leveraging of tools and techniques to gain insightful insights from raw data by means of mining the data, visualizing the data, creating infrastructure to mange the data and providing guidelines to businesses as to how this information can be used to make data driven decisions. [5]
BI tools such as Tableau provide the means to convert data into meaningful visualizations and dashboards that convey important information about the data in a way that is quick and easy to understand.
For this project, we wanted to perform a comparative study on the visualization features and ease of use of two of the most commonly used BI tools – Tableau by Tableau Software (acquired by Salesforce in 2019), and Power BI by Microsoft.

To properly compare the features of Tableau and Power BI, we thought it would only be fair to use data that has not been overly used before. The world is currently dealing with the spread of a pandemic named “Coronavirus Disease 2019” (abbreviated “COVID-19”), caused by the virus named “SARS-CoV-2” [1]. The propagation of this virus has been documented by State bodies across the world that share the numbers with the public. The Center for Systems Science and Engineering (CSSE) at Johns Hopkins University (JHU) has been collecting this data and providing it to the public for use in analysis and research [2].
Initially, we looked at obtained the data directly from the JHU COVID-19 repository on GitHub. However, both Tableau and Power BI announced the availability of datasets that have been cleaned and targeted towards analysis in their respective tools and we decided to use those datasets for this project.
The Tableau COVID-19 case data was accessible through a Web Data Connector from data.world where the data is refreshed every evening at 10 p.m. PT.
https://tableau.data.world/?dataset_name=covid-19-data-resource-hub%2Fcovid-19-case-counts&query=SELECT%20*%0AFROM%20covid_19_cases&queryType=SQL
The Power BI dataset was available as online Web Data Connector from USA Facts which aggregates data from the Centers for Disease Control and Prevention (CDC), state- and local-level public health agencies and the data is updated daily at 10:30 PM Pacific Time.
3
https://usafactsstatic.blob.core.windows.net/public/data/covid-19/covid_confirmed_usafacts.csv
Since there are already a couple of websites that are providing data on a worldwide basis, we decided to focus our analysis on the propagation of cases within the US.

The Tableau Dashboard can also be viewed on Tablea Public at this link - https://tabsoft.co/2ZiiQsw

![Tableau Dashboard Image](https://github.com/5amue1/COVID-19-US-Dashboards/blob/master/Tableau%20Dashboard%20Image.png)







References:
[1] CDC. (2020, February 11). Coronavirus Disease 2019 (COVID-19). Centers for Disease Control and Prevention. https://www.cdc.gov/coronavirus/2019-ncov/index.html
[2] Home. (n.d.). Johns Hopkins Coronavirus Resource Center. Retrieved May 11, 2020, from https://coronavirus.jhu.edu/
[3] maggiesMSFT. (n.d.). Ways to share your work in Power BI - Power BI. Retrieved May 11, 2020, from https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-how-to-collaborate-distribute-dashboards-reports
[4] Sharing Workbooks with People Who Don’t Have Tableau Desktop | Tableau Software. (n.d.). Retrieved May 11, 2020, from https://kb.tableau.com/articles/howto/sharing-workbooks-without-tableau-desktop
[5] What is business intelligence? Your guide to BI and why it matters. (n.d.). Tableau Software. Retrieved May 11, 2020, from https://www.tableau.com/learn/articles/business-intelligence
