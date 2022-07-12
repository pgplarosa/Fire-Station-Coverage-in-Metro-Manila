# Cathching Fire: Fire Station Coverage in Metro Manila

<p align="justify">Geospatial Analysis Final Project by Marvee dela Resma, Patrick Guillano La Rosa, Miguel Carlo Pingol, and Christian Alfred Soriano - December 13, 2021. Full report can been in the <a href="https://github.com/pgplarosa/Fire-Station-Coverage-in-Metro-Manila/blob/main/GSA%20Team%2014%20Final%20Report.pdf">Technical Report</a>. If you have any questions regarding this study, please send me a message via  <a href="https://www.linkedin.com/in/patricklarosa/">LinkedIn</a>.</p>

<img src="./outputs/banner.png" width=100% />

## Executive Summary

<p align="justify">In 2017, the Bureau of Fire Protection (BFP) in the Philippines reported a record high of the number of fire incidents in the Philippines that cost about 500 billion pesos. Metro Manila accounts for 32% of these incidents. In the Philippines, the ideal response time is 5 to 7 minutes.</p>

<p align="justify">Recently, President Duterte signed a BFP modernization act to strengthen and modernize the BFP that would include acquisition of modern fire equipment, expansion of manpower, provision of training for the firefighters and most importantly, building new fire station infrastructure. This study aims to help in creating insights on how to attack the current problems the BFP is facing.</p>

<p align="justify">The datasets that were used for this project were the OSM data, GADM data, and BFP data. The team conducted exploratory data analysis, and treated it as a facility location problem where we used two methods such as LSCP and MCLP.</p>

<p align="justify">With 3 km distance to the fire stations, using LSCP, the team found that only 85% of amenities were covered by the fire stations while  using MCLP with weights as the number of fire incidents over the number of amenities per municipality. The team got a coverage of 98% of the amenities. The team also saw that only 30 fire stations are needed to get a high coverage of the amenities which means that the placement of the fire stations are not that optimized.</p>

<p align="justify">In this study, we have presented two methods to solve the problem of the Philippine Government to assess the placement of fire stations around the nation to optimize their allocated budgets for fire safety to ensure that the Filipino people would be served in the times of emergency when they need it the most.</p>

<p align="justify">We found out that based on distance alone, there is a possibility of inefficient distribution of fire stations in Metro Manila while not reaching full coverage.</p>

<p align="justify">Lastly, this study can be further improved by using road networks to determine the distance for cost function, inclusion of residential data, and capacity of fire stations as constraints.</p>



