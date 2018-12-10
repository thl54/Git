# Git
ESSEC WORK
Gaëtan Gilles & Thibault Lavaine

We imported a csv file (villes_france.csv) that contains among others, the names, the population, the altitude of the 36,000 French towns. 

Thanks to our Python skills in Data science, we managed to create an algorithm that gives the number of inhabitants above and under an altitude, and the mean above and under that altitude.

We used Pandas and Numpy libraries as well as datetime and colorama.

First, we gave names to each of the 27 columns of the file. 
Then, we created functions to copmpute the number of towns above and under the chosen altitude, the mean of the population, and its sum.
We used several methods such as .sum, .mean, .format, .CYAN and functions like int.
To avoid ValueError, we also created a Try loop which makes the algorithm user friendly when the mean computation is not possible.

Then come the loop of the program : we ask the user the altitude he/she has chosen and then give all the answers, using the functions previously explained.

As we are only 2 in the group and completely new to Python, this algorithm was already quite an achievement and we did not have the time to learn HTML and CSS to build a front-end with Flask, but no doubt we will study these languages on our own to make it possible in a few weeks. 

Thank you.

