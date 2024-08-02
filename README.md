<!-- PROJECT LOGO -->
<br />
<h1 align="center">CREDIT RISK ANALYSIS</h1>
<p align="center">
  <a href="https://github.com/kp-stats/Credit-Risk-ML-Project/">
   <img src="resources\credit.gif" alt="Description of the GIF" width="300" height="150">
  </a>

  <p align="center">
    
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#dependencies">Dependencies</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#authors">Authors</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
<h3> Problem Statement</h3> 
<p align="center"> <img src="resources\problem.gif" alt="method" width="300"  height="150"></p>
<p>
This project aims to analyze credit risk using a dataset containing various financial and demographic attributes. The analysis includes cleaning, exploring, and modeling data to predict credit risk. The objective is to identify key factors that influence creditworthiness and develop a predictive model for assessing risk levels.</p>

<p><h3>Dataset Description</h4>
The dataset consists of multiple features related to the financial behavior and demographics of individuals.
<p>Key columns include</p>
<ul><li><b>pct_tl_open_L6M:</b>Percent of accounts opened in the last 6 months</li>
<li><b>pct_tl_closed_L6M :</b> Percent of accounts closed in the last 6 months</li>
<li><b>pct_active_tl :</b> Percent of active accounts</li>
<li> <b>Total_TL_opened_L12M :</b> Total accounts opened in the last 12 months</li>
<li><b>Tot_TL_closed_L12M :</b> Total accounts closed in the last 12 months</li>
<li><b>Tot_Missed_Pmnt :</b> Total missed payments</li>
<li><b>Auto_TL, CC_TL, Consumer_TL, Gold_TL, Home_TL, PL_TL :</b> Counts of different types of loan accounts</li>
<li><b>Age_Oldest_TL :</b> Age of the oldest opened account</li>
<li><b>max_delinquency_level :</b> Maximum delinquency level</li>
<li><b>ARITALSTATUS, EDUCATION, GENDER :</b> Demographic information</li>
<li><b>NETMONTHLYINCOME :</b> Net monthly income</li>
<li><b>Approved_Flag : </b>Indicator for priority levels</li></ul>
</p>

## Methodology

<p align="center"> <img src="resources\METHOD.gif"  alt="method" width="300" height="150"></p>

<ul>
<li><b>Data Cleaning:</b> Handling missing values and data inconsistencies.</li>
<li><b>Exploratory Data Analysis (EDA):</b> Visualizing data distributions, relationships, and trends.</li>
<li><b>Feature Selection:</b> Selecting and Transforming existing ones for better model performance.</li>
<li>Building predictive models using machine learning algorithms to classify or score credit risk.</li>
<li><b>Hyperparametric Tunning:</b> This process involved systematically adjusting key parameters within the models to identify the best combination for accuracy and efficiency. Techniques such as Grid Search and Random Search were utilized to explore a range of hyperparameter values.</li>
<li><b>Cross-validation</b> was implemented to ensure the robustness and generalizability of the models. The optimized parameters helped in enhancing the model's predictive power, reducing overfitting, and improving overall model performance on unseen data.</li>
<li><b>Evaluation:</b> Assessing model performance using appropriate metrics.</li></ul>

## Results

<p align="center"><img src="resources\result.gif" alt="result" width="300" height="150"></p>

<p>The analysis identifies key factors that contribute to credit risk, such as account activity, delinquency history, and financial behavior. The predictive model helps in assessing the risk levels of individuals, providing a valuable tool for financial institutions. According to the risk appetite of the business, we will make recommendations.</p>

### Dependencies
* Python 3.11.5
* Pandas 2.0.3
  ```sh
  pip install pandas
  ```
<!-- Authors -->
## Authors

1) Kartik Pandey - [Linkedin](https://www.linkedin.com/in/kpstats/) - https://www.linkedin.com/in/kpstats/

2) Tejaswi Raj - [Linkedin](https://www.linkedin.com/in/tejaswi-fin) - https://www.linkedin.com/in/tejaswi-fin

3) Surbhi Sharma - [Linkedin](https://www.linkedin.com/in/s-s-stats/) - https://www.linkedin.com/in/s-s-stats/

## Thank you

