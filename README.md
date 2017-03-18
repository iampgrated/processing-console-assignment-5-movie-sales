# Processing Assignment 5: Movie Sales

In this assignment you will create a program that will be presenting information to the user about various blockbuster movies and then take user input on whether the user is interested in watching the movie or not. Identify five movies and their sales ($). You can find this information at various web sites, e.g. https://en.wikipedia.org/wiki/List_of_highest-grossing_films . 

## Set up
Your set up section will be quite large as you are going to store two things for 5five movies of your choice (a total of 10 variables). Those two things are:
* The movie name  - stored in Strings called movie1Title, movie2Title, etc.
* The movie’s total sales so far – stored in ints called movie1Sales, etc.
These should be set up similar to the following:
```
String movie1Title = “Where the Wild Things Are”;
int movie1Sales = 32000000;
```
## First movie
Complete the following (IN THIS ORDER) for the FIRST movie:
1. Using a ```println```, print out the title of the movie.
2. Using ```If… Else``` statements, print something similar to: 
  * ```This is a blockbuster movie!!``` if sales are greater than 100 million dollars (or some other appropriate threshold).
  * ```This movie is not very popular.```  if sales are less than the threshold.
3. Then ask the user: ```Are you interested in seeing this movie?``` 
4. Using ```If… Else``` statements:
  * If they answer no, print them a discount coupon to encourage them to come (see the Final 10% section below).  
  * If they answer yes, explain what time it is playing at your favourite theatre (you can make this up).

## Movies 2 - 5:
Get this working for the first movie, and then do the same thing for the next four movies. You can copy and paste your code and tweak the title/sales for the other movies.

## Evaluation
60% - completion of the above requirements for the FIRST movie
20% - completion of the above for each additional movie 
10% - Good Coding practices (comments, indenting, commits, etc.)
Final 10% 
* For each movie, add an ```If… Else``` statement inside the ‘no I am not interested in attending this movie’ option.  Once the user has answered no, ask the user if he or she likes popcorn.  
* If the answer is yes, offer them a discount on a combo that includes popcorn (make something up) and print a coupon similar to the example below.
* If the answer is no, offer them a discount on a combo that includes a hotdog and print a coupon.
* As part of the above, print out a coupon like the one below.

Note: You can print the same coupon for each movie.

Example coupon:
```
****************************************************
*     Here is a special offer to encourage you to attend            
*     Where the Wild Things Are:                                            
*     Super Combo                                                                  
*     (Large Pop, Belly-Buster Popcorn, 8 Miles of licorice)       
*     $8.95 (regular price is $11.95)                                        
****************************************************
```
