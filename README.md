# CallForCode-CleanWater2021
Technological prophecy of the biosphere- Visualizing insights on how the biosphere is impacting clean water.

## Description
### What's the problem?
Water makes 3/4th of our bodies and is the most threatened natural resource due to climate change. It is essential for life on the planet. According to the WHO, approximately 30% of the world's population does not have access to safe drinking water. But, what could be the reason behind this scarcity? The Biosphere. Our biosphere dictates how water is affected today and as a testament to that we have collected data from various sources to get the meaningful insights. 

### How can technology help?
If we analyze our ecosystem, we can see many prevailing factors like, Arable land, the changes in precipitation percentage over a decade and GDP deflation rates. Of these, country-wise analysis can help recognize the shortcomings in these sectors and help in the improved availability of clean water.

### The idea
With the industrial setbacks due to the COVID-19 pandemic, we were more dependent on machines, people and SME's experiences. The data collected through these and many other sources via [aquastat](http://www.fao.org/aquastat/en/) has helped us identify the culprits of our biosphere. Hereby, we have visualized some very critical insights backed by IBM Cloud and Watson Services which will enable us to bridge the gaps between vast inequalities in the accessibility, availability, and quality of the services. 

### Demo video
https://www.youtube.com/watch?v=03ynk_jeNXw

### Data cleaning
This notebook cleans the aquastat data of 200 countries and carves out the insights depicting the most impactful features leveraging the unsupervised machine learning techniques like PCA and T-SNE.

### IBM_clean_water_project_all_var_dim_years
Here, the dataset consists of various ecological factors as the features, and yearly distributed country data as samples. Firstly, we have applied Principal Component Analysis(PCA) to the data. Then, we have visualized the data into a lower dimension using T-SNE. Once the data was refined and a clearer picture was formed, clustering techniques were implemented to obtain country clusters. To improve the readability, instead of considering all the 193 factors, we have only considered those that have a high correlation with each other.

### IBM_clean_water_project_all_years
Similarly in this file, countries are treated as features and clusters were obtained for the ecological factors. This helped us in grouping the factors together based on a mathematical approach. Through this data, governments, activists or lawmakers can understand the impact of factors on each other better and this can also enable them to implement the "green policies" more efficiently.

### Conclusion
All the 3 notebooks can be used to provide meaningful insights to the government of different countries, so that the other ecological factors can aid in the improvement of clean water. The clusters have an expandable scope and can be used to improve a linear regression model by using cluster labels as independent variables and they can be also used to capture hidden ecological patterns between country groups. Thus, our idea can make a significant impact on the availability of water and its consumption.

### Results

![image](https://user-images.githubusercontent.com/38141850/127762172-7e0c5622-5838-4558-9bc1-ab4700b5afe6.png)

### Acknowledgments
IBM's Call for code, Aquastat and Python libraries.

## Getting started
### Pre-requisites
#### IBM Cloud Account:
1. Create a free IBM Cloud account with Lite subscription.
2. Utilize IBM Watson from the catalog.
3. Create/Upload the above notebooks and datasets(Assets).

## Built with
[IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handling logic
[IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - The ultimate suite of tools for infusing AI and Machine learning logic

## License
This project is licensed under the Apache 2 [License](https://github.com/BajajSmriti/CallForCode-CleanWater2021/blob/master/LICENSE) - see the LICENSE file for details.

## Contributors
[![](https://avatars.githubusercontent.com/u/30683141?s=100&v=4)](https://github.com/remarkablemark)
[![](https://avatars.githubusercontent.com/u/38141850?s=100&v=4)](https://github.com/remarkablemark)

- [Madhunil Anil Pachghare](https://github.com/Madhunil)- Master of Science in Data Science, Northeastern University- USA
- [Smriti Bajaj](https://github.com/BajajSmriti)- Master of Science in Data Science, Northeastern University- USA

