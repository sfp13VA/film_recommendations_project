# Business Understanding
The company would like to create a new movie studio for original video content, but we don't have any experience with making movies. Here, we want to explore what types of films are performing best at the box office currently in order to make recommendations about what type of films to create in our new studio.

# Data Understanding
We are working with two datasets provided by IMDB and The Numbers.  The data includes information about movies and their genres, ratings, staff, domestic and international gross revenue, budget, and more.

## Data Preparation

I make the data easier to work with by combining my two datasets and calculating ROI as my measure for movie success, bringing all of the information I need into one dataframe for analysis.

# Exploratory Data Analysis
I analyzed the data to make recommendations for making movies, evaluating movie success by ROI.

Movies released in the summer, especially June, performed best.

 <img width="720" height="432" alt="roi_by_month" src="https://github.com/user-attachments/assets/44a4accb-2967-49f1-973d-d48acadfa3d2" />

Mystery, horror, and thriller genres had the best ROI.

<img width="720" height="432" alt="ROI_by_genre" src="https://github.com/user-attachments/assets/5c0d9247-0ec6-4b31-9a06-259da1a1b243" />


Chris Lofing, Travis Cluff, and Matthew Peterman were the best performing writers in these genres measured by ROI.

<img width="720" height="432" alt="ROI_by_writer" src="https://github.com/user-attachments/assets/bd3622a0-22bf-413c-a42c-be2397aff1f6" />



# Conclusion
1) Release dates in the summer, ideally early summer (June), are correlated with the best ROI.
2) Horror, mystery, and thriller genres are associated with the highest ROI.
3) Chris Lofing, Travis Cluff, and Matthew Peterman are writers associated with the highest ROI movies in the horror, mystery, and thriller genres.

## Limitations
Even though we have a good amount of data covering a long time period, the rise of streaming movies is still a new development that will continue to change the way consumers watch movies and even what they watch. There are also societal changes that could cause preferences to evolve over time. We also had no information about marketing budget in this data, so that should be evaluated as well.

## Recommendations
1) We should work toward a goal of summer release dates, ideally in June.
2) Horror, mystery, and thriller genres are recommended.
3) Chris Lofing, Travis Cluff, and Matthew Peterman are writers we should try to work with.
4) 
## Next Steps
1) This is an ever-evolving industry, so keeping tabs on this data and how it changes is essential.
2) It would be good to get some information about marketing budgets and to what extent marketing could help achieve an even better ROI for our movies.
