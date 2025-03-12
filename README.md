# Book-Recommender-System-Clustering-ML-Project

### Step-by-Step Code Execution
### Load Libraries:

```numpy and pandas for data manipulation.
```
### Read and Explore Datasets:

1.Books.csv: Contains book details like title, author, year, and publisher.
2.Users.csv: Contains user details like user ID, location, and age.
3.Ratings.csv: Contains book ratings given by users.
### Preprocessing:

1.Columns are renamed for consistency.
2.Dataset shapes are displayed to understand data volume.

###Filtering Data Based on Criteria:

1.Only users who rated more than 200 books are considered.
2.Only books that have at least 50 ratings are included.

### Creating a Book-User Matrix:

1.The dataset is transformed into a matrix where rows represent users, columns represent books, and values represent ratings.

### Applying Similarity Measures:

1.Either cosine similarity or correlation-based similarity is used to find similar users or books.

### Generating Recommendations:

1.Based on similarity, the system suggests books to users.
2.The most similar books to a given book or user preferences are displayed.

### Insights
1.The system filters out less active users and unpopular books, ensuring meaningful recommendations.
2.Similarity-based recommendation suggests books based on either user preferences (user-based) or book similarity (item-based).
3.Popular books and highly active users have a stronger influence on the recommendations.

### Conclusion
1.The recommender system effectively refines the dataset before making recommendations.
2.The approach uses collaborative filtering to suggest books based on similar users or books.
3.Improvements can include content-based filtering (using book descriptions) or hybrid models to enhance accuracy.
