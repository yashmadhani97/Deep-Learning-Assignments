I have put separate code for each questions to easily reproduce the result.

DL_Assignment_1.ipynb file
1. run all the cells from "Common cell for all questions"

2.for question 2,3,4,5,6
I have put separate cells which are configured with wandb.

3.for question 7 
I have put separate cells which execute partial code locally and configured wandb only for pushing confusion_matrix plot.

4.for question 8 
I have put separate cells which are configured to wandb with different sweep for only 2 runs for better comparisions of different losses.

5.for question 10 
I have reloaded the mnist dataset and put 3 different cells for each configuration.

6. Under "Extra local test runs" we can test model locally without wandb configurations

For check result first run the common cell section then goto each question and run as per requirement.