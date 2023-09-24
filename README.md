# GPS-clustering-and-analysis
Preprocessing the GPS data according to the algorithm and clustering it using kmeans clustering algorithm and using random forest regression algorithm. Analysing the traffic data and plotting the accurate results on the map gets the appropriate traffic analysis with the mobility pattern obtained on the map.
this obtained mobility patterns helps the taxi drivers in analysing the traffic.
Dataset:

Functions and techniques used in the source code:
1.	OneHotEncoder(handle_unknown='ignore')
A pre-processing technique called the OneHotEncoder(OHE) is used to convert categorical data to numerical data that may be used in machine learning models. If there are unseen categories in the test data (categories that weren't included in the training data), the encoder will ignore them rather than generating an error because the handle_unknown parameter is set to 'ignore'.

3.	scaler.fit_transform(X)
The method call scaler.fit_transform(X) scales the input data X using the StandardScaler instance scaler and returns the scaled data.

5.	kmeans.fit(X)
It is a method call that fits the KMeans clustering algorithm to the input data X.

6.	ax.scatter()
It is a method of an Axes object, which is a container that holds the plot elements in Matplotlib. It is used to create a scatter plot of data points on the Axes.

7.	fig.add_subplot()
It a function in Matplotlib, a plotting library for Python. It is used to add a new subplot to    a Matplotlib figure.

8.	plt.scatter()
It a function in Matplotlib, a plotting library for Python. It is used to create a scatter plot of x-y pairs.

9.	np.unique()
It a function in the NumPy library for Python. It is used to find the unique elements in an array.

10.	final_train.query()
final_train is assumed to be a Pandas DataFrame object. Thequery() method of a Pandas DataFrame is used to filter the rows of the DataFrame based on a boolean expression 

11.	sns.distplot()
It is a function in the Seaborn library, which is a popular data visualization library for Python.  It is used to create a histogram with a density curve overlaid on top.


12.	axs.flatten()
It is a method to flatten a NumPy array of subplots into a one-dimensional array.


13.	axs[i].set_title()
It is a method that sets the title of a subplot in a Matplotlib figure.

14.	MultiOutputRegressor(RandomForestRegressor(n_estimators=100, random_state=1))
It uses random forest regression as the primary estimator to build a multi-output regression model. For reproducibility, the RandomForestRegressor(RFR) function call specifies the random seed (random_state) and the number of decision trees in the forest (n_estimators).  The MultiOutputRegressor(MOR) function uses this as a parameter and builds a wrapper for the random forest regressor to support multi-output regression.

15.	forest.predict()
It is a method in scikit-learn used to predict the output of a machine learning model, specifically a random forest regressor.

