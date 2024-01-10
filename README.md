# Overview of the analysis: Explain the purpose of this analysis.

# Results: Using bulleted lists and images to support your answers, address the following questions:

# Data Preprocessing

1. What variable(s) are the target(s) for your model?
 
 The target is Is-Successful  columns
2. What variable(s) are the features for your model?

  Features list of this model are the name, application type affiliation classification use_case organization income special cosideration status and ask amount
3. What variable(s) should be removed from the input data because they are neither targets nor features?
  
  EIN(Employee identification) 

# Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

  FOr this model 3 huden layers each with many neurons as the compute seems to increase accuracy above 75%. this is costly. The first activation is relu and the other layers are sigmoid. it might boost accuracy from using these functions. Re adjusting the data that names as a get dummies can factor with better scores. 

2. Were you able to achieve the target model performance?

  Yes

3. What steps did you take in your attempts to increase model performance?

  Required to convert NAME into data points which has boggest impact on improving efficiency but costly and it requires adding third layer usong sigmoid activation function. 

# Summary: Summarize the overall results of the deep learning model. 


  Overall accuracy above 75% we are able to correctly classify each in th test 75% of the time. 
  And am applications has 80% chance of being succesful if they following thios: 

  Name of applications appears more than 5 times
  type of applications following T3 T4 T5 T6 T7 T8 T9 T10 T19
  application of dollowing classification.. 

#Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

  Random Forest
