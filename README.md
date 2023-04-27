# Data Visualization Project

## Data

The data I will use is the historical performance for each team in NBA league until 2017 seaon. My dataset includes the winning rate for each team in each season. And I need to organize these data, and calcualte the average winning rate for each team in a certain period, like three, five, or ten years. In my project, I will compare the recent winning rate and historical winning rate for each team to show their performance comparison.

## Prototypes

I’ve created a proof of concept visualization of this data. In this visulization, it shows two intersecting axis, which shows the recent winning rate and historical winning rate. This spite the graph into four differnent areas, and each area shows differnent performance. I think that will be clear to observe each team's performance. I will also replace these circles with differnent team's icon. 

![pro1](https://user-images.githubusercontent.com/54642539/220192532-59c55587-2c54-40f6-bef2-1e6389ca06b4.png)
https://vizhub.com/wqygod/522246578b554f16996616b62d981db3 (viz link)

I also hope to implement another function, if users click on the icon of the team, they can view the historical performace for that exactly team, this will shown as a Scatterplot. This graph focus on the genera winning rate situation for each team. 

![Pro2](https://user-images.githubusercontent.com/54642539/220193445-912b1656-24ea-4ab1-adfa-805310226906.png)
https://vizhub.com/wqygod/52a31dcbdbf94f58b8ec75bcb3386bb5 (viz link)
## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which teams did well in this season (2017-2018) and recent 5 seasons?
 * Is it possible to predict the state of the future season through the record in recent 5 years? 10 year?
 * Can a team with a poor record quickly improve its winning percentage through the draft?
 * Macroscopically observe what affects the team's winning percentage.

## Sketches

In the first iteration, I draw several graphs and finally decide to use this one which is very similar with the first visualization graph. This will be the base sketch of the project.

![ske1](https://user-images.githubusercontent.com/54642539/220195827-14c1d29f-0b2b-4346-a344-a3f418e77dae.png)

In he second iteration, I try to add more interaction in the project. I add three filters to pick recent 3, 5, and 10 years performance. And I try to use connected line to show the change on each team, I think this can compare the performance change easier.

![ske2](https://user-images.githubusercontent.com/54642539/220196033-270390f0-c88f-46bc-897e-6a30386d4198.png)

## Open Questions

I think the hardest part in my projrect is to add differnent interaction. Like my second part thinking is to let users click on each team to show a ttoally different data, I am not sure if this is possiable or able to implement. I will try to implemnt it, but I already excepted there will be many problems. So this is the point I am concerning about. 

## Milestones

Week 7 - Orgnize currect dataset to put differnent data into differnt set. 

week 8 - Put real data into intersecting graph and test problems.

week 9 - Put each team's icon into graph, and calcualte winning rate in different periods

week 10 - Put different period performance together

week 11 - Add filter into graph and test the interaction of the graph

week 12 & 13 - Add click function into graph and test all functions

week 14 - Implement the connected line(is possiable), final visualizations
