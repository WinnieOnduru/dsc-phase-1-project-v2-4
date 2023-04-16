## Analysis For Microsoft's New Studio


### Overview

Microsoft has decided to get in on the fun that the big companies creating original video content are in.
This they are doing this by creating a new movie studio.They however, lack knowledge and expertise in creating films and It’s is for this reason that they need to determine which types of films are currently successful in the market. 


### Business Understanding

I need to conduct an analysis to identify the current top-grossing film genres that are driving box office success. I also need to examine the budget and competitive landscape of successful films and consider any emerging trends in the industry. The findings from this analysis will help Microsoft's new movie studio to make informed decisions on what type of films to create.
The questions ill have to answer in order to objectively get clear recommendations that will be beneficial to Microsoft are:

       1.How does the release month of a film affect its gross values i.e Worldwide and Domestic?

       2.Which is the most popular film genre ?

       3.Which Studios are making the highest profit?
       
       
### Data Understanding
These data were provided by Flatiron.I had several datasets in zipped files, namely:
    * Box Office Mojo
    * IMDB
    * Rotten Tomatoes
    * TheMovieDB
    * The Numbers
    
For this analysis though i used :
    * bom.movie_gross.csv has five columns comprising of movie titles, studios, financial incomes both domestic 
      and foreign and the release year.
    * tn.movie_budgets.csv contains information on released films, including their names, release dates, 
      and financial data such as production budget and worldwide gross. 
    * rt.movie_info.tsv tells us more about each movie.It has twelve columns namelyid,synopsis,genre,rating,director,writer,theater_date,dvd_date, currency,box_office,runtime and studio.
    
    
### Data Analysis
I checked my directory so as to access all the folders with the datasets that i am going to use for this project.
I merged datasets.This is the process of bringing two datasets together into one, and aligning the rows based on common attributes or columns. In this case, df_movies_info and df_bom_movies_gross are joined first to form df_dataset_one. They share a common column called 'studio'. Since Title and Movie columns are the same,i am going to change the column Movie in the table df_movies_budgets
to Title then join df_dataset_one to  my final dataset called df_dataset_final.
This analysis can be seen more comprehensively here http://localhost:8888/notebooks/student.ipynb#Data-Analysis and http://localhost:8888/files/PRESENTATION.pdf


### RECOMENDATIONS
 All said and done,After my analysis, these would be my data driven recommendations to Microsoft:
1.Know your audience,how so you may ask,the top film genres overall were Drama|Mystery and Suspence.
 Microsoft should then consider creating movies within these genre parameters if they want to generate interest and increase their likelihood of achieving high popularity since these kind of films draw the crowds.
 
2.The highest profiting studios have the best business models that should inform Microsofts practice for their own studio.
   The business strategies of these studios should be carefully scrutinized to determine and emulate their methods for success.
   These studios include FOX,WB,MGM,A24 and IFC.
   
3.Finally the findings of the study presented above lead one to the conclusion that there is, in fact,
   a positive link between the release month/period and the gross values i.e Domestic and Worldwide.
   The films released in the month of July and December generally grossed higher compared to other months.
   
   
### NEXT STEPS
Its said that the core advantage of data is that it tell us something about a world we did not know of before.
More analysis can still be done on issues like(but not limited to) the Film directors ,the Runtime of each Film and even the Ratings.
With the above analysis and recomendations,Microsoft should be now ready to enter into the Film industry head high with data driven decisions.