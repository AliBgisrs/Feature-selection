# Feature-selection
If you want to do feature selection before training a machine learning model, this tool helps you

![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/c4dba35f-2a56-4c69-b7a7-898f6f7a6e48)

Project Title

[Feature Selection]

Description

[If you want to do feature selection before training a machine learning model, this tool helps you.]
  
Table of Contents

•	Installation
•	Usage
•	Contributing
•	License

Installation

ARCGIS PRO

[Download the tool and unzip its folder.]

[Go to the insert tab of your ArcGIS PRO project]

 ![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/f68fc613-6332-4ce2-9718-6f4cc0aa522e)

[Select add folder and browse to the folder that you have saved your script and add that folder]

[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of FeatureSelectionAli.atbx, then open it to find the script]
![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/39ef4a77-cc9e-463d-ae05-d6eb4058c8d5)

![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/19d957f7-501b-4835-9f2a-aa880a70e969)
  
 
You need to have an excel file that contain your predictor variables and also a column with the name of target that shows response varibale.

[Double click and open the script]

![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/705f2c02-043e-494d-b2c4-8177e997a69c)
 
[Call the input file (an excel dataset). Note: these tools work based on Random Forest, Lasso regression, and principal component analysis (PCA) methods.

 ![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/d36fbe39-f56d-4b73-ad66-40e631cacd47)


In this example, target column shows the value of lodging severity for dry pea and other columns work as predictor variables.

Usage

If you need to do feature selection , this tool helps you

![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/0c17298a-816c-48b1-918a-6aef38147f2d)

  
After running the tool, three excel files with the name of Lasso, PCA, and RFE can be seen in the output directory.

 ![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/98baf00d-0784-4863-8b96-51d60fb87475)

If you open that files, you can know about the importance of each variable to estimate the value of response variable. You need to do descending sort for feature importance column to see what variable play the most important role to predict the value of the response variable. 

 ![image](https://github.com/AliBgisrs/Feature-selection/assets/109620013/8a950802-604d-48c4-9fcd-355d5d36181f)

The interpretation of feature importance can vary depending on the algorithm used and the specific method for calculating feature importance.

Random Forest (RFE): The feature importance values provided by the Random Forest algorithm represent the total reduction in impurity (e.g., Gini impurity) that each feature contributes when used in the decision trees.

Lasso Regression: In Lasso regression, feature importance is often represented by the absolute values of the coefficients. These values indicate the magnitude of the effect of each feature on the target variable.

PCA: In Principal Component Analysis (PCA), the feature loadings indicate how much each feature contributes to each principal component. The loadings are orthogonal, and their squares represent the proportion of the variance explained by each component.

Contributing

[Please run the script, use it, and help me improve the performance of that script using your valuable suggestions.]
License

About the Author

[Developed by Aliasghar Bazrafkan.]

Acknowledgments

[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].

Contact

[Aliasghar.bazrafkan@ndus.edu]

Additional Notes

[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]

