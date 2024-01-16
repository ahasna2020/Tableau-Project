> # Final-Project-Tableau

## Project/Goals

This project is a study of global death data using the datasets provided by "Our World in Data" using Tableau as the data analytics and visualization tool. The following are the main goals of this project:

-   Turning data into easily consumable visual insights, using Tableau
-   Creating impactful dashboards that help stakeholders make decisions, based on business questions
-   Communicating insights with the correct visualizations

## Process
In order to try and answer the above questions, the following are the steps that were followed:

1. Referred to [this](https://www.kaggle.com/datasets/ivanchvez/causes-of-death-our-world-in-data/data) page on Kaggle to review and download the "Causes of Death - Our World in Data" dataset.
2. Did further exploratory data analysis of the files to determine reliability of data. Performed data cleanup where country information was ambiguous for some parts of the dataset (20222703 Causes Of Death Clean Output V2.0.csv). Also, created a new date field in the data set to be able to generate time series data for analysis.
 - [ ] The file had United States and America as country information. These were merged to United States after reviewing the data.
 - [ ] The year column came in as string. Used makedate() function in a calculated field in Tableau to convert it into a proper date column.
4. Started high level data analysis by plotting visualizations over several Tableau worksheets to study the data and develop inference.
5. Each visualization and inference led to the next visualization and resulting inferences. 
6. As a next step, dashboards were created using the visualizations that were developed.
7. As a final step a Tableau story was created by utilizing the dashboards created with ample explanations on the inferences made.

## Results

For this analysis, Option 2 was chosen. The dataset chosen was "Causes of Death - Our World in Data". The dataset is available from the Kaggle website: [Cause of Death - Our World In Data](https://www.kaggle.com/datasets/ivanchvez/causes-of-death-our-world-in-data?resource=download).

The following sets of visualizations were created to understand the data trends:

1. High level death data analysis by countries to identify the death counts by country.
2. Death count trend over the years and forecast. 
3. Death count analysis by cause and by country.
4. Study of Percentage contribution of different causes of deaths.
5. Death cause trend analysis by country and leading causes.
6. Death cause trend analysis by least impactful causes.
7. Cluster Analysis of death data.

Using the above visualizations, dashboards were created and in turn those dashboards were used to create a data story in Tableau to answer the following questions:

The following were the data questions prompted by each stage of data analysis. 

 1. Which are the countries with most deaths in the world?
 2. What is the forecasted death counts and trend?
 3. What are the leading causes of death in the countries with top death counts?
 4. What are the causes that contribute the least to deaths?
 5. What inferences can be drawn from the analysis?
 6. What story does the data tell us?
 7. Where should governments spend more funds to improve the lifespan of their citizens?

As a conclusion to this project, the Tableau Story was developed to share the inferences and answers to above questions.

## Challenges 
1. I initially started off with Option 1, however, at a certain point, the data provided started to present challenges as I could not find specific information I was looking for. I also felt that answering pre-prepared questions curbed the opportunity for me as a data analyst to study data, draw inferences and create my own questions based out of research. So I decided to move on to Option 2.
2. Study of death data sounded intriguing, so I decided to go for the "Causes of Death - Our World in Data" analysis. I initially downloaded only the flat data set (as I overlooked the other cleaned data set) and this presented challenges in my analysis. However, on probing further, I realized another clean data set was available, which I then used for the rest of my analysis.
3. The country information was ambiguous for some parts of the dataset (20222703 Causes Of Death Clean Output V2.0.csv) where United States and America appeared as separate countries. The data was merged after carefully reviewing the data.
4. There was no specific date field in the data, which was vital for my analysis. Therefore, I added a calculated date field in Tableau to help with the analysis.

## Future Goals
If I had more time, I would have liked to do the following analysis:

 1. Dissection of data to study death trends in different continents.
 2. Study death cause trends in first, second and third world countries.
 3. Study of countries with improvement in death trends.
