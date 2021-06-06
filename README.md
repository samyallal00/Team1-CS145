# Team1-CS145
This is Team1's repository containing the code written for timeseries data forecasting of COVID-19 cases across the United States (U.S.). This work is part of the final project of the CS145: Data Mining course at UCLA, Spring 2021.

Necessary files to work with:
1. pipeline.ipynb
2. requirements.txt

# Set-up your environment and Run code:
First, you will need to set-up your virtual environment, in order to install all necessary python libraries used for this project (tensorflow/keras, etc.). Please follow the steps below for a guaranteed and successful setup.

 1. In the directory where the repository has been cloned, create a virtual environment. If you do not have it installed already, you would do:
   a. pip3 install virtualenv
   b. After installation, run: virtualenv <name_of_virtualenv>
   c. Then, run: source <name_of_virtualenv>/bin/activate 
  
  ### Note: <name_of_virtualenv> is a name you choose. If having trouble, please follow the link below on how to setup in different machines: https://www.geeksforgeeks.org/python-virtual-environment/
  
  
 ### 2. After step 1, you are ready to download the packages we used. For that, run: pip3 install -r requirements.txt 
 ### 3. Now that all packages are installed, you are ready to run the jupyter notebook by running the following command: jupyter-lab
 ### 4. Three different links will appear on your terminal, choose either and copy paste it in your browser (ideally chrome), and our code is ready to be run.
 ### 5. Once inside the jupyter notebook, make sure to run each cell consecutively until "Part-5".
 ### 6. While running each cell, pay attention to the markdown headers where an explanation of each code cell is presented as titles and subtitles. The code is divided into multiple parts for data preparation, model selection etc.
 ### 7. Finally, you have three options to run in "Part-5" at the end:
   #### a. Run one example of our best performing model to visualize the model's score and predictions on the state of california.
   #### b. Reproduce the "Team1.csv" file that was submitted through Kaggle.
   #### c. Run the LSTM model to visualize its score and predictions.
   
### Note: Part-5 (b) is the one that will reproduce our work submitted in Kaggle. Also, note that that cell will take up about 5-10mins to run given the complexity of the model and the data. At the end of the running cell, a file named "Team1.csv" will be created in your current directory where you can visualize the predictions.
