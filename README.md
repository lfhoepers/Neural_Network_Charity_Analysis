# Module 19 Challenge

## Overview of the Neural Network Charity Analysis

The purpose of this analysis was to assist Alphabet Soup predict where to make investments, analyzing data from more than 34,000 organizations that have received funding from Alphabet Soup over the years.


[AlphabetSoupCharity.ipynb](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity.ipynb)

[AlphabetSoupCharity.h5](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity.h5)

[AlphabetSoupCharity_Optimization.ipynb](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity_Optimization.ipynb)

[AlphabetSoupCharity_Optimization_Attempt_1.h5](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity_Optimization_Attempt_1.h5)

[AlphabetSoupCharity_Optimization_Attempt_2.h5](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity_Optimization_Attempt_2.h5)

[AlphabetSoupCharity_Optimization_Attempt_3.h5](https://github.com/lfhoepers/Neural_Network_Charity_Analysis/blob/f6cb16558c90aec4595176cb4aa5f4685c2fd105/AlphabetSoupCharity_Optimization_Attempt_3.h5)



## Results:

- What variable(s) are considered the target(s) for your model?

The IS_SUCCESSFUL column is our target for the deep learning neural network.

- What variable(s) are considered to be the features for your model?

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL CONSIDERATIONS, ASK_AMT.

- What variable(s) are neither targets nor features, and should be removed from the input data?

These were the EIN, NAME, and the original columns that were encoded.

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
2 hidden, 80 neurons on first and 30 on second.

hidden_nodes_layer1 =  80
hidden_nodes_layer2 = 30

![image](https://user-images.githubusercontent.com/100812079/176792577-9d0799de-a0c1-4989-b558-a65f2e5f55d4.png)


- Were you able to achieve the target model performance?

No, I just found 68% of accuraccy.

- What steps did you take to try and increase model performance?

Attempt 1 - Removed Noisy Variables Only


![image](https://user-images.githubusercontent.com/100812079/176792996-b1a16e75-f6fe-4a0d-aeae-966527ef1780.png)


Attempt 2 - Removing Noisy Variables & Adding additional neurons to the hidden layers and hidden layers


![image](https://user-images.githubusercontent.com/100812079/176793045-8d0a7035-0b0e-4feb-a5bc-f717181d1d32.png)


Attempt 3 - Removing Noisy Variables, Adding additional neurons to the hidden layers and hidden layers & Changing activation to tanh


![image](https://user-images.githubusercontent.com/100812079/176793067-5c4952b1-042c-4a8a-a46c-6813906c1c65.png)

## Summary: 

Despite all above efforts, I was not able to achieve the desired accuracy of 75%.

For further analysis I recommend an additional analysis using the Random Forest classifier to compare the results to the deep learning model.


I appreciate the opportunity to present this project, I am available for any clarification.


**Luiz Fernando Hoepers**  
###### UofT SCS Data Analytics Boot Camp
