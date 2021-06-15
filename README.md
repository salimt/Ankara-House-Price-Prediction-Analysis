
# Ankara-House-Price-Prediction-Analysis

<center><img src="https://i.imgur.com/Co6gvzM.png" alt="drawing" width=300/></center>

The objective of the project is to perform data visulalization techniques to understand the insight of the data. Machine learning often required to getting the understanding of the data and its insights. This project aims apply various [Python](https://www.python.org/) tools to get a visual understanding of the data and clean it to make it ready to apply machine learning opertation on it.

## Installation
This is an exe file. Package requirements are included in requirement.txt. This project uses Python 3.9.
Run the following command in terminal to install the required packages. 
`pip3 install -r requirements.txt` 

## Usage
The app includes all the markdowns which explain the process. 

## Data-set examination
#### The data-set is in CSV format that includes:
* The train data-set has 21980 samples, 40 features and 1 target variable.
* The test data-set has 9420 samples and 40 features.
* The target variable is the sale price.

## Data-set pre-processing
The heat-map showed the correlation of each variable with another. The darker colour means the relationship between any two variables are strongly correlated and lighter colour means they have almost no relationship.
<center><img src="https://i.imgur.com/iLwapum.png" alt="drawing" width=500/></center>

#### The coefficient of determiantion that highly correlated to 'SalePrice' from heat-map shown below:
<center><img src="https://i.imgur.com/ElD4zUs.png" alt="drawing" width=500/></center>

## Summary
<img src="https://i.imgur.com/Qgb9ukj.png" alt="drawing" width="400"/>
<img src="https://i.imgur.com/vYFtgXK.png" alt="drawing" width="400"/>
After the result comparison, I still need to put more effort to improve the model. The result reflects that some of the valuable data might not yet to be discovered from the dataset. Probably need to review all the missing data, outliers, also, spend more time on data analysis and multicollinearity issue.

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :)

## Authors
This repo is maintained by salimt.