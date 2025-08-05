Movie Studio Analysis

Overview

This project analyzes movie industry data to help a new movie studio decide which types of films to produce for maximum box office success. Using exploratory data analysis (EDA), we identified key trends in revenue, return on investment (ROI), audience ratings, and release timing.

Business Understanding

Stakeholder: Head of the new movie studio

Objective: Determine what types of films perform best at the box office and translate findings into actionable recommendations.

Key Questions:

Which movie genres generate the highest revenue and ROI?

How do audience ratings correlate with box office success?

Which release months are most profitable?

Does budget size significantly impact ROI?

Data Understanding and Analysis

Datasets Used:

Box Office Mojo (movie grosses)

The Numbers (movie budgets)

IMDb (movie basics and ratings)

TMDB (popularity and votes)

Rotten Tomatoes (reviews and sentiments)

Data Cleaning:

Removed duplicates and handled missing values

Converted currencies and numeric fields

Merged datasets on movie titles

Extracted primary genres and release months

Visualizations

Revenue by Genre: Shows domestic and worldwide revenue in billions across genres.

ROI by Genre: Average ROI to identify profitable genres.

Ratings vs Revenue: Correlation between IMDb ratings and worldwide gross.

Ratings by Genre: Boxplot of audience ratings by genre.

Monthly Revenue: Average worldwide revenue based on release timing.

Hypothesis Testing

ANOVA for ROI and ratings by genre

Correlation tests for ratings and revenue

ANOVA for monthly revenue differences

A/B tests for peak/off-peak releases and high/low budget films

Conclusion

Action genres dominate global revenue, while Drama has consistent ROI.

Ratings moderately correlate with box office success.

Releasing during summer and holidays significantly boosts revenue.

Higher budgets do not always guarantee better ROI.

Developing globally appealing franchises can maximize long-term profits.

Recommendations

Focus on high-revenue genres like Action and Adventure.

Schedule releases in summer and holiday periods.

Maintain balanced budgets for optimal ROI.

Prioritize scripts with high audience appeal (ratings).

Consider franchises and sequels for sustained revenue.

Repository Structure

movie-studio-analysis/
│── data/ 

│   ├── bom.movie_gross.csv

│   ├── tn.movie_budgets.csv

│   ├── tmdb.movies.csv

│   ├── rt.movie_info.tsv

│   ├── rt.reviews.tsv

│   └── im.db (Git LFS or cloud storage)

│
│── reports/

│   └── data_report.pdf

│

│── visuals/

│   ├── revenue_by_genre.png

│   ├── roi_by_genre.png

│   ├── ratings_vs_revenue.png

│   ├── ratings_by_genre.png

│   └── revenue_by_month.png

│

│── presentation/

│   │──presentation.pdf

│── student.ipynb

│── README.md


Tech Stack

Python (Pandas, Matplotlib, Seaborn, SciPy)

SQLite (for IMDb data)

Git & GitHub



GitHub Profile StephB254
LinkedIn Stephen Bwanmkubwa
