# music-taste-prediction

Repository contains the project report for a program that I wrote for my major project during engineering school.

I extracted a user vs. song matrix from the Million Song Dataset availabe online. Rows represented users and 
columns represented songs with the values representing the playcounts for the songs by the users.

I split the matrix to testing and training subsets and approximated the playcounts by all users for a song 
in the test data by taking a weighted average of 10 of its nearest neighbors.

Used cosine similarity to find neighbors.

Please reach out to me for the source-code and matrices and I shall share the same (original repo with me is 41gigs).
