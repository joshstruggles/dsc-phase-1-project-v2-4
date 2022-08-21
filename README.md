# Microsoft film studio narrows down specifics for team's first project



<div>
    <img src="microsoft building.jpg" width="900" align = "center"/>
</div>

## Overview

Microsoft has decided to join the film industry and we are charged with the responsibility of finding out how best the company can dip their metaphorical toes into the depths of Hollywood. Our approach is to take a look at films that are considered to be "good" films, with an IMDB score of "7" or above, and an ROI of 5000% or higher. Once we have our sample size we will look to see if the genre and initial budget has anything to do with the success of other films, and how we can replicate some of that success for ourselves. 


## Business Problem 

Microsoft historically has not been in the business of filmmaking however, change is on the horizon. From a business standpoint, we are responsible for the direction this film could potentially go in and without proper research, the success of Microsoft's first outing could prove problematic. 

## Data Source and Data Exploration

The data used was provided to us via the original project repository. We mainly utilized IMDb database, as well as thenumbers.com database. From the IMDb database we utilized the following: 

* IMDb ratings database for average user ratings on films. 
* IMDb basics database for information on films: genre, film title, and runtime. 

From thenumbers.com database we utilized the following:  

* Website dataframe with information on initial budget, domestic, and worldwide gross. 
* ROI(return on investment) percentage was found dividing initial budget into worldwide gross and multiplying by 100. 

We narrowed down our dataset by allowing only films deemed "above average" (an IMDb score of 6.14 or above) and an ROI (return on investment) of 500% or better. From that set we surveyed the 331 films to answer four questions: 

* What film genre makes the most money? 

* What film genre costs the most to produce? 

* What film genre has the highest ROI percentage? 

* What film genre is the most critically acclaimed? 

# Which film genre makes the most $$$?

<div>
    <img src="photos\MOSTMONEY.png" width="900" align = "center"/>
</div>

## Average worldwide gross per genre: 

* History films make $1.47 billion 

* Animation films make $500 million

* Adventure films make $400 million 

* Fantasy films make $320 million 

* Musicals make $316 million

History films on average make the most in terms of worldwide gross followed by animation, adventure, musicals and fantasy films. 

## Which films cost the most to make? 

<div>
    <img src="photos\HIGHESTCOST.png" width="900" align = "center"/>
</div>

## Average cost of making a successful film in this genre: 
* History films cost $133.6 million

* Animation films cost $57.3 million 

* Muscial films cost $48.1 million 

* Adventure films cost $46.3 million 

* Fantasty films cost $38.6 million

## *Further considerations in regards to genre:*

* Musicals on average make less ROI than Adventure and Fantasy films with a similar initial budget. 

## Which film genre has the highest ROI percentage? 

<div>
    <img src="photos\ROI.png" width="900" align = "center"/>
</div>

## Average ROI percentage by genre: 

* Horror films have a 5421.27% ROI with an intial investment of \\$10.5 million and a worldwide gross of $116 million

* News films have a 5336.59% ROI with a initial investment of \\$1 million and a worldwide gross of $53.3 million 

* Sci-fi films have a 5230.71% ROI with an initial investment of \\$18 million and a worldwide gross of $167 million 

* Mystery films have a 5067% ROI with an initial investment of \\$12 million and a worldwide gross of $152 million 

* Action films have a 4153% ROi with an initial investment of \\$27 million and a worldwide gross of $268 million 

## What film genre is the most highly rated? 

<div>
    <img src="photos\HIGHESTRATED3.PNG" width="900" align = "center"/>
</div>

## Average IMDb rating by genre: 

* Surprisingly, westerns have a very high score of a 7.85 on average on IMDb

* Documentaries on average have a 7.41

* News gets a 7.4

* Biography films on average get a 7.35

* War films are also highly rated with an average of 7.3

## Further Considerations

* Mad Max has the highest ROI percentage of any of the films we looked at today with an ROI percentage of 49875%, genres fall under Action, Adventure, and Sci-Fi. 

* Big has an average IMDb score of 8.9 and is a documentary. Documentaries are also on average the second highest rated genre on IMDb. 

## Conclusions

* History films have the potential historically (no pun intended, I swear) to make the most $$$, unfortunately they also cost the most to create. 

* Horror films on average have the most ROI, however that also seems to be because horror films in general start with a fairly modest average budget of \\$10.5 million (compared to the average history film's budget of $133 million). 

* The Western genre does very well with viewer scores if we are interested in solely making a good film with an average IMDb score of 7.85
