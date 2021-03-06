# Initial Genre Recommendations for Microsoft
#### Author: Dominick D'Andrea

# Overview
Microsoft has decided to create a new movie studio because they have recognized the success of other studios. However, they don’t know anything about creating movies. They have hired you to help them better understand the movie industry and explore what type of films are currently doing the best at the box office.

# Data
The data for this project comes from IMDB and TheMovieDB.org. There are several databases that needed to be joined from IMDB to connect each movie to its respective rating, which can be accomplished using a unique identifier for each movie. TheMovieDB.org contains the financial information for movies, but contains significantly less data that the IMDB database. Therefore, joining the two resulted in a smaller sbuset of movies that had financial and ratings information.

# Methods
This project uses exploratory data analysis to look at genre financial and ratings to come up with a recommendation.

# Results
The genres with the highest ROI are Horror, Mystery, and Thriller, respectively.  

![download](https://user-images.githubusercontent.com/41350313/116320519-5d6fdb00-a786-11eb-86e1-206bda452ca7.png)

Looking one layer deeper, we see that production budgets have varied greatly over genres. Cross-referencing this information with genre ROI, Mystery and Thriller are attractive prospects. Mystery films have the second highest ROI of over 1000% and a median budget of $14 million while Thriller films have the third highest ROI of 685% with a median budget of $21 million. Horror may have the highest ROI, but the average ratings are poor and they don't have the broad appeal of Mystery or Thriller.

![production budget](https://user-images.githubusercontent.com/41350313/115923875-f0d6a280-a44c-11eb-94c1-b40532a38557.png)

Adventure, Animation, and Sci-Fi movies gross more, on average, with Animation bringing in a median of $100 million. However, the production budgets for these genres are unsurprisingly high, which would not be prudent to pursue so early in the game. Theses films require a lot of special effects and computer animations, which are expensive and take time to perfect. Mystery and Thriller films don't gross as much, but the potential for these films to gross high amounts is there, looking at the distribution.

![worldwide gross](https://user-images.githubusercontent.com/41350313/115924292-883bf580-a44d-11eb-802e-27efe13fe41f.png)

# Conclusions
I would recommend Microsoft pursue either Mystery or Thriller films given the ROI and relatively modest production costs. Their ratings are vitually identical at 6.2 and 6.1, respectively. Thriller is a more crowded space, whith over 11 thousand movies while there may be more opportunity to shine with an Mystery film, which has about 4.6 thousand films.

# Next Steps
I think it's important to consider whether or not Microsoft will focus on domestic or international movies, which could change the findings depending on what is popular in the US versus abroad. Further data analysis could also uncover any relationships between ROI and runtime/production budget. Once a genre is selected, a list of producers with the highest grossing movies and ratings in that genre should be constructed, as these could be potential collaborators or producers for Microsoft.

# For more information
For more information, view the full [Jupyter Notebook](https://github.com/dandread/project1Submission/blob/main/projectSubmission/student.ipynb) or [presentation](https://github.com/dandread/project1Submission/blob/main/projectSubmission/Microsoft%20Presentation.pdf) here.
