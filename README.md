# Investigate a Movie Dataset
## by Suleiman Mohamed


## Dataset

> This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings, budget, genre, director and revenue. Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. There are some odd characters in the ‘cast’ column. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

## Summary of Findings

> From the first question about the popularity of movies over the years, which shows relationship between released year for movies with popularity, we can see that the histogram is more skewed to the left. This means that movies are becoming more popular over the years.

> From the second question about the rate of voting for movies over the years, which shows relationship between released year for movies with votes casted, we can see that the histogram is more skewed to the left. This means that movie voting is being done more in recent years.

> From the third question about the runtime of movies over the years, which shows relationship between released year for movies with there runtime in minutes, we can see that the histogram is more skewed to the right. This means that movies have reduced there runtime over the years.

> From the fourth question which shows relationship between popularity ratings and votes count for movies, we can see the graph which shows a positive correlation between vote count and popularity. This means that the votes count and popularity ratings of movies are dependent on each other, if the votes count is low so does the popularity and vice versa.

> From the fifth question which shows relationship between popularity ratings and runtime in minutes of movies , we can see that the graph above is more densely populated between 0-200 in runtime and 0-10 in popularity rating. This means that many movies lies in the runtime of <200 min and do have a popularity ratings of <10.

> From the sixth question which shows relationship between vote counts and runtime in minutes of movies , we can see that the graph above is more densely populated between 0-200 in runtime and 0-4000 in votes count. This means that many movies lies in the runtime of <200 min and do have votes count of <4000.

> From the seventh question which shows how is the distribution of runtime for some popular movies , we can see that the graph is more skewed to the right. We can see 2 different halves of the runtime of movies that lies in the range <200 min; The 1st half is less than half the <200 min contains total no. of movies in between 3000-2000. The 2nd half is greater than half the <200 min contains total no. of movies more than 8000. This shows that many movies lies in this 2nd half in the range <200 min.

## Limitations

1.  The dataset had so many irrelevant data that needed to be cleaned.

2. Some features had some missing values that there was need to eliminate them.

3. The dataset contained different datatypes that there was need to change the datatypes to the appropriate one.