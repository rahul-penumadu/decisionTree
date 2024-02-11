# Predicting Term Deposit Subscriptions

Features:
age --> age
job --> type of Job
marital --> marital status
education --> highest education finished
default --> already has credit in default?
balance --> account balance
housing --> taken housing loan?
loan --> taken personal loan?
contact --> communication via...
day --> day of last contact
month --> month of last contact
duration --> duration of last contact
campaign --> number of contacts made to the client during the campaign
pdays --> number of days that passed by after the client was last contacted from a previous campaign (999 means client wasn't previously contacted)
previous --> number of contacts performed before this campaign and for this client
poutcome --> outcome of the previous marketing campaign

Target variable:
y --> has the client subscribed a term deposit?


Usage
Run the 'decision_tree_classification.ipynb' Jupyter Notebook to execute the code step by step.
Adjust parameters and experiment with different settings as needed.

File Structure
decision_tree_classification.ipynb: Jupyter Notebook containing the decision tree classification code.
dataset_DT.csv: CSV file containing the dataset.
myTree.png: Decision tree visualization image.

Data Preprocessing
Handling missing values.
Converting categorical features to numerical using Label Encoding.
Creating new features ('age_group').

Visualization
Utilizing seaborn and matplotlib for data visualization.
Displaying count plots for various features.

Model Training and Evaluation
Splitting the dataset into training and testing sets.
Training Decision Tree Classifier with Gini impurity and Entropy.
Evaluating the models using confusion matrices and classification reports.

Results
Comparing the performance of models with Gini impurity and Entropy.
Visualizing the decision tree with a depth of 5.
