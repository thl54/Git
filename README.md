# Git
ESSEC WORK
Gaëtan Gilles & Thibault Lavaine

We imported a csv file that contains among others, the names, the population, the altitude of the 36,000 French towns. 

Thanks to our Python skills in Data science, we managed to create an algorithm that gives the number of inhabitants above and under an altitude, and the mean above and under that altitude.

We used Pandas and Numpy libraries as well as datetime and colorama.

First, we gave names to each of the 27 columns of the file. 
Then, we created functions to copmpute the number of towns above and under the chosen altitude, the mean of the population, and its sum.
We used several methods such as .sum, .mean, .format, .CYAN and function likt int.
To avoid ValueError, we also created a Try loop which makes the algorithm user friendly when the mean computation is not possible.

Then come the loo of the program : 

