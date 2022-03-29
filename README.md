# ApacheSpark
spark-timeseries is a Scala / Java / Python library for interacting with time series data on Apache Spark.
Time-series are an important part of data science applications, but are notoriously difficult in the context of distributed systems, due to their sequential nature. Getting this right is therefore a challenging but important element of progress in the universe of distributed systems applied to data science.


Introducing Flint: A time-series library for Apache Spark

Time Series Analysis



Time series analysis has two components: time series manipulation and time series modeling.

Time series manipulation is the process of manipulating and transforming data into features for training a model. Time series manipulation is used for tasks like data cleaning and feature engineering. Typical functions in time series manipulation include:

Joining: joining two time-series datasets, usually by the time
Windowing: feature transformation based on a time window
Resampling: changing the frequency of the data
Filling in missing values or removing NA rows.
