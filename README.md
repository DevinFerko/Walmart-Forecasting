# Walmart-Forecasting

## Built Using :
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" title="pandas" alt="pandas" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="numpy" alt="numpy" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" title="jupyter" alt="jupyter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" title="Github" alt="Github" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="vscode" alt="vscode" width="40" height="40"/>&nbsp;
</div>

## 1. Project Summary <a class="anchor" id="projectsummary"></a>

#### 1.1 Project Background <a class="anchor" id="projectbackground"></a>
Inspiration for this project came from [**Help Walmart Predict Manage Inventory**](https://www.kaggle.com/competitions/dsedelhi) contest held by Kaggle. This contest was shut on 30/May/2019 but I thought it would serve as an excellent opportunity to improve my skills in Python, Machine Learning, and SQL. The premise for this contest was to use historical sales data to forecast future sales of products. Sale forecasting has a strong influence on the performance of a company's success, therefore proper analysis of this data is crucial for the company's performance in the coming year. The accurate forecast will lead to better business decisions and help the retailer to take the necessary steps and measures to plan their yearly budgets and investments. 

For this Case Study I decided to ask the following questions:
* Whether the size of the store had an affect on sales?
* Which days had the highest sales?
* Conclude whether the weather has an essential impact on sales.
* Do the sales always rise near the holiday season for all the years?

#### 1.2 Dataset <a class="anchor" id="dataset"></a>
As the contest has been shut for 4 years, the dataset offered by Kaggle was no longer available to the public. After searching for a similar dataset I decide on using the  [**Walmart Recruiting Store Sales Forecasting**](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting) dataset made available through Kaggle. This dataset contains four separate CSV files named features, stores, test, and train. All four csv files can be linked by the first column labelled 'Store'. Also, this dataset focuses on data collected between 2010-02-05 to 2013-12-30. The key dates in between that time frame are as follows:
* Super Bowl: 07-Feb-10, 06-Feb-11, 05-Feb-12, 03-Feb-13
* Labor Day: 06-Sep-10, 05-Sep-11, 07-Sep-12, 02-Sep-13
* Thanksgiving: 25-Nov-10, 24-Nov-11, 22-Nov-12, 28-Nov-13
* Christmas: 25-Dec-10, 25-Dec-11, 25-Dec-12, 25-Dec-13

## 2. Objectives <a class="anchor" id="objectives"></a>​
#### 2.1 Main Objective <a class="anchor" id="mainobjective"></a>
The main objective of this case study is to predict future sales for Walmart retail stores. As the datasets give us access to information such as weather, whether or not the sales day was a holiday, the price of fuel, and unemployment rates, we will also examine if any of these affect sales.
