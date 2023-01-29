# 14-Algorithmic-Trading-Assignment
Base Case (Short Window = 4, Long Window = 100, Training months offset 3
![image](https://user-images.githubusercontent.com/106042828/215296124-1663a74e-d94d-4070-bd80-2e1b3ff9b004.png)

Tune the Baseline Trading Algorithm
Step 1:  Tune the training algorithm by adjusting the size of the training dataset.  Updated the ending period for the training data from 3 to 4 months.  
This produced lower strategy returns relative to the actual
![image](https://user-images.githubusercontent.com/106042828/215296427-6057a34c-8648-4b78-870b-94c2c07a0664.png)

Step 2:  Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file
Shifted the Long Window from 100 to 50 produces slightly higher strategy returns.
![image](https://user-images.githubusercontent.com/106042828/215296546-eda36f6d-a961-4e73-ab14-276dc372b371.png)

Evaluate a New Machine Learning Classifier
Step 1: Imported the AdaBoost classifier

Step 3: Using the AdaBoost classifier model produced higher accuracy, however the strategy return was less than the SVM model leveraging the same parameters
![image](https://user-images.githubusercontent.com/106042828/215296751-abe4dd71-0a6e-41bc-b7dc-c357953963ee.png)
