# PROBLEM STATEMENT
Participants are expected to use ML models to predict welding defects in the materials by
developing algorithms using the provided parameters. Participants are free to use any
technique provided it is suited for the variety and volume of data provided.
The end goal of this competition is to enable the Godrej Aerospace team to produce
defect-free products every time.

# PROJECT AIM : 
Our project's aim is to do advanced analytics on welder’s details provided in the dataset and to build a model to predict defects before it occurs as per the input parameters.

# Brief Walkthrough of work done : 
●	 Cleaning and Preprocessing the data using necessary techniques. \
●	Getting insight from data by doing necessary EDA.\
●	Methods to determine welder’s performances:\
○	Visualisation Techniques – plots like histplot, countplot ,box-plots ,sub-plots ,pair-plots, frequency distribution  etc are used .\
○	Statistical Techniques :  pearson correlation , kendall correlation , p-values and heatmap for statistical visualisation  like redundancy , confusion matrix .\
●	SWEET SPOT ANALYSIS : \
○	Feature visualisation using various methods like U-Map and t-SNE for insight into how whole data is distributed over features . \
○	We have also thought of an idea , sorting and dividing each feature column into 10-20 equal subsets and doing separate analysis to find correlations and zooming/analysing over subsets having higher proportion of defect and non defect in them and going  iteratively to find the sweet spot of that feature .\
●	Using different technique to prepare data for training \
○	Splitting data for training and testing .\
○	Feature scaling (Standardisation like standard , quantile , robust scaler)the data to enable machine learning models to converge faster and also fit to distance based algorithms like svms , knns .\
○	Dealing with an imbalanced dataset to prevent overfitting using techniques like gaussian noise upsampling , SMOTE .\
●	Training dataset and evaluating accuracy :\
○	Fitting both original data and SMOTE generated data on various ML models like Decision Trees , Random Forest , Logistic Regression ,XGBoost , Gradient Boosting and SVMs also using cross validation techniques.\
○	Obtaining Classification report from both data to get insight of overfitting .

# CLASSIFICATION REPORT OF FEW ML MODELS :-
![image](https://github.com/ariesiitr/-WeldRight-IITBOMBAY-TECHFEST/assets/100424180/f2cff5a5-9642-4063-8ab6-fb3d1247aa6b)
![image](https://github.com/ariesiitr/-WeldRight-IITBOMBAY-TECHFEST/assets/100424180/6bb56e21-5e04-4be6-863b-59cee6184457)



# DATA PROVIDED
We have identified multiple parameters affecting the welding process and recorded the
dataset from past activities. Process parameters such as ambient temperature, weld job
temperature, humidity, voltage current, welding travel speed, shielding gas flow, and metal
composition. For advanced analytics machine data, welder details are provided.
# link to the data:-
https://docs.google.com/spreadsheets/d/1PifuLam1mMntrI0dPTWJosTYUWt8elwi/edit?usp=share_link&ouid=107098656021209623719&rtpof=true&sd=true

