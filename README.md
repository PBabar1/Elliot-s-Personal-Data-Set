# Professional Tennis Serve Rankings
## Motivation
As someone who comes from a family of people who all play tennis, naturally I ended up playing tennis throughout highschool. I had the idea of Tennis statistics since I had never looked at sports statistics before, and I was curious what metrics they used to determine questions like: "Who is the best Server?"
## Data Process
I got my data from the ATP Tour Website (https://www.atptour.com/en/stats). Under the 'Serve Leaders' column, I downloaded the data and uploaded it into Excel. In terms of cleaning the data, I had to delete each of the players' pictures that came with their row in the data, and I had to change all of the columns that were talking about percentages, like "%1st Serve," from whole numbers with a percentage sign, to decimals, so that it would play nicer with Python. 
## Visualization

![Professional Men's Tennis Serving Statistics](https://raw.githubusercontent.com/PBabar1/Elliot-s-Personal-Data-Set/master/ProTennis%20Visualization.png?token=ARFIEI2E6X5U7HMYAU35ABS7US2GS)

This figure shows the Serving Statistics for the top 83 servers in Professional Men's tennis over the last year (Ranked from 1 to 83 from left to right). I decided after looking at levels of correlation, looking at these players' ranks relative to their percentage of points they win, when they start a point with their first serve. The big noticeable outliers, like Milos Raonic (Serve Rank #2), have a percentage of first serve points won, but his first serve accuracy is almost 10% lower than John Isner's (#1). Generally the outliers we see might be really good on this particular graph, but their overall serving rank suffers from other aspects.  

## Analysis
I wanted to look at how each of these top players' serving rank was related to what percentage of first serve points they had won. While the comparing a colu..While there are some outliers in this graph, those can be reasonably explained.
