# ACM Research coding challenge (Fall 2022)

Hello! For my coding challenge I decided to answer two separate questions. The first half of my response is supposed to answer how people's taste in cars differs between states. The second half of my response is supposed to answer which colors of cars are most expensive

## Part 1 - How do people's taste in cars differ between states?

For this part, I wanted to figure out how people's taste in cars differ between states. First, I filtered the list to find the top 75% of the most highly rated and commented cars, to see which cars are most liked by people in the US as a whole through the use of Bayesian rankings to calculate each cars weighted ranking. Afterwards I made a list for the attributes of the car I wanted to see the preferences of (Year, Make, Model, Drivetrain, Maximum MPG, Minimum MPG, Fuel Type, Transmission, Engine, and Mileage). Then through the use of for loops, the code will loop through every state and find all the cars in that state. Then using .value_counts I found the most popular attributes in the list of the highest rated / most commented cars and printed them out for every state. Although it works, some states don't print out any attributes, which will be something I have to work on

## Part 2 - Which colors of cars are most expensive?
For this part, I wanted to graphically figure out which cars are most expensive. First I made a function that will simplify the colors of the exterior colors dataset by taking out all the complex colors and classifying all the colors into simpler color groups (red, black, white, blue, green, brown, orange, yellow, gray, and other). Next I converted the price dataset from an object to an int by taking out all commas and question marks and assigning it to int. Next using colors as the independent variable and price as the dependent variable, I graphed a boxplot that will find the meding price of a car for each color and bar graph that displays the mean price of a car for each color. My code found that the most expensive average mean price of a car is yellow, followed by other colors and black. My code also found that the most expensive average median price of a car is yellow, followed by white, black, and other. 

## Citation
Here are all the sources of code I used / took heavy inspiration from. Mpst of my information came from ACM and Stack Overflow. 
1. https://www.kaggle.com/code/alexandernchin/acm-research/notebook
2. https://www.kaggle.com/code/kll505/acm-coding-challenge#Color-Analysis
3. https://stackoverflow.com/questions/63364949/how-to-plot-a-bar-plot-of-mean-value-by-category
4. https://www.geeksforgeeks.org/analyzing-selling-price-of-used-cars-using-python/
