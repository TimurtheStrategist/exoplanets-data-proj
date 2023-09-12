# exoplanets-data-proj
This project involves working with Kepler Objects of Interest (KOI) dataset (data from Kepler telescope) from NASA Exoplanet Achive and creating a machine learning model for predicting whether the object is an exoplanet candidate or a false positive of an observation. 
Link to the dataset: [link](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative)
Link to columns description: [link](https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html)

I used NumPy, Pandas, Matplotlib, Seaborn, scikit-learn and Keras libraries. Initially, I cleared the dataset to prepare it for machine learning prediction. Next, I performed train-test-split and used decision trees to determine what features will be the most important in the prediction. After that, I built a neural network for binary classificaton and achieved an accuracy score of 0.93. This is a decent result, which means the algorithm can be used further for determining the nature of objects in space.
 
