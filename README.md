# Keywords for books data integration

Given the books.csv file, I needed to clean and transform the data for import and also to add relevant keywords for each books. I did this in two steps:

## Description extractor.ipynb
First I scraped 6 books datasets from kaggle and joined their description on the ISBN of the given dataset. 

## Keyword extractor.ipynb
I then performed a keyword exrtraction analysis on these descriptions.

## Output
The output files are books_import.csv and books_keywords.csv which are both ready to be imported.
