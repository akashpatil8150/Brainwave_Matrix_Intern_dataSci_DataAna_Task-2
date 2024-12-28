Instagram Sentiment Analysis
This project analyzes Instagram post captions to determine the public sentiment and visualize the trends over time. Using VADER sentiment analysis, captions are categorized into Positive, Neutral, or Negative sentiments. Various visualizations are provided to explore the data further, including trends over time, sentiment distribution, and engagement metrics (likes and comments) by sentiment.

Steps:
1. Importing Libraries and Loading Data
Libraries like pandas, matplotlib, nltk, and seaborn are used for data manipulation and visualization.
Instagram data is loaded from a CSV file using pd.read_csv().
2. Data Preprocessing
Special characters are removed from captions, and text is converted to lowercase for consistency.
Missing data is handled, such as filling in missing location and username fields with default values, and using the mean value for numerical fields like followers and following.
3. Sentiment Analysis
VADER sentiment analysis is applied to the captions, producing a sentiment score for each post.
Posts are classified into Positive, Neutral, or Negative based on their sentiment score.
4. Time Analysis
Sentiment scores are averaged over time, and trends are visualized using a line plot.
5. Visualizations
Pie Chart: Distribution of sentiments (Positive, Neutral, Negative).
Histogram: Distribution of sentiment scores.
Boxplot: Sentiment score distribution by sentiment category.
Word Cloud: Common words in captions for each sentiment category.
Bar Chart: Count of posts by sentiment.
Heatmap: Correlation matrix of numerical features like likes, comments, and sentiment scores.
Boxplot: Likes and comments distribution by sentiment.
Insights:
Trends: Visualizes sentiment trends over time.
Engagement: Examines the relationship between likes, comments, and sentiment.
Word Clouds: Highlights common words used in different sentiment categories.
Visual Examples:
Sentiment Distribution:
A pie chart showing the proportion of posts with each sentiment.

Sentiment Trends:
A line plot showing sentiment trends over time.

Word Cloud:
A word cloud for Positive, Neutral, and Negative captions.

Correlation Heatmap:
A heatmap showing correlations between likes, comments, followers, and sentiment scores.
