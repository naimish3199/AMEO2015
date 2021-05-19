# AMEO2015
The aim of this project is to recognize important factors that influences job success for engineers in India . The trends and patterns in the data are analysed and visualized to aid the design and development of machine learning models that would predict the job salary of a graduate . Aspiring Minds’ Employability Outcomes (AMEO) 2015 dataset is analysed and pre-processed for the machine learning pipeline to build machine learning models which will be able to predict the salary of an engineering graduate given his credentials . Standard data analytics and visualizations are used to understand and prepare the data. The data is cleaned of unnecessary attributes . The categorical features are encoded using one-hot encoding scheme. For categorical classification , the target points are placed into class bins based on quantile distribution . These methods help feature engineering to enable a good enough prediction ability . Detailed analysis is available in Report.pdf .

Salaries are divided into classes on basis of 0 , 20 , 40 , 60 , 100 percentile values of Column 'Salary'

* Class 1 contains (34999.999, 180000.0]
* Class 2 contains (180000.0, 240000.0]
* Class 3 contains (240000.0, 325000.0]
* Class 4 contains (325000.0, 400000.0]
* Class 5 contains (400000.0, 4000000.0]
