## Video Game Recommender System v2

### Description
Using a large game metadata dataset that also includes old-school games, do the Word2Vec thing and get recommendations based on cosine similarity. Code for creating a matrix row by row is in the notebook as doing cosine_similarity(matrix, matrix) will likely not be possible unless you have 64GB.

### Instructions
- Install ARRM (Windows only)
- In Users/%username%/AppData/Roaming/Nexouille Soft/arrm/Database, you will find a bunch of MS Access .mdb files. Its either the Launchbox.mdb or Gametdb.mdb.
- Extract the data and convert it e.g. use MS Access to export data to MS Excel.
- Run cells in the notebook as desired