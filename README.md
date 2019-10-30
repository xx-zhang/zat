## Bro Analysis Tools (BAT) [![travis](https://travis-ci.org/SuperCowPowers/bat.svg?branch=master)](https://travis-ci.org/SuperCowPowers/bat) [![codecov.io](http://codecov.io/github/SuperCowPowers/bat/coverage.svg?branch=master)](http://codecov.io/github/SuperCowPowers/bat?branch=master) [![supported-versions](https://img.shields.io/pypi/pyversions/bat.svg)](https://pypi.python.org/pypi/bat) [![license](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://choosealicense.com/licenses/apache-2.0) 

The BAT Python package supports the processing and analysis of Bro data
with Pandas, scikit-learn, and Spark

### Recent Improvements (Fall 2019):
- Better Docs (<https://supercowpowers.github.io/bat/>)
- Faster/Smaller Pandas Dataframes for large log files: [Large Dataframes](https://supercowpowers.github.io/bat/large_dataframes.html)
- Better Panda Dataframe to Matrix (ndarray) support: [Dataframe To Matrix](https://supercowpowers.github.io/bat/dataframe_to_matrix.html)
- Scalable conversion from Zeek logs to Parquet: [Zeek to Parquet](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Parquet.ipynb)
- Vastly improved Spark Dataframe Class: [Zeek to Spark](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Spark.ipynb)
- Updated/improved Notebooks: [Analysis Notebooks](#analysis-notebooks)


### BroCon 2017 Presentation

Data Analysis, Machine Learning, Bro, and You!
([Video](https://www.youtube.com/watch?v=pG5lU9CLnIU))

### Why BAT?

Bro already has a flexible, powerful scripting language why should I use
BAT?

**Offloading:** Running complex tasks like statistics, state machines,
machine learning, etc.. should be offloaded from Bro so that Bro can
focus on the efficient processing of high volume network traffic.

**Data Analysis:** We have a large set of support classes that help
bridge from raw Bro data to packages like Pandas, scikit-learn, and
Spark. We also have example notebooks that show step-by-step how to get
from here to there.


## Getting Started
- [Examples of Using BAT](https://supercowpowers.github.io/bat/examples.html)

### Analysis Notebooks

- [Zeek to Scikit-Learn](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Scikit_Learn.ipynb)
- [Zeek to Parquet](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Parquet.ipynb)
- [Zeek to Spark](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Spark.ipynb)
- [Spark Clustering](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Spark_Clustering.ipynb)
- [Zeek to Kafka](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Kafka.ipynb)
- [Zeek to Kafka to Spark](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Kafka_to_Spark.ipynb)
- [Clustering: Picking K (or not)](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Clustering_Picking_K.ipynb)
- [Anomaly Detection Exploration](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Anomaly_Detection.ipynb)
- [Risky Domains Stats and Deployment](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Risky_Domains.ipynb)
- [Zeek to Matplotlib](https://nbviewer.jupyter.org/github/SuperCowPowers/bat/blob/master/notebooks/Zeek_to_Plot.ipynb)


<img align="right" style="padding:25px" src="notebooks/images/SCP_med.png" width="160">

### Install

    $ pip install bat

### Documentation
<https://supercowpowers.github.io/bat/>


### About SuperCowPowers
The company was formed so that its developers could follow their passion for Python, streaming data pipelines and having fun with data analysis. We also think cows are cool and should be superheros or at least carry around rayguns and burner phones. <a href="https://www.supercowpowers.com" target="_blank">Visit SuperCowPowers</a>

