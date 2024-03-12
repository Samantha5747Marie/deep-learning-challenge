# deep-learning-challenge

The purpose of this analysis is to get the prediction on if applicants to a charity will be successful or not.   


Data processing:
The target of the model is IS_SUCCESSFUL 
The features of the model are all columns that aren't the target such as "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT"
The variables that should be removed are "EIN" and "NAME"

Compiling, Training, and Evaluating the Model
I used 15 neurons and 10 for the 2 layers and then 1 neuron for the output layer with the relu function 
The model performance was at 72.91% which is pretty accurate .
While trying to increase the models performance in the AlphabetSoupCharity_Optimization i changed the neurons many times, added and took away layers, changed the value count on the classification and application counts but the performance and i did get it up to 73% but then i tried changing things again and wasn't able to get back to that. So after a handful of times changing things it was lower than the first time ending at 72.70%. 

Images:
I first tried changing these: 
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/ebd6daaf-38b1-47fc-a1c8-5d1bf902fedd)
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/21148729-65c2-47a8-8042-56c2a68f6c41)
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/e5f7ad2e-3c6c-4fdf-bbf7-7d722e2a3bc1)
and got this result 
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/8e70ab89-01b5-4fba-830f-54d40be8f335)

then tried changing this 
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/76c10086-dd48-466e-ba63-1ceab63a0653)
and got this result 
![image](https://github.com/Samantha5747Marie/deep-learning-challenge/assets/144191446/c825f156-255a-4d68-85c9-e823f21e5c6e) 

Results:
The overall results of this analysis were pretty accurate at aroun 72% which is very reasonable but also room for improvement. Another recommendation would be to try and use random forest classifier as it would be easy to add, it can become less inclined to overfitting the data and it can reduce the impact of outliers to the final result.   
