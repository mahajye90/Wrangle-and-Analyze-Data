# Wrangle and Analyze Data

## Introduction:
This project is about gathering data from a variety of sources and in a variety of formats, assessing its quality and tidiness, and cleaning it.

## Tools 

    `pandas`
    `NumPy`
    `requests`
    `tweepy`
    `json`


## Wrangling:
This process contains three steps :
 - Gathering
 - Assessing
 - Cleaning 

### Gather
Gathering data depends on the question of our research and there are various resources to obtaining data. It is important to produce a code that  is reproducible and scalable, so dowloding data from the web is a great practice. We can download a file from the web using `requests`, scraping a web page using `BeautifulSoup`, etc.) 

### Assessing

Assess data for:
#### Quality: 
 The quality of the content. A dirty data or low quality data may contain missing values, incorrect values, or duplicate records .
 The four main data quality dimensions are:
   -Completeness
   - Validity: data must contain valid values.
   - Accuracy: inaccurate data is wrong data that is valid. 
   - Consistency: inconsistent data is both valid and accurate, but there are multiple correct ways of referring to the same thing.

#### Tidiness: 
 Tidy issues are related to the structure of the data. Untidy data is also known as messy data. Tidy data requirements:
      Each variable forms a column.
      Each observation forms a row.
      Each type of observational unit forms a table.

Assessing the data can be done by scrolling through the data. However, programmatic assessment by using python libraries such as pandas is more sufficient.

### Cleaning
Start by making copies of the original data before cleaning. 
The programmatic data cleaning process:
    - Define: the  instruction of cleaning task.
    - Code: the code of the task and run that code.
    - Test: test to make sure that the cleaning operations worked.
    
## In any step of the data wrangling, you can iterate .
    
### Storing 
Finally store the data in a master data frame. 

#### References
  - [Hadley Wickham. Tidy data.](https://vita.had.co.nz/papers/tidy-data.html)
  - [How to Improve Data Quality](https://www.informit.com/articles/article.aspx?p=399325&seqNum=3)
  -

#### Project LICENSE

    This is a Udacity data analyst nanodegree project.
