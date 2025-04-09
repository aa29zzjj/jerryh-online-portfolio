| [home page](https://aa29zzjj.github.io/jerryh-online-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Telling Story with Data -  Assignment: Critique and redesign
### Step 1: choose a data visualization from MakeoverMonday
I chose [Steam Top 100 Played Games](https://store.steampowered.com/charts/mostplayed) as my data visualization source from [MakeoverMondy](https://makeovermonday.co.uk/)

### Step 2: critique the data visualization
Rate each speciality in the original data visualization:
1. Usefulness.  Is it useful for the intended audience?  Does it communicate valuable information? 9 out of 10
2. Completeness.  Does the visualization have everything necessary to make it understandable? 7 out of 10
3. Perceptibility.  Can the reader understand the information with minimal effort? Is the visualization type appropriate?  Does it use illogical comparisons? 6 out of 10
4. Truthfulness.  Is the visualization accurate, reliable and valid?  Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisions that aren't correct? 10 out of 10
5. Intuitiveness.  Is it easy to understand and clearly communicates the information?  If unfamiliar, does it include easy to understand instructions on how to interpret it? 9 out of 10
6. Aesthetics.  It is interesting / enjoyable to look at?  Is it a good example of what a beautiful data visualization might look like?  Is it somewhere in the middle - pleasing but otherwise not distracting to look at? 8 out of 10
7. Engagement.  Does it lead the audience to learn more about the topic?  Does it inspire the audience to talk about the data or share it with others? 10 out of 10


8. Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't work well?

The popularity of Steam games are arranged by current players (good). However, we do not know what kind of the game can be more attractive to customers by the provide data (bad).

9. Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?

The primary audience of this tool will be video game players. The visualization is effective for them because they can review the current players of each game to decide which video games they would like to try.

10. Based on your critique, what do you think you'll try to focus on in your redesign?   Any ideas or inspiration for how you can make a better data visualization?  What are you excited to try next?

I will categorize the Steam Top 100 games by genre (e.g., team-based, single-player) and create a bar chart for each category to highlight which types of games are most attractive to Steam users. The popularity of each category will be represented by the number of current players for each game. This approach allows the audience to easily identify the top 3 popular games in their preferred type and view recommendations displayed on the chart. Overall, it helps viewers quickly access the information they’re looking for in a clear and visual format. Besides, the viewers who want to design games on Steam can figure out the market in which Steam is popular by graphics, which shows how many current players are in each type of game.

### Step 3: sketch out a solution - 2025 Steam Top 100 Played Games by Type
Thought:
I used Horizontal Stacked Bar Chart to present my data since this not only shows out the total current player in each game field.
To deal with the data of Steam Top 100 games, I divided the games into three categories:

1. Team-based: Required more than 2 players (for each team) to play. Competing with other team.
2. PVP: person versus person 
3. Co-op: No competition, cooperating with each player.
4. Single player: only 1 person can play the game.

Then, I calculate each category's current players to see what is the most popular category in Steam, showing out the name for games that contains a great number of current players.
By doing so, viewers can check what type of game is the most popular on Steam to check what kind of customers are attracted by Steam's games.
Otherwise, I will point out the top 3 games in each category, so it is also a good recommendation graphic for players.

[![Click to view the interactive Tableau dashboard](https://public.tableau.com/static/images/As/AssignmentCritiqueandredesignStep3/Sheet1/1.png)](https://public.tableau.com/views/AssignmentCritiqueandredesignStep3/Sheet1)

### Step 4: Test the solution
During the class, I show my graphic to my teammates to test if my solution works for them.
These are my teammates' feedback:
1. student A, MPM:
- I would like to see the separated data chart for each name of the game but not accumulated. This lets me easily see the distribution of the market.
For example: for the team-based game, do the top 3 games contain the greatest number of current players, or it is accumulated by other games?
- The color is not meaningful to me. I would suggest making meaningful colors for each bar chart.
- Maybe ratio works better than numbers?
  
2. student B, MAM:
- I would suggest doing it in Grouped Vertical Bar so you can present the market distribution well
- The topic label looks ambiguous to me since it doesn't show out the top 100 games in the graphic
- For the color, I would recommend using the meaningful color. For example, which one is top 1? 

### Step 5: Build your solution - 2025 Steam Top 100 Played Games by Type
After reviewing my teammates' feedback, I found that the Horizontal Stacked Bar Chart is not a good idea to present the data since this makes the viewers clarify Steam's market distribution.
Besides, the color is not meaningful to my graphic. I should use clear, understandable, obvious colors to separate each bar to let viewers clarify.
However, I do not agree that ratio (like a pie chart) will make the data visualization better since numbers may speak louder than percentages.
Last but not least, the topic name should be more accurate to viewers.

In the re-design graphic, I am more focused on the Steam market field distribution and the top 3 games in each field.
By doing so, my audience can get the following valuable information:

For video game players:
They can see the top 3 games in their preferred game field. It can be a recommendation manual for them.

For game designers:
They can see each game field's market to decide which game can attract the most customers in Steam. 
Besides, designers can check the market distribution in the graphic to make sure whether the current players in the field are combined with the Top 3 games.

Re-design step:
1. Use Grouped Vertical Bar to present the current players in each top 3 game in each field.
2. Arrange the bar by 1st, 2nd, 3rd popular game, and others, so it can let viewers easily verify the top 3 from the graphic.
3. use the same dividable color for the top 3 games, and use the same color for others in each field. By doing so, viewers can easily find out the top 3.
4. Change the graphic topic name to "2025 Steam Top 100: Current Player Counts and Top 3 Games by Genre" to make it more accurate.

Finally, a perfect graphic is completed:
Source: [Steam Top 100 Played Games](https://store.steampowered.com/charts/mostplayed)
Click the image to access the graphic:
[![Click to view the interactive Tableau dashboard](https://public.tableau.com/static/images/As/AssignmentCritiqueandredesignStep5/Sheet2/1.png)](https://public.tableau.com/views/AssignmentCritiqueandredesignStep5/Sheet2)
