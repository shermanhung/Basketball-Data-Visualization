# Basketball-Data-Visualization
We are still in the process of finishing this project, therefore please keep in mind that the visualizations displayed here are far from finished. A lot of changes will be made in the future. I will attempt to given an detailed explanation of each visualization here: 


## GameClock
![gameclock](https://cloud.githubusercontent.com/assets/25786510/24466719/6bf51d86-14e4-11e7-8cde-3dcbf2cc13ad.png)


GameClock allows coaches to analyze a single basketball game on a play-by-play level. Please note the source of the data is play-by-play     data merged with SportsVU data, that is why we were able to obtain the location of each play that takes place during a game.

The x-axis represents the time of a single game. The left starting point represents the beginning of a game, and the right ending point represents the ending of a game. Notice that this visualization is split into four quadrants, where each quadrant represents one single quarter. 

The y-axis represents distance away from the basket in feet raning from 0 to 30. Also notice that the visualization is split into two segments: upper half and bottom half. Upper half represents the home team, and bottom half represetns the away team. 

You will see a lot of symbols attached with a line on this diagram. Each symbol represents the kind of play that takes place during a game. The definition of each symbol is shown on the very top of the visualization. Each line and symbol are colored coded in red or green. Green means a positive play, and red means a negative play. For example, the first green line with a circle labled 1 in the upper half means the home team scored 1 point. 

## PlayerStream
![playerstream](https://cloud.githubusercontent.com/assets/25786510/24466792/b5cf291a-14e4-11e7-94f1-5f158281b06f.png) 


PlayerStream also allows coaches to analyze a single baskebtall game, but from a different perspective. The data source of this visualization is the same as the one used in GameClock.
  
The x-axis represents the time of a single game. The left starting point represents the beginning of a game, and the right ending point represents the ending of a game.
  
This visualization is split into three segments: upper half, middle, and bottom half. The upper half represents the home team. The middle represetns the scores of the game. The bottom half represents the away team. Each stream represents a player on respective team. The thickness of the stream represents the impact of each player at specific point in time. Notice that each stream has a different color, thus making it easier to differentiate among different players. The bar chart in the middle shows which team team is leading at any specific point in time, and also by how much that team is leading.

## CourtChart
![courtchart](https://cloud.githubusercontent.com/assets/25786510/24585530/4700f080-17bf-11e7-96a5-03facabd4fcc.png)

CourtChart is an animation that allows coaches to analyze the spacing and location of players during a basketball game. The animation shows the positioning the players and the ball on the court in each basketball play. More importantly, it shows the trajectory of the movement of each player. The data source of this visualization is from SportsVU data. SportsVU is a camera system that is installed at the top of an arena. It captures the X,Y positioning of players and X,Y,Z positioning of the ball. 


