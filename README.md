# P6: Make Effective Data Visualization
### by Laima Stinskaite

## Summary

A data set containing 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. Here I visualize some parameters that affects the performance of the baseball players. There are 2 plots on the page: first is the differences among the performance of the baseball players by Height and Home Runs, second - differences among the performance of the baseball players by Height, Handedness and Home Runs.

Warning: for better visualization and effects it is recommnded to use Chrome or Safari latest versions.

First plot: size of bubbles represents total number of Home Runs. On this graph you can notice that smaller players are better batting and medium players are more constant in their home run rates.

Second plot: color represents different type of handedness, size of bubbles - total number of Home Runs. Also this graph is interactive. You can choose what information you would like to see. If you click on the rectangle of handedness in the legend then appropriate chart will be hidden. On this graph you can notice that the best batting players are both-handed or left-handed players.

## Design

### Initial

Initially, after I decided what story I want to tell and what parameters I need to use for that (height of a player, batting average of a player and handedness), I began making one or two bubble, line and bar plots, compared them and chose to use bubble plot because it better represented quantitative data. I decided to add a line to the bubble plot to help highlight the trends. To let readers spot the trends of different handedness more easily, I used three different colors to represent the three types of handedness. I chose to use y-axis for the bating average, x-axis - for the height of a player, color - for the handedness. A legend for handedness was placed to the right from the graph. Hovering over any bubble would provide the mean average for that specific height and handedness.

### After first feedback iteration

After getting the first feedback, I added "Home Runs" to the graph as z-axis which represented size of the bubbles on the graph. I changed sizes of labels for both x- and y-axis, so  they became more visible on the page. I changed number of decimal signs for y-axis, so it shows correct values. I also expanded the values of handedness in the legend: from B to Both-handed, L to Left-handed, and R to Right-handed.

### After second feedback iteration

After getting the second feedback, I added a short description of my story (what information user can receive from this graph). I changed labels on the pop-ups when user hovers bubble. So these info became more user-friendly. Also, I decided to add adiitional interactivity on the graph. User can choose what info he\she would like to see. If user click on the rectangle of handedness in the legend then appropriate chart will be hidden.

### After third feedback iteration

After getting the third feedback, I added one more plot to the top of the page. This graph doesn't depend on the handedness property and only shows dependencies between height of a player, batting average and total number of home runs. Also I added titles and descriptions for every plot.

## Feedback

### First iteration

#### Feedback 1 (from my colleague)
- The legend says B, L, R. What do these abbreviations mean?
- The majority of mean batting averages are within 0.01 or 0.02 to 0.250.
- Since there's other variables such as weight and HR count, maybe try to play with them to get a better visualization.

#### Feedback 2 (from my colleague)
- Rename the legend labels, e.g. "R" becomes "Right-handed".
- Very tall right handed batters have rather low batting averages.
- Does anything else have an impact on the trend other than the height of the player?

#### Feedback 3 (from my friend)
- It will be interesting to see the trends of the players in each height group for the Home Run series.
- Smaller players are better at batting (at 67 inches value). Then, the higher the height, the smaller the average batting, decreasing smoothly to 74 inches.

#### Feedback 4 (from my soul-mate)
- Can we also know the trend of the average of the Home Run among different heights groups?
- The axis labels and fonts are small and hard to read.
- Something wrong with y-axis. It shows the same values several time. Is it OK?

### Second iteration

#### Feedback (from my colleagues)
- The information on the tooltips, for example "avg" not user-friendly and not easy-understanding for not math person.
- What is the meaning of the circles?
- It will be helpful to have a short summary about your visualization.

### Third iteration 

#### Feedback (from my colleagues)
- It is clear you want to show that left-handed are somewhat better at average.
- The relationship can be easily found from the plot.
- I like it! Your visualization is easy to understand, interactive by user and consists of short description about graph.

### Fourth iteration 

#### Feedback (from Udacity reviewer)
- Design choices are great. I like in particular:

Bubble chart choosing - great solution for such type of data
Header that catches the viewer attention
Introduction text and outcomes are provided at the project page - it makes the project more comfortable for the readers
Anyway, there is one item that should be improved still: as you focus only on a comparison of people height and HR/batting average - no need to separate data by player handedness by default. It is a great exploratory feature (remember martini glass principles?) but currently it takes the whole attention on it so it can confuse the reader a bit while he or she will explore your outcome. I suggest you two options for improvement (of course you can implement your own solution):

1) Implement handedness as a drop-down list with values left, right, both, total. Use total by default
2) reate one more chart with total values and move the current chart to the bottom of the page

## Resources

1. https://github.com/d3/d3/blob/master/API.md
2. http://dimplejs.org/
3. https://github.com/PMSI-AlignAlytics/dimple/wiki
4. http://colorbrewer2.org/#type=sequential&scheme=Greens&n=3
5. http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
