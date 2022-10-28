# final-project
Final project for Decision Support Systems &amp; Verification 2022

# part 1

Here we have the EDA and RS in the ipynb file for part 1.

## Dataset
Datasets taken from [here](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) 

## Cleaning up the dataset
### We removed the BX- prefix from each dataset name readability
### I know that all books have a valid ISBN since the website where i got the dataset states that all data with invalid ISBNs have been removed (http://www2.informatik.uni-freiburg.de/~cziegler/BX/)
### I see some of the ISBNs end with a X and some are only numbers but have to assume that this is intended beacuse of the statemant above that invalid ISBNs have been removed
### The site also states that if a book has multiple authors only the first in provided, so we know that each book only has one author
### First  thing i notice is in the users.csv, there are some inconsistencies in how the locations are written down (ex. ny, ny / ny, new york / ny, nyc) so i will see how this will affect the data, i can only assume there are similar thing on other locations
### I see that many of the users have no age, an esstimate would be just under 50% of them have no age, we will see hom this affects the data
### The ratings seems fairly straightforward, no big changes for any outliers
### The year seems to be inconsistent between strings and numbers so we need to fix that, while doing that we noticed a few lines with data in the wrong places which we manualy fixed

## Reading the data
### Some names in Users and Author Books have some special characters in them so we have to change the encoding
Datasets taken from [here](http://www2.informatik.uni-freiburg.de/~cziegler/BX/)

# part 2
For part two we chose the Effective Nearest-Neighbor Music Recommendations submission.

# part 3
Part three is a part of the video
