Files
  - a1digits.mat cotaints data to be analyzed
  - MaeveBuchan_20020510_Assignment1 contains my code 
  - MaeveBuchan_20020510_Assignment1_WriteUp contains my findings and output
  - README is this file

To run my code 
  - Ensure the data is in the same path as MaeveBuchan_20020510_Assignment1.
  - Run all code. 


MaeveBuchan_20020510_Assignment1 Sections

	%% Load Data into MATLAB
	  - Gets all the provided data into Matlab matricies. 
          - Creates matrix for testing data and training data for Gaussian Classifier
	  - Creates matrix for testing data and training data for Naive Bayes Classifier
	  - Converts Naive Bayes Classifier data to binary values.


	GAUSSIAN CLASSIFIER
		%% Learn Data and Data Dimensions
		  - Get information on data size
		  - Plot a random sample to visualize 

		%% Gaussian Classifier Training
		  - Calculate mean values.
		  - Calculate variance
		  - Calculate standard deviation
		
		%% Gaussian Mean Plot
		  - Plot the means

		%% Gaussian Testing 
		  - Calculate p(x|Ck) for all test data.
		  - Calulates and stores all classifications to determine error count + error %.
		
		%% Gaussian Output Table
		  - Uses data from the previous section to output table with how many errors out of 400 each classifier makes for each class.

	NAIVE BAYES CLASSIFIER
		%% Naive Bayes Sample
		  - Plot a random sample to visualize 

		%% Naive Bayes Mean Plot
		  - Calculate mean values.
		  - Plot the means

		%% Naive Bayes Testing 
		  - Calculate p(b|Ck, η) for all test data.
		  - Calulates and stores all classifications to determine error count + error %.
		
		%% Naive Bayes Output Table
		  - Uses data from the previous section to output table with how many errors out of 400 made for each class.
		
	%% Gaussian and Naive Bayes Output Table
	  - Outputs 2X11 table with with how many errors out of 400 each classifier makes for each class.
	  - Includes error %.