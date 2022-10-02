# Car Resale Value Prediction  <img src="https://media.giphy.com/media/XAaKkXYRd7858X8G7I/giphy.gif" width="120px">

With difficult economic conditions, it is likely that sales of second-hand imported (reconditioned) cars and used cars will increase. 
In many developed countries, it is common to lease a car rather than buying it outright. After the lease period is over, the buyer has the possibility to buy the car at its residual value, i.e. its expected resale value. 
Thus, it is of commercial interest to sellers/financers to be able to predict the salvage value (residual value) of cars with accuracy.

In order to predict the resale value of the car, we proposed an intelligent, flexible, and effective system that is based on using regression algorithms. 
Considering the main factors which would affect the resale value of a vehicle a regression model is to be built that would give the nearest resale value of the vehicle. We will be using various regression algorithms and algorithm with the best accuracy will be taken as a solution, then it will be integrated to the web-based application where the user is notified with the status of his product.

# Technical Architecture <img src="https://media3.giphy.com/media/BtVpIOi3doaz3RE5w4/giphy.gif?cid=ecf05e47rkw5pzp7hc9nz6ue1646xz5f4s8ucn1gp6omn9d5&rid=giphy.gif&ct=s" width="30px">

![image](https://user-images.githubusercontent.com/67733463/190889435-b2fd85ff-d147-4650-baa6-4f6f2532b5c3.png)

# Project Objectives<img src="https://media.giphy.com/media/U1anBXfZ4wmKoGsIMG/giphy.gif" width="40px">
* To understand the problem to classify if it is a regression or a classification kind of problem.

* To know how to pre-process/clean the data using different data pre-processing techniques.

* Applying different algorithms according to the dataset 

* To know how to evaluate the model.

* To build web applications using the Flask framework.

# Project Flow  <img src="https://static10.lottiefiles.com/images/v3/industry-standard/animation.gif" width="50px">


* The user interacts with the UI (User Interface) to enter the input features

* Entered input features are analyzed by the model which is integrated

* Once the model analyses the input, the prediction is showcased on the UI

To accomplish this, we have to complete all the activities and tasks listed below
Download the dataset.

1. Preprocess or clean the data.

2. Analyze the pre-processed data.

3. Train the machine with preprocessed data using an appropriate machine learning algorithm.

4. Save the model and its dependencies.

5. Build a Web application using Flask that integrates with the model built.

# Pre-Requisites <img src="https://media.giphy.com/media/mFjYHowKIQxRoGVSJy/giphy.gif" width="80px">
In order to develop this project we need to install the following software/packages:


Step 1:

Anaconda Navigator :

Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning related applications. It can be installed on Windows, Linux, and macOS. Conda is an open-source, cross-platform,  package management system. Anaconda comes with great tools like JupyterLab, Jupyter Notebook, QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. 

For this project, we will be using Jupyter notebook and Spyder

Step 2:

To build Machine learning models you must require the following packages

Sklearn: 

Scikit-learn is a library in Python that provides many unsupervised and supervised learning algorithms.

NumPy: 

NumPy is a Python package that stands for 'Numerical Python'. It is the core library for scientific computing, which contains a powerful n-dimensional array object  

Pandas: 

pandas is a fast, powerful, flexible, and easy to use open-source data analysis and manipulation tool, built on top of the Python programming language.  

Matplotlib: 

It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits

Flask: 

Web framework used for building Web applications. 

If you are using anaconda navigator, follow the below steps to download the required packages:

Open anaconda prompt.
Type “pip install numpy” and click enter.
Type “pip install pandas” and click enter.
Type “pip install matplotlib” and click enter.
Type “pip install scikit-learn” and click enter.
Type “pip install Flask” and click enter.

If you are using Pycharm IDE, you can install the packages through the command prompt and follow the same syntax as above.
