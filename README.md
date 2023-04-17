## Video Game Recommender System v2

### Description
A video game recommender system using a larger game dataset based on Launchbox metadata. The dataset was cleaned and preprocessed. Then Word2Vec was used to create a word vector database. Description vectors were created based on the word vectors with one-hot encoded genres added afterwards. A recommendation function is included that calculates cosine similarity on the fly. Code for creating an entire similarity matrix row by row is also included but it takes time. This is because if you simply try creating the matrix using cosine_similarity(matrix, matrix), you will need around 44GB of RAM.

### Instructions
- Install ARRM (Windows only)
- In Users/%username%/AppData/Roaming/Nexouille Soft/arrm/Database, you will find a bunch of MS Access .mdb files. The data is in the launchbox.mdb file under the Game schema.
- Extract the data and convert it. In this case the schema was exported to multiple Excel files in MS Access due to export row limits.
- Run cells in the notebook as desired

### Notes
Still learning Word2Vec and what the different parameters do. So could be an even better model.