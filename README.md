# dogbreed_identification_cnn
## Description
The data consists of 10222 train and 10357 test dog images, a two-column labels dataset listing the IDs and dog breeds, and a sample Kaggle submission file.  
## Objective
The objective was to create a model that would predict the breed of a dog by image. 
Set up a GitHub repository and upload the completed Jupyter Notebook.
Submit the model to the Kaggle Dog Breed Identification Competition for analysis and obtain a score and a leaderboard position. 
## Model
For this exercise, I chose to build a basic two convolution layer Sequential CNN, since I was running the model using a CPU.  I added back propagation hopefully to induce quicker convergence.  
## Results
Actual results from this model placed me at around the 1000 mark with a 10-epoch score of 4.62446.
My original model included running on a GPU and would have produced better results. After trying to read the images from Google Drive into Colab many times with poor results, I decided to use Jupyter Notebook, worked just fine.  The likely suspect was using tqdm in the Google system.
