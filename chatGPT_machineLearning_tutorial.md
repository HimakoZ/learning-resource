#### This is a tutorial from the vedio creater Dave Ebbelaar. (https://www.youtube.com/watch?v=OmQiLvnY3WY&t=2s) 
#### You can use chatgpt to do the machine learning work and run model to forecast value you want.
#### Make sure that you have a proper Python enviroment that can use for this tutorial.
#### This tutorial by using chatgpt to do machine learning work will follow by Data Science Lifecycle
![image](https://github.com/HimakoZ/learning-resource/assets/95627649/1cfa5ec3-8158-4b3b-95d5-d27238905f70)

----

#### Step 1
  --Open the link and download the dataset already created : https://docs.datalumina.io/bJhyeJ4lHG...  
  
#### Step 2
  --Open an empty Python file that in source "Data", put dataset into VS code 
  
#### Step 3
  --give chatGPT the senario and business questions that you want to solve by asking to give you a python code using Pandas into a dataframe. 

<A company that rents our bikes that will be rented out on a given day. The model will tabke into account varuious factors such as the date(month, day, whether it is a holiday or weekend), as well as weather data(temperature, precipitation, etc.) to make accurate predictions about bike rental demand. This will help the company to better plan for staffing and bike inventory, and optimize revenue. Can you write python for me that can read this csv using Pandas into a datafram?>

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/2ef6fc14-356c-4de8-8c75-649747dbed88)

#### Step 4
--give chatGPT the column of the table that to help chatGPT get a better sense of what we have to do in the data preparations. then you will get a train test split code and a linear regression model. Copy and Paste, then run the code from chatGPT

<Can you explain the dataset and how we can create a prediction model for the rental? These are the columns in the datasets...>

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/8934265c-56c2-4f07-b2d1-932c0dfa06c5)

#### Step 5
--To ask chateGPT convert the categorical features to dummies

<How do I convert these columns to categorical feature and then create dynnues ub rge oabdas dataframe?>

![1683764639813](https://github.com/HimakoZ/learning-resource/assets/95627649/ef5e5dd8-42ec-4f8e-88ac-68efb30b5ade)

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/3bb47ef7-634a-4399-b550-fd955fa80aad)

--Change the convertion variable from 'df' to 'x'

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/e2ac35bd-922d-44f1-8833-06c8313867f1)

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/c62210f1-d00d-4aad-8bde-b8eb591da88c)



#### Step 6
--Ask chatGPT to make regression model more fancy

<The regression model is too simple, can you provide me with 5 algorithms and code to train, evaluate and compare them? And combine all >

--Ask chatGPT to combine all code into one function that tests all the algorithms and saves the scores to pick the best one in the end, then you will get the code that import all the various models and then creates a loop and score everything

#### Step 7
--Replace the split step of model with new code, and put import step on the top of the code
![image](https://github.com/HimakoZ/learning-resource/assets/95627649/08241c98-556d-4fe4-96aa-241e1cd86f9a)

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/b79321ff-a878-48cc-9121-5f4c4eb2831c)

![1683767512916](https://github.com/HimakoZ/learning-resource/assets/95627649/999da872-f91c-420a-8e68-77d24cd47a61)

#### Step 8
--Run everything, get the best model based on metrics

#### Step 9
--Tell chatGPT which one is the best model, and ask th create a function to perform a grid search over the most important hyperparameters in order to tune the model

<The random forest is the best model. Can you create a function to perform a grid search over the most important hyperparameters in order to tune the model? Use 5-fold cross validation and the MSE and R2 as evaluation metrics.>

--Put import part on the top 

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/024a848c-64ab-4e9d-b1ad-ab707b0017de)

--Run the code you have been given, get the best parameters

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/42e573d9-213a-4e74-8cd5-7835e8b2d51f)

#### Step 10
--Give the result and Ask ChatGPT to create perfect model with best parameters

<These are the best Parameters... Can you create a random forest model with those params and create predictions for y and create multiple plots to visually inspect the results?>

![1683768749232](https://github.com/HimakoZ/learning-resource/assets/95627649/651754ae-c949-40a6-a3e3-bf69d09acbae)

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/0558aa37-5ddc-4ee2-a632-f6ab4815f4ed)

--The plot might be wrong. Try to change the 'y_test' to 'y_test_values'

![1683769073734](https://github.com/HimakoZ/learning-resource/assets/95627649/41a9223d-e8cf-4152-8f0e-6d341500fb6b)

### Step 11
--After got a perfect model, ask chatGPT how to put it into production

<How can I export the model and then put it into production so my client can start using the model to make prediction?>

--Paste the code into VS code

![1683769351241](https://github.com/HimakoZ/learning-resource/assets/95627649/c2a1327f-c72a-4a2d-a70f-df3b34c6d96c)

![image](https://github.com/HimakoZ/learning-resource/assets/95627649/ecf50bd5-324c-42e3-9b11-3bdb0f4fda00)

