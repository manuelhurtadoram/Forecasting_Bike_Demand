# Forecasting_Bike_Demand
This Capstone project of the Udacity Data Scientist Nanodegree Program builds a Multi-Layer Perceptron to estimate the proportion of bikes to cars (1) in any given day or hour of the years 2011 and 2012, for Washington D.C. data of a bike-sharing company. 

The aim of this project is to develop a model that allows these companies to better optimize their resource allocation by better predicting aggregate trends in bike usage, and therefore remaining more competitive and environmentally sustainable during growth. 

(1) The bike-to-car ratio is actually the ratio of company bikes used to cars in Washington, D.C. However, for the purpose of simplicity, the 'bike-to-car' term has been employed instead.


***Forecasting Bike Demand***

1. **Installations**

    - Uses Python 3.0
    
    - Other libraries used:
    
        - **Pandas**: https://pandas.pydata.org/pandas-docs/stable/)
        - **Numpy**: https://docs.scipy.org/doc/)
        - **Sci-Kit Learn**: https://scikit-learn.org/stable/documentation.html)
        - **Keras**: https://keras.io
        - **Matplotlib**: https://matplotlib.org
        - **Seaborn**: https://seaborn.pydata.org

2. **Project Motivation**

This project was completed as part of the Udacity Data Scientist Nanodegree program requirements.

Like all the projects related to machine learning that I have undertaken in the past, this model has important
real-life applications, since it can enhance the environmental impact that bike-sharing companies have on the environment by facilitating growth strategies that minimize the environmental footprint of the companies while at the same time maximizing the value to customers of these companies. 

3. **File Descriptions**

	1. **Data (folder)**:
  
      1. **Bike_Data (folder)**:
      
          1. *day.csv*: CSV file containing daily bike usage counts (of provider company) for Washington, D.C., in 2011 and 2012.
          2. *hour.csv*: CSV file containing hourly bike usage counts (of provider company) for Washington, D.C., in 2011 and 2012.
      
      2. **Oil_Data (folder)**:
          
          1. *wti-daily.csv*: CSV file containing daily WTI oil quotes for mid 1990s through 2018.
      
      3. **Traffic_Data (folder)**:
      
          1. *traffic_counts.json*: JSON file containing Annualized Average Daily Traffic measurements for devices scattered across the Washington, D.C. and surrounding areas.
      
      4. **Model_Weights (folder)**:
      
          1. *best_mlp_daily.best.hdf5*: Best weights for Multi-Layer Perceptron trained on daily dataset.
          2. *best_mlp_hourly.best.hdf5*: Best weights for Multi-Layer Perceptron trained on daily dataset.
		
4. **Acknowledgements**

This project was made possible with the knowledge I obtained from the Udacity Machine Learning Engineer Nanodegree and the Udacity Data Scientist Nanodegree. 

The day.csv and hour.csv data were made available by Fanaee-T, H., & Gama, J (2013), on behalf of the University of Porto's Laboratory of Artificial Intelligence and Decision Support. 

The wti-daily.csv data was made available by OpenHub.io.

The traffic_counts.json data was made available by Open Data D.C.
