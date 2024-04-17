
![Logo](https://github.com/kiranjorwekar/Linear-Regression-using-California-Dataset/blob/main/Linear_Regression_using_CalHousingData.jpg)


# Project Title - "Traffic Volume Prediction using - HistGradientBoostingRegressor Model".

An assignement to find prediction on Traffic Volume Dataset with the available Train Dataset & Test dataset using "HistGradientBoostingRegressor" model. Actually this hackathon is based on any model to be implemented which gives a more and valid results when you predict on the test dataset with MSE(Mean Square Error) values.

It's a basic level of finding very latest or you can say a 'Baseline' dataset using this example.

Let's understand about some basic details about the - HistGradientBoostingRegressor is a variant of the Gradient Boosting algorithm implemented in scikit-learn, specifically optimized for large datasets. It uses histogram-based algorithms for efficient computation, making it faster and more memory-efficient compared to traditional gradient boosting implementations.


## Implementation Details

- Dataset: test_set_nogt.csv, train_set_dirty.csv
- Model: [HistGradientBoostingRegressor]- (https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html#sklearn-ensemble-histgradientboostingregressor)
- Input: features columns - traffic_volume | holiday |	temp | rain_1h | snow_1h | clouds_all | weather_main | weather_description | date_time

- Output: traffic volume data prediction.

## Dataset Details

This dataset was obtained from Kaggle repository as a part of Hackathon conducted by "123 of AI Presents"([Link](https://www.kaggle.com/competitions/123ofai-predict-the-traffic-volume))


- [Traffic Volume Prediction](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.HistGradientBoostingRegressor.html#sklearn-ensemble-histgradientboostingregressor)
- 30415 samples
- 9 Input Features: *Data columns (total 9 columns)*:  
	* 1**holiday**: Categorical US National holidays plus regional holiday, Minnesota State Fair.  
	* Item2**temp**: Numeric Average temp in kelvin.   
	**rain_1h**: Numeric Amount in mm of rain that occurred in the hour.  
	**snow_1h**: Numeric Amount in mm of snow that occurred in the hour.    
	**clouds_all**: Numeric Percentage of cloud cover.   
	**weather_main**: Categorical Short textual description of the current weather.  
	**weather_description**: Categorical Longer textual description of the current weather.  
	**date_time**: DateTime Hour of the data collected in local CST time.   
	**traffic_volume**: Numeric Hourly I-94 ATR 301 reported westbound traffic volume.   
	
 #   Column               Non-Null Count  Dtype  
---  ------               --------------  -----  
 0   traffic_volume       27411 non-null  float64
 1   holiday              27377 non-null  object 
 2   temp                 27395 non-null  float64
 3   rain_1h              27488 non-null  float64
 4   snow_1h              27404 non-null  float64
 5   clouds_all           27350 non-null  float64
 6   weather_main         27360 non-null  object 
 7   weather_description  27392 non-null  object 
 8   date_time            30414 non-null  object

## Evaluation and Results
After 

| Metric        | Value         |
| ------------- | ------------- |
| R2 Score      | 0.080653      |
| MSE           | 3389.184      |
 

## Key Takeaways

It's a basic model as a part of hackthon I have created but for MSE score is not really very good, hence we will wait for further solution and correct model of the same will be updated in this to confirm and correct understanding as a part of learning with "123 of AI" team.


## How to Run

The code is built on Google Colab on an iPython Notebook. 

```bash
Simply download the repository, upload the notebook and dataset on colab, and hit play!
```


## Roadmap

Will continue learning and evolving further model with different dataset. Will provide the details for further learnings. Thanks!


## Libraries 

**Language:** Python

**Packages:** Sklearn, Matplotlib, Numoy, Pandas, Seaborn


## FAQ

#### How does the linear regression model work?

Linear regression is a statistical method used to model the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the independent and dependent variables. The goal of linear regression is to find the best-fitting straight line that describes the relationship between the variables.
It will be analyzed using - 
1. Data Collections
2. Scatterplot
3. Model Representation - which means relationship between Independant variable (X) and the dependent variable (Y)

#### How do you train the model on a new dataset?

Training a regression model for a datataset based on -
1. Data Processing - Prepare the new dataset for traning by perfromaing necessary pre-processing steps like -  handling missing values, scaling or normalizing features and spliting the data into training and testing sets.
2. Model Selection - Decide whether to use Linear Regression Model or multiple regression model(means multiple independent variables). This is completely dependent on the nature of data and releationship between variables.
3. Model traning - Estimating the coefficients that best fit the data using a method of least squares.
4. Model Evalutions
5. Fine-tuning of fetures .. etc 

#### What is the traffic volume data prediction?

Traffic prediction means forecasting the volume and density of traffic flow, usually for the purpose of managing vehicle movement, reducing congestion, and generating the optimal (least time- or energy-consuming) route.


## Acknowledgements

All the links, blogs, videos, papers you referred to/took inspiration from for building this project. 

 - [Blog around the Traffic predictions](https://www.altexsoft.com/blog/traffic-prediction/)
 - [A good read to understand](https://www.mdpi.com/2076-3417/14/6/2285)
 - [IEEE Blog details](https://ieeexplore.ieee.org/document/8853429)


## Contact

If you have any feedback/are interested in collaborating, please reach out to me at kiran2777@rediffmail.com


## License



