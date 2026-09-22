# Spotify-Content-Based-Recommendation

A content-based music recommendation system using Spotify track metadata, genres, and audio features to recommend similar songs.

### Key Results
- Analyzed Spotify tracks using **10+ audio and metadata features**, including danceability, energy, loudness, acousticness, valence, and tempo.
- Investigated relationships between audio features, with **Energy–Loudness correlation ≈ 0.69** and **Acousticness–Energy correlation ≈ -0.63**.
- Built a recommendation engine using **TF-IDF Vectorization** and **Cosine Similarity**.
- The system returns the **Top 5 most similar tracks** for each user query.
- Tested the recommendation system with **5+ artist, song-title, and genre-based queries**.
- Example: the query **"Taylor Swift Love Story"** achieved a similarity score of **0.8896** for *Love Story (Taylor's Version)*.

### Technologies
Python, Pandas, NumPy, Scikit-learn, TF-IDF, Cosine Similarity, Matplotlib, Seaborn
