# Movie Ratings Analysis

## Objective

This project analyzes movie ratings to uncover patterns and influencing factors. It examines various aspects including top-rated movies, genre-specific ratings, monthly rating trends, and fluctuations by release year. The insights aim to assist film producers and marketers in making data-driven decisions.

### Goals
- Evaluate top-rated movies to understand their significance.
- Explore average ratings across genres to assess genre impact.
- Track monthly rating trends to identify seasonal variations.
- Assess the distribution of ratings and fluctuations by release year.
- Analyze genre popularity trends to understand performance over time.

## Dataset
- **movie.csv**: Contains information about movies, including titles, genres, and release years.
- **review.csv**: Contains movie reviews, including ratings, review dates, and reviewers.

## Files
- **Movie_Ratings_Analysis.ipynb**: Python notebook containing the analysis code and visualizations.
- **README.md**: This file.

## Key Functions
- **`plot_monthly_trends(data)`**: Visualizes average movie ratings over the months.
- **`plot_genre_ratings(data)`**: Displays average ratings by genre.
- **`plot_rating_distribution(data)`**: Illustrates the distribution of movie ratings.
- **`plot_ratings_by_year(data)`**: Shows average ratings by release year.
- **`plot_genre_popularity(data)`**: Analyzes monthly review counts for each genre.

## Insights
- **Top Movies**: Identified top-rated movies, highlighting their exceptional quality.
- **Genre Ratings**: Sci-Fi has the highest average rating, though differences between genres are relatively small.
- **Monthly Trends**: Significant rating peaks in May, with dips in February and August suggesting seasonal or release-related effects.
- **Rating Distribution**: Ratings are fairly evenly distributed across various values.
- **Fluctuations by Year**: Ratings show notable fluctuations over time, with peaks in 1993 and 2017. No clear trend of improvement is observed.
- **Genre Popularity**: Drama, Crime, and Fantasy genres show peak review counts in specific months, while Sci-Fi films, despite fewer reviews, have notable spikes.

## Conclusion

The analysis indicates that movie ratings are influenced by multiple factors, including film quality, release timing, and genre popularity. There are no consistent trends over time or by genre, suggesting that improving movie quality and strategically timing releases may be more effective than focusing solely on specific genres or release dates. Further exploration of additional factors could offer deeper insights into the dynamics of movie ratings.
