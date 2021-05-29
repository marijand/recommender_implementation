The main contribution was to apply the idea of neural collaborative filtering to the amazon product review data set and thus, show how neural collaborative filtering could be used to recommend products to customers.

Steps to run the program

Run locally:
1. Install Anaconda Navigator to install Jupyter Notebook: https://docs.anaconda.com/anaconda/install/
2. Open the navigator. Navigate to "Environments" and add the Keras library to your base (root) environment.
3. Launch Jupyter Notebook
4. Download and unzip the file
5. Open the file "Recommender Implementation.ipynb" using Jupyter Notebook
6. Download the dataset from Kaggle: https://www.kaggle.com/saurav9786/amazon-product-reviews
7. Make sure that the file "ratings_Electronics (1).csv" is in the same folder as the "Recommender Implementation.ipynb" file.
8. Now you are able to run the file


Run using Kaggle:
1. Register on Kaggle: https://www.kaggle.com
2. Navigate to https://www.kaggle.com/code and click on "New Notebook"
3. Click on "File" on the top and select "Upload notebook".
4. Upload the "Recommender Implementation.ipynb" file.
5. To load the dataset, click on the "add data" button on the right side.
6. A window will pop-up. Enter "Amazon Product Reviews" in the search field and click on the "add" button on the one that is uploaded by Saurav Anand (https://www.kaggle.com/saurav9786/amazon-product-reviews)
7. Be sure to remove "#" from the code line that is used to load the data from kaggle and add a "#" to ensure that the the code line that is used for loading the data locally is not being executed
8. Now you should be able to run everything. Just be sure to reduce the number of data that you use at the beginning of the "Conduct pre-processing" step. Kaggle only offers limited computational power. Training a neural network with 150,000 data points might take too long on Kaggle.
