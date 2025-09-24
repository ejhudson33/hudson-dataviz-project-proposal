# Emily Hudson Data Visualization Project

## Data

The data I propose to visualize for my project is a NCAA Women's Volleyball Boxscore Dataset. There are 26 different attributes ranging from hitting percentage, number of aces, sets played and several others. The dataset can be found here: https://www.kaggle.com/datasets/tylerwiddison/ncaa-womens-volleyball-boxscores-20122019?resource=download&select=ncaa_w_boxscores_2012-2019.csv


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there a relationsip between final standings and hitting percentage or digs per a game? 
 * Is there a relationship between the starting lineups performance and outcome of the game? 
 * Do players at certain schools improve their stats over time more dramatically than players at other schools?

## Sketches

This sketch shows a visualization that compares hitting percentages across schools for multiple years. This visualization can be altered to show more than two years worth of data to help answer the question regarding other schools improving their player's performance more efficiently than others. 
<img width="1596" height="1218" alt="image" src="https://github.com/user-attachments/assets/3d18de03-b5ed-4ec7-aefe-c1c90308ec6c" />

Another sketch that I created that is more dynamic and shows a second attribute of the data is attached below. It is a chart that has circles that represent each Big Ten school. The circles would start showing the average of each teams average digs per a game (X-axis) and average hitting percentage (Y-Axis) for 2012. The chart would dynamically change to show this data for each year until 2019.  

<img width="1548" height="564" alt="image" src="https://github.com/user-attachments/assets/71364adb-35f2-4904-a806-7f3d7e8b06d5" />

Another version of this chart could show the average change in their players hitting percentage or digs per a game. This chart would only take in consideration players who have been on the team for at least 2 years. It would average the difference between each player's most recent hitting percentage and the previous year.This would indicate whether players, on average, show an improvement or decline in hitting.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a scatterplot and it shows kills v.s. hitting percentage for players in the Big Ten Conference during the years 2012-2019. This visualization is fairly simple, but it serves as the first step toward the more advanced designs I outlined in my sketches. It can be seen below.

[![image](https://github.com/user-attachments/assets/45cb95e5-8833-4bf7-99af-da2e6be1917d)](https://vizhub.com/ejhudson33/cd2fcf9c405c4ffda0289e2c315575de)

Here is another prototype that I created that resembles one of my sketches more closely. It is a bar chart that shows average hitting percentage per school. In future iterations, I would like to parse the data not only by school but by year similar to my sketches. I also need to go back to the original CSV file and pull all data for Big Ten Schools. For these iterations, I only chose the top 4000 lines of the CSV. 

[![image](https://github.com/user-attachments/assets/c073feba-37fd-417b-bb7d-d45f6070ecb7)](https://vizhub.com/ejhudson33/48c0a216565f489fb56cb74f4c3d60ce)

## Open Questions

One fear that I have is that the CSV file from Kaggle contains more than just Big Ten data and it is quite large. I am worried about being able to extract only teams that are in the Big Ten Conference before putting the data into DataViz. One I have the data laoded, I am confident that I will be able to manipulate it how I need. 


## Milestones

I hoping by the beginning of October, I am able to filter the original CSV to only contain Big Ten schools and have it imported in DataViz. In October, I hope to get the basic design completed as well as any moving/dynamic parts completed. For November, I hope to finalize any details of the visualizaion that I did not complete in October and begin the writing process. 
