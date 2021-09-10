# Machine learning based web application firewall

Machine learning based Web Application firewall for detection attacks such as SQL injections, XSS and shell script injections. 

Requirements:
 - Python 3.x
 - Jupyter notebook
 - Python libraries
   * Pandas
   * Numpy
   * Sklearn
   * matplotlib
   * seaborn
   * scipy

Classifiers tested using custom feature space:
 - AdaBoost
 - SGD classifier
 - MultiLayerPerceptron classifier
 - Logistic Regression
 - Support Vector Machine
 - Random forest
 - Decision Tree
 - Multinomial Naive Bayes

Follow along our development process in these notebooks:
 - ML_for_WAF.ipynb (All analysis, training, evaluation and saving models to pickles (not recommended to step through the training section, takes a long time))
 
 To run notebooks (they can also be read from github):
 1. Install jupyter notebook
 2. type in cmd: jupyter notebook <notebookfile.ipynb>
 3. step through each part of the notebook using Ctrl+Enter or from the toolbar

