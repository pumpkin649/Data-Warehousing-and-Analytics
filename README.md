# NYC Dog Park Optimization Data Warehousing and Analytics
- Authors: Sao Fong Leong, Jiehui Chen, Geyao Shuai and Rongnan He
- Date created: 05/05/2022
- Class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were:
1. For data integration - Excel
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for the project:
Since the start of the pandemic, people have faced more stress than ever. Many people decided to have a dog who could provide companionship during this difficult period. With more dogs living in the city, NYC dog parks' locations & sizes should also be updated in order to satisfy people's needs.

Description of the issues or opportunities the project will address:
The increasing number of dogs also triggered a series of social conflicts, such as the impact of dog walking on urban public places, and the harm caused by hounds to humans. So increasing the number of dog parks is imperative.

Project Business or Organization Value:
Enough dog park provides independent activity space and necessary sanitary facilities for dogs, allowing dogs to run freely, and also giving dog owners outdoor space to get along and communicate with dogs. For non-dog owners, it can reduce the chance of encountering dogs in public spaces and avoid safety hazards. 

Data Sources:
1. NYC Dog Licensing: https://data.cityofnewyork.us/Health/NYC-Dog-Licensing-Dataset/nu7n-tubp
2. NYC Parks Dog Runs: https://data.cityofnewyork.us/Recreation/NYC-Parks-Dog-Runs/8nac-uner



### Business Requirements Definition

List of Data Warehouse KPI's:
- 1.Dog license registration trend
- 2.Dog licenses by borough
- 3.Dog parks by zip-code
- 4.Zip code areas without dog parks
- 5.Dog parks acreage by boroughs


### Dimensional Model

This project's Dimensional Model consists of "dog_license & dog_park" Facts, and "License_info, Animal_info, Location, Park_Name, Park_info" Dimensions

![Alt text](https://drive.google.com/uc?export=view&id=1ZDBdNYcHzo6_L7Mo_b0qVeeoZrdGIKb6)

This project's Kimball Bus Matrix:

![Alt text](https://drive.google.com/uc?export=view&id=1efF-os6OJcY7U8mIBn_pavTKf3es8ZdZ)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Line Chart for comparison of the dog license registration trend
2. Pie Charts for displaying the dog licenses by borough
3. Map for displaying dog parks by zip-code 
4. Treemap for displaying the zip code areas without dog parks
5. Packed bubbles for displaying dog parks acreage by boroughs

Picture of BI Application Wireframe design/final Dashboard:

![Alt text](https://drive.google.com/uc?export=view&id=1Nh2IsYjkGKBUzEnQcchjlC11CmSbC846)

### Deployment

The project was deployed on Tableau Public: https://public.tableau.com/app/profile/jiehui.chen/viz/cis9440-finalprojectmilestone4/Dashboard1?publish=yes 
