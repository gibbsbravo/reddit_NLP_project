# Analyzing Language in Political Subreddits
Uses a variety of natural language processing techniques to explore the use of language in the comments of different political subreddits

1. Reddit API: Pulls submissions and comments from Reddit PRAW API
2. Reddit Comments: reads comment file as iterator and extracts relevant subreddits
3. Subreddit Analysis - Submissions: produces a dataframe with summary level statistics for ~1000 submissions in each subreddit and the news outlets they link to
4. Subreddit Analysis - Comments: produces a clean dataframe with supplemental information on each subreddit
5. Word Frequency: shows summary statistics and correlation between subreddits on sentiment around key terms 
6. Subreddit Classification: Main workbook which takes all other workbooks and tries to predict subreddit based on comments
7. Word Embeddings: trains two word2vec models on conservative and liberal comments and examines how the key terms compare
