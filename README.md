# AI/Machine Learning Intern Challenge: Simple Content-Based Recommendation Deliverables:


📌 Dataset

I’m using the TMDB 5000 Movie Dataset from Kaggle. Link for dataset: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv. I have uploaded the same to this repo.

⚙️ Setup

Python 3.x (Tested on 3.10+)

If using Colab, just upload the dataset and run the cells.

🚀 Running the Code

In Google Colab or Jupyter, run all cells and execute the following function with a query:

recommend("I love thrilling action movies set in space, with a comedic twist.")

It'll give you top 10 recommendations based on genre and plot similarity, re-ranked by popularity.

🎯 Example Output

Here’s results from a sample run:

Query: query="I like fun animated movies with talking animals, humor, and heartwarming adventures."

Top Recommendations For You: 

1. Spirited Away (Similarity: 0.0800, Popularity: 118.968562)
2. Alice in Wonderland (Similarity: 0.0586, Popularity: 78.530105)
3. Madagascar (Similarity: 0.1055, Popularity: 48.110909)
4. Insidious: Chapter 3 (Similarity: 0.0609, Popularity: 45.946524)
5. Mars Attacks! (Similarity: 0.0882, Popularity: 44.090535)
6. Patch Adams (Similarity: 0.0732, Popularity: 35.537397)
7. Scary Movie 2 (Similarity: 0.0650, Popularity: 35.376971)
8. 16 Blocks (Similarity: 0.0544, Popularity: 32.31022)
9. Inkheart (Similarity: 0.0637, Popularity: 27.018886)
10. Open Season (Similarity: 0.0792, Popularity: 26.61951)

📸 Results Screenshot
![image](https://github.com/user-attachments/assets/d10be965-44da-4e4c-98dc-8e67c2c3dd1d)
