# Emily Hudson Data Visualization Project

## Introduction 

Volleyball is a complicated sport that requires the balance between an aggressive offense and solid defense. Finding training strategies that incorporate both of these objectives can be challenging. However, by studying the mindset, training and technique of the players in the Big Ten Division (one of the highest levels of volleyball in the country), we can find strategies that have been successful at creating a balance on the court. It can also be important to study teams that have imporved over the years by developing new training or recruiting strategies and helped them dominate in the league. 

## Data

The data I propose to visualize for my project is a NCAA Women's Volleyball Boxscore Dataset. There are 26 different attributes ranging from hitting percentage, number of aces, sets played and several others. The dataset can be found here: https://www.kaggle.com/datasets/tylerwiddison/ncaa-womens-volleyball-boxscores-20122019?resource=download&select=ncaa_w_boxscores_2012-2019.csv


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Is there a relationsip between final standings and hitting percentage or digs per a game? Or does making improvements in areas that are not tracked by statistics more important in terms of success (less unforced errors, mindset, new coaching staff, etc)?
 * Do players at certain schools improve their stats over time more dramatically than players at other schools? Do these schools that improve their athlete's hitting percentage quicker have a better standing in the conference? 
  

## Sketches

The first sketch I came up was during my initial brainstorm. It shows a visualization that compares hitting percentages across schools for multiple years. This visualization can be altered to show more than two years worth of data to help answer the question regarding other schools improving their player's performance more efficiently than others. Unfortunately, I did not end up moving foward with this sketch because it would be difficult to show all schools in the league over multiple years. This sketch could be successful at answering a question about a smaller number of schools over a larger time period. 

<img width="1596" height="1218" alt="image" src="https://github.com/user-attachments/assets/3d18de03-b5ed-4ec7-aefe-c1c90308ec6c" />

Another sketch that I created that is more dynamic and shows a second attribute of the data is attached below. It is a chart that has circles that represent each Big Ten school. The circles would start showing the average of each teams average digs per a game (X-axis) and average hitting percentage (Y-Axis) for 2012. The chart would dynamically change to show this data for each year until 2019. I ended up moving forward with this design because I felt that it answered the questions I was proposing the best. It allows for a user to easily see all of the schools and their stats for each year without it being too overwhelming. 

<img width="1548" height="564" alt="image" src="https://github.com/user-attachments/assets/71364adb-35f2-4904-a806-7f3d7e8b06d5" />

## Prototypes

My first step in moving forward with this project was to create a proof of concept visualization of this data. It's a scatterplot and it shows kills v.s. hitting percentage for players in the Big Ten Conference during the years 2012-2019. This visualization is fairly simple, but it serves as the first step toward the more advanced designs I outlined in my sketches. The purpose was to become familiar with using the VizHub platform and get some data onto the screen. At this point in the project, I was struggling with the volume of data in this CSV file. This was due to keeping all the information about individual players instead of grouping it by team because I was hoping I could do something that showed improvement by player. However, I learned quickly that this would not be feasible due to the number of players and games listed in the file.  

[![image](https://github.com/user-attachments/assets/45cb95e5-8833-4bf7-99af-da2e6be1917d)](https://vizhub.com/ejhudson33/cd2fcf9c405c4ffda0289e2c315575de)

Here is another prototype that I created that resembles one of my sketches more closely. It is a bar chart that shows average hitting percentage per school. Eventhough I did not go through with a bar chart for my final design, this prototype was important because I learned how to group the data by school.  For these iterations, I only chose the top 4000 lines of the CSV. I had not considered eliminating columns instead of rows at this point in my project development. 

[![image](https://github.com/user-attachments/assets/c073feba-37fd-417b-bb7d-d45f6070ecb7)](https://vizhub.com/ejhudson33/48c0a216565f489fb56cb74f4c3d60ce)

Here is the next iteration of my project that was the beginning of my final product. I created a scatter plot that shows average digs on the x-axis and average hitting percentage on the y-axis. This chart makes these calculations by grouping the data by school. You can also hover over each circle to see which school it is representing. After creating this original prototype, I knew that I wanted to move forward with this design. I also began to remove data fields that were not being used so taht I could select more rows of data.  

[![image](https://github.com/user-attachments/assets/fdd00e54-ee31-4a04-ba49-9e29af218982)](https://vizhub.com/ejhudson33/4f2e32f4551e42b281920e39476a553b)

For the next iteration of my project, I decided to add movement to the graph. If a user presses the 'Play' button, the points will move throughout the graph to represent data for 2017, 2018 an 2019. The points now have letters to represent each school as well. If you hover over one of the points, it will show the average hitting percentage and average digs for that season. I also removed the background color to make the visualization smoother.

[![image](https://github.com/user-attachments/assets/987a0954-0cdf-47a2-8993-1b30316c5fc6)](https://vizhub.com/ejhudson33/62c551490c8348e4a829fc3c8d3a466a?mode=embed)

My next iteration is similar to the past one, however, I worked on readability. I added lines on the chart to make it easier to see where each point lies as well as adjusting the scale of the x-axis. 

[![image](https://github.com/user-attachments/assets/b41e5191-8778-4e75-888d-42cbcc9eeddf)](https://vizhub.com/ejhudson33/15ca03d986b740ada71e3b29cfa5c819)

To add to the readability of the graphic, I decided to make the points on the graph less opaque so that it was easier to see schools that were overlapping. It makes it a little easier to read, but I also decided to add a legend so that a user can see the total list of schools. 

[![image](https://github.com/user-attachments/assets/a2f7129c-ebbe-4a91-80f3-f527c3e8c2fc)](https://vizhub.com/ejhudson33/5b49a3acdda64be5bb6eb06e828292f4)

After receiving peer feedback, I decided to make my finishing touches. This included making small code fixes to improve a bug with the pause/play button. One of my classmates found that the play/pause button stopped working after it was used once. This button was a critical part of the project because it allows the user to stop and analyze one year of data at a time. However, I was able to resolve this bug with a quick code fix, and it now allows for pausing more than once. 

## Conclusion 

Overall, I learned a lot during the process of completeing this project. While it is easy to create a simple bar chart or scatterplot, it was really interesting to find ways to represent as much information as possible without overloading the user. I knew that I wanted to allow for the user to interact with the vizualization which is why it was critical to add the pause/play button as well as the ability to hover over the points on the graph. If I were to suggestion improvements for future iterations of this project, I think it could be interesting to add a leaderboard on the side of the chart that shows the final standings for the season that is being shown on the scatter plot. I also think it could be interesting if the user could input a which years were shown on the chart. For example, it might be helpful to include drop down menus where the user could select the start date and end date. I am really happy with the result of this project and grateful for the feedback I received from my peers. 

