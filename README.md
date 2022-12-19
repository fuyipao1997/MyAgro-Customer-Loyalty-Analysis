# MyAgro Customer Loyalty Analysis
Colab link: https://colab.research.google.com/drive/10OkhEtAn_WmTMjr4Z1LMKXJbm02KzIre?usp=sharing
## <b> 1. Project Proposal</b>
Our goal is to determine if getting high yields makes a customer become more loyal to MyAgro products. Customer loyalty will be measured by customers’ re-enrollment dates, amounts of packages purchased, training attended, and payment dates in the following year. We will utilize exploratory data analysis and visualizations to analyze clients, sales, and harvest data provided by the MyAgro team to find insightful attributes and suggest them to MyAgro’s sales strategy and resource allocation.
## <b> 2. Report Summary</b>
In this notebook, we are using the harvest data from seasons 2020 to 2022, which includes yield data self-reported by the farmers or measured by MyAgro staff, joined with client data, payment data, and package data to identify clients with high yields, make observations of customer loyalty and how high yield clients' customer behavior differ from other clients.
  
*   We start by looking at all clients recorded, and from the data exploration stage, we reached the following observations: 
    1.   MyAgro is successful in attracting more new clients in 2022, and this trend is likely to continue in 2023 based on the current composition of season 2023's enrollment.
    2.   2021 season has the highest number of packages from 2020 to 2023.  Most clients who took the harvest survey order one package per year from MyAgro. There are also some bulk orders made. 
    3.   Mali's and Senegal's payment is increasing, since Tanzania is a pilot country, it has a relatively lower payment. Tanzania has empty records in the "harvest" table, so we will not conduct further analysis regarding its data.
    4.   Agriculture data such as planting machine used, fertilizers/compost applied, training attended and client ratings are used as variables to measure the yield for each crop. This can be blended with sales data to tailor and understand client yields and sales behaviors.

*   We then focused on clients with high yields in each country each season for each crop, analyzing their commonalities and their customer behaviors in the next season.
1. Amongst the data set of clients with high yield, we looked at the yield produced by different crops across country and season along with other factors such as trainings attended, most_recent_year_enrolled and staff_present_fertilizer. This had allowed us to have a better undertanding and insight so as to view the variations of yields for different crops. 

  1.1. In `2020`, riz and sorgho display the highest concentration of yield amongst their respective ranges when compared to mais, arachide and mil.

  1.2. In `2021`, all 5 crops display a fairly good concentration of yield amongst their respective ranges.

  1.3. Similar to 2021, all 5 crops seem to have an increadibly high concentration of yields amongst their respective ranges in `2022`.

  1.4. Crops such as `Riz` and `Mais` have an incredibly high concentration of yield amongst their respective ranges in both `Mali` and `Senegal`.

  1.5. `Sorgho` and `Arachide` on the other hand display a very high concentration of yield amongst their respective ranges in `Mali`.

  1.6. Meanwhile, `mil` only seems to be present in `Senegal` with a good concentration of yield.

2. From the data we have, in most cases high yields in seasons 2020 and 2021 did not lead to more purchases in the corresponding sales season 2021 and 2022. Furthermore, there is a 60% churn rate for clients with high yields in 2021 to leave the program in 2022.
3. After further research, we think the results can be explained by data inconsistency, inaccuracy, and price increase of fertilizers.

*   We hence can provide the following suggestions:
    1.  MyAgro can establish some incentives for farmers that are farming the crops or from countries that do not have as many responses as others. With current limits on the data, we are not able to look at trends among clients with multiple years of high yields, as we can only find 15 clients over the 3 seasons that have high yields in multiple years.
    2.  To improve the quality of data, MyAgro can emphasize more the importance of data consistency and accuracy to their local staff.
    3.  Based on the current analysis, MyAgro can review the clients that had high yields but left the program, or ordered fewer products in the next season, and look into the reasons behind this.
