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

What variable(s) are considered the target(s) for your model?
Checking to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column is the feature chosen for this dataset.

What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
In the optimized model, layer 1 started with 120 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation. From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons).
