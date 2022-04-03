# Neural_Network_Charity_Analysis

# Overview of the Project

Beks is a data scientist and a programmer for a non-profit foundation Alphabet Soup. They are philantropist foundation dedicated to helping organisations that protect the environment and help people's wellness and unify the world.

Alphabet soup has raised and donated over ten billion dollars in the past twenty years. This money has been used to invest in a life saving technologies.Beks is in charge of data collection and analysis for the entire organization. Her job is to analyse the impact of the donation and vet potential recipients.These helps insure that the foundation money is been used effectively. Unfortunately not every donation the company made is impactful.

In some cases an organisation will take the money and disappear.As a result, Alphabet Soup top management has asked Beks to pridict which organaztion are worth donating to and which are too high risk.He wanted her to create mathematical data driven solution that can do this accurately.

I was approached to help Beks learn about Neural Network Model and how to design and train these models using the python tensorflow library.

This project is out to create a robust Deep Neural Network capable of interpreting large complex datasets.These models will he

## Sources And Tools

Data source: It is a CSV file with more than 34000 organizations.
Technologies:Matplotlib,visual studio code,python tensorflow library,pandasand nunpy.

# Results

## Data Preprocessing

1. What variable(s) are considered the target(s) for your model?
   Checking to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

2. What variable(s) are considered to be the features for your model?
   The IS_SUCCESSFUL column is the feature chosen for this dataset.

![Is_successful](https://github.com/femiimam001/Neural_Network_Charity_Analysis/blob/main/Resources/Is-_successful.PNG)

3. What variable(s) are neither targets nor features, and should be removed from the input data?
   The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.

![Ein_name](https://github.com/femiimam001/Neural_Network_Charity_Analysis/blob/main/Resources/Ein_name.PNG)

4. # Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized model, layer 1 started with 120 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation. From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons).

![Optimized_neural_model](https://github.com/femiimam001/Neural_Network_Charity_Analysis/blob/main/Resources/Optimized_neural_model.PNG)

5. Were you able to achieve the target model performance?
   The target for the model was 75%, but the best the model could produce was 72.7%.

6. What steps did you take to try and increase model performance?
   Columns were reviewed and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. Other activations were tried such as tanh, but the range that model produced went from 40% to 68% accuracy. The linear activation produced the worst accuracy, around 28%. The relu activation at the early layers and sigmoid activation at the latter layers gave the best results.

   ![target_model_performance](https://github.com/femiimam001/Neural_Network_Charity_Analysis/blob/main/Resources/target_model.PNG)
