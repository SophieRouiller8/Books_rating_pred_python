# Books_rating_pred_python
The objectif of this exercise is to predict books score rating based upon a dataset of 11127 entries (rows). while the books market represents $112.5bn in 2022 the market is expected to grow (CAGR) by 1.9%. Therefore knowing what books will be successful is becoming important for the publshers and in general the industry.
The dataset contains the following information :
```
 -bookID : unique book's identifier
 -authors : the person who wrote the book, and/or the designer, and/or translator....
 -average_rating : the average score given by the lectors
 -isbn : unique international books identifier (10 digits)
 -isbn13 : same as above but 13 digits
 -language_code : international codes for the publications languages
 -num_pages : number of pages per book
 -ratings_count : the number of ratings (votes) given by the lectors
 -text_reviews_count : the number of text written about the books
 -plublication_date : issue date of the book
 -publisher : the company that publishes the book
 ```
 ```
 This dataset is provided by 'Goodreads' website and is based on real users information.
 Missing in this dataset : the books genres (that I call 'categories').
 Web scrapping using selenium, I could gather 10679 categories. So only 397 were missing (3.6%)
 
 Then I could process to the data cleaning, transformation, formatting, analysis and finally trained the set on Linear Regression, Random Forest Regressor and Ridge models.
 
 _Technology_ :
 Python 3.9.13 on a test environment
 VS Code (supports jupyter notebook)
 Github : host
 
 _Libraries_ (see requirements)
 
