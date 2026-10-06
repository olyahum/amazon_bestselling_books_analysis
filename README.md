# What Makes a Bestseller?

This is my data analytics case study based on Amazon Top 50 bestselling books from 2009 to 2019.

I analyzed book genre, ratings, prices, authors, and how the genre distribution changed over time.

## Questions

- Which genre is most common among bestselling books?
- How do average ratings differ between Fiction and Non Fiction books?
- How does the average price differ between the two genres?
- Which authors appear most often on the bestseller list?
- How does the distribution of Fiction and Non Fiction books change over time?

## Tools

- Python
- Pandas
- SQL
- Google BigQuery
- Tableau

## What I did

- Checked the dataset and its structure
- Checked for missing values and duplicate rows
- Cleaned the data using Python and Pandas
- Renamed columns to make them easier to work with
- Used SQL in Google BigQuery to calculate summary statistics
- Analyzed Fiction and Non Fiction books
- Created a Tableau dashboard to visualize the main findings

## Main findings

- There were **310 Non Fiction books** and **240 Fiction books** in the dataset.
- Non Fiction books made up about **56%** of the dataset.
- Fiction books had a slightly higher average rating: **4.65** compared with **4.60** for Non Fiction.
- The average price of Non Fiction books was **$14.84**, compared with **$10.85** for Fiction books.
- **Jeff Kinney** appeared most frequently in the dataset, with **12 books**.
- Non Fiction books appeared more often in most years, although the difference changed over time.


  ## Recommendations

Based on my analysis:

1. **Maintain a strong Non Fiction selection**
   Non Fiction books appeared more often in the bestseller dataset.

2. **Promote highly rated Fiction books**  
   Fiction books had a slightly higher average rating.

3. **Consider genre when reviewing prices**  
   Non Fiction books had a higher average price.


   ## Files

- `What Makes a Bestseller.ipynb` - Python and Pandas analysis
- `What Makes a Bestseller__Case_Study.pdf` - full case study
- `What Makes a Bestseller_dashboard.png` - Tableau dashboard
- `bestsellers with categories.csv` - original dataset
- `books_clean.csv` - cleaned dataset
