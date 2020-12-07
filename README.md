# PersonalDataSet
# Motivation
For my personal Data Set, I looked at the apparent magnitude of the closest nearby stars to determine what was the most common star type in proximity to our solar system and the rate at which they were moving away from us. This was important to me because as someone who wishes to pursue astrophysics it is important to know what our nearby neighbors consist of and if we can make connections to our own solar system. Also one day these stars will no longer be visible to use by the naked eye since our universe is ever expanding. To be exact the universe expands at a rate of 72 kilometers per second per megaparsec, a megaparsec is a measure of distance that is roughy 3.3 million light years. Meaning that for every megaparsec the star is away from earth, it moves 72 kilometers per second. 

# Data
I obtained my data from Space.com where they created a visual of the data from NASA's database about the magnitude and distance of the nearby stars. Then to obtain the expansion rate, I created a formula in excel, that used the light years divided by a megaparsec and multiplied by 72 kilometers to get the expansion in km per sec. However, because those numbers were so small, I multiplied by the number of seconds in a year, 31536000 seconds, to get them in km per year To be able to get the scatter plots to work correctly I revised the data so that the magnitude of brightest was on a number scale instead of using the letters from the Morgan-Keenan scale, with 1 being the brightest and 9 being the coolest. The brightest stars typically consist of hypergiants, supergiants and white dwarfs, where the coolest typically consists of red and brown dwarf stars. 

# Visualization
![Magnitude of Stellar Brightness](https://raw.githubusercontent.com/tamikataylor/PersonalDataSet/master/Magnitude%20of%20Stellar%20Brightness.png)

To begin with, I created the first visualization to show the most common type of magnitude that surrounds us. In this case it is the Red Dwarf which is the same type of star that we orbit. For this visulaization I looked at the brightest star in each solar system because some contained more than one. 

# Analysis 
![Expansion Rate of Nearby Solar Systems](https://github.com/tamikataylor/PersonalDataSet/blob/master/exp%201.png)
![Expansion Rate of Nearby Solar Systems](https://github.com/tamikataylor/PersonalDataSet/blob/master/exp%202.png)

The first diagram shows the rate of expansion of each solar system, where the second one look at the rate of expansion over the solar systems distance in terms of light years. The first one can be misleading since we know that expansion happens linearly, at a constant rate, not logrithmic as the first one suggests. 

# Source
https://www.space.com/18964-the-nearest-stars-to-earth-infographic.html
