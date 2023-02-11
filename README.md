# Bird-Eye-View
The Bird's Eye View (BEV) technique is a cutting-edge approach for feature selection, particularly effective in dealing with high-dimensional data. The method's core objective is to identify and eliminate irrelevant features that could hinder machine learning models' accuracy. Removing unimportant features contributes significantly to the models' optimal fit and improve predictive power. The BEV approach has been extensively evaluated against other advanced feature selection methods, with consistently superior results in terms of model accuracy and selected numbers of features. The BEV methodology employs a combination of modern techniques, including evolutionary algorithms, Markov chain, reinforcement learning, and genetic algorithms, that synergistically improve its effectiveness. 

# Requirements
The following libraries are required to use the BEV methodology
* scikit_learn
* pandas
* numpy
* matplotlib

Note that specific versions of these libraries can be installed using the following command
```
pip install -r requirements.txt
```

Ensure that the command is executed in the root directory of the project. Additionally, it is recommended to install the required libraries in a virtual environment to maintain a clean and organized workspace.

# Instructions to use BEV

*	Clone the repository and install the necessary libraries.
*	Prepare the data file and specify its path in the BEV Python file, located at line number 20.
*	Run the BEV feature selection process by executing the following command.
```
python bev.py
```

*	Upon completion of the feature selection process, the selected feature files will be automatically saved in the "best features" folder, located in the root directory of the project.
*	The detailed statistics for each selected feature file, including the experiment number, stage number, accuracy, and number of features, will be embedded in the data file name, as illustrated in the image below ![Screenshot](best features files img.png) 
