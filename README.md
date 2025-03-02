<img width="1384" alt="210127415-b2067d99-45e5-4806-b9d9-723b1cbcea70" src="https://user-images.githubusercontent.com/96717126/235229273-ee9d050e-9910-4462-bebe-ff5b8dd1b94a.png">

# Project Summary :-
**Mobile phone companies aim to analyze sales data and determine the factors that drive prices in the competitive market. They seek to establish a relationship between a phone's features, such as RAM and internal memory, and its selling price range. The objective is to classify the price range as high or low, rather than predicting the exact price.**

# Objective :
- **Our objective is to predict the price range of a mobile phone by building a model that takes into account various features provided in the dataset. We will be using supervised learning methods such as XG Boost, Random Forest, Logistic Regression	, KNN, Gradient Boosting and Support Vector Machine (SVM) to determine the best model for this problem.**

# Dataset info :
- **1.Number of records: 2,000**
- **2.Number of features: 21**

# The dataset contains features like :
- **`Battery_power`: Total energy a battery can store in one time measured in mAh**
- **`Blue:`  Has bluetooth or not**
- **`Clock_speed:` speed at which microprocessor executes instructions**
- **`Dual_sim:` Has dual sim support or not**
- **`Fc:` Front Camera mega pixels**
- **`Four_g:` Has 4G or not**
- **`Int_memory:` Internal Memory in Gigabytes**
- **`M_dep:` Mobile Depth in cm**
- **`Mobile_wt:` Weight of mobile phone**
- **`N_cores:` Number of cores of processor**
- **`Pc:` Primary Camera mega pixels**
- **`Px_height:` Pixel Resolution Height**
- **`Px_width:` Pixel Resolution Width**
- **`Ram:`  Random Access Memory in Mega**
- **`Touch_screen:`  Has touch screen or not**
- **`Wifi:`  Has wifi or not**
- **`Sc_h:`  Screen Height of mobile in cm**
- **`Sc_w:`  Screen Width of mobile in cm**
- **`Talk_time:`  longest time that a single battery charge will last when you are not**
- **`Three_g:`  Has 3G or not**
- **`Wifi:`  Has wifi or not**

# Target Variable :
- **`Price_range:`  This is the target variable with value of 0(low cost), 1(medium cost),2(high cost) and 3(very high cost).**

# Algorithms Used For ML Model Implementation :-
- **`Logistic Regression`**
- **`Random Forest`**
- **`XG Boost`**
- **`k-nearest neighbors`**
- **`Support Vector Machine`**
- **`Gradient Boosting`**

# Conclusion :-
- **We began by gaining an understanding of the data, performing data wrangling, and conducting basic exploratory data analysis. During this phase, we identified relationships and trends between the price range and other independent variables..**
-  **To determine the most effective features for predictive modeling, we utilized the K-best feature selection method with Chi-square statistic.**
-  **In line with our primary goal of predicting the mobile price range, we identified Logistic Regression and Support Vector Machine as the top-performing models among the various models tested, which included Decision Tree, Gradient Boosting, K-Nearest Neighbors, Random Forest, and XGBoost.**
- **Out of the models we tested on our dataset, the K-Nearest Neighbors model was found to be the least effective performer.**
- **We assessed the feature importance of each model and found that RAM, battery power, px_height, and px_width were the most significant contributors in predicting the price range.**


