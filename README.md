# Diabetes Classification with XGBoost
This project is the implementation of a classifier for diabetes, which uses the ```XGBoost``` library to train the model.</br>
After training, the model should decide whether a person has diabetes disease or not.

## Diabetes Dataset
The [dataset](https://github.com/arminZolfaghari/Data-Mining-XGBoost/blob/main/diabetes.csv) includes more than 70000 records that have been collected from patients. </br>
Dataset has 22 columns: </br>
`Diabetes_binary`, `HighBP`, `High Cholesterol`, `Cholesterol Check`, `BMI`, `Smoker`,
`Stroke`, `HeartDiseaseorAttack`, `Physical Activity`, `Fruits`, `Veggies`, `Heavy Alcohol Consumption`,
`Any Health Care`, `No Doctor because of Cost`, `General Health`, `Mental Health`, `Physical Health`, `Difficulty Walking`, `Sex`, `Age`, `Education`, `Income`.
</br>

## XGBoost
XGBoost is a ```decision-tree-based``` ensemble Machine Learning algorithm that uses a ```gradient-boosting``` framework.
In prediction problems involving unstructured data (images, text, etc.), artificial neural networks tend to outperform all other algorithms or frameworks.
However, when it comes to small-to-medium structured/tabular data, decision tree-based algorithms are considered best-in-class right now.

[Project](https://github.com/arminZolfaghari/Data-Mining-XGBoost/blob/main/DM_XGBoost.ipynb) has 6 steps:
1. Import libraries
2. Getting the data
3. Preprocessing: load dataset, rename column names, handle ```Null``` values, normalize, and convert categorical features to numerical features with ```OneHotEncoding``` and ```Min-Max```.
4. Build XGBoost classifier model: create a ```XGBClassifier```, train the model, print accuracy, plot ```confusion_matrix```, and plot ```precision-recall``` curve.
5. Set hyperparameters (use GridSearchCV)
6. Visualization

Check the full [description](https://github.com/arminZolfaghari/Data-Mining-XGBoost/blob/main/DataMining_Project.pdf) (in Persian)
</br>
## Contact
If you have any questions, feel free to ask me: </br>
:envelope_with_arrow:		arminzolfagharid@gmail.com
