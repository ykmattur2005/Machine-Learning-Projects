# Project 1: EDA (Exploratory Data Analysis) In Python
I utilized my newly learned skills in Python to develop a short data analysis of a set of data that described income and expense (CSV file: Inc_Exp_Data.csv). I then used that data to find correlations between different values (such as level of education, amount of rent, etc) that determined what caused differences in income and expense amongst different groups of people. 

I used distribution analysis for income to find that in most cases, it’s generally skewed, with most people in low-income and few people with a high income. Then, I used graphical analysis to show how at low income levels, expense levels are usually pretty predictable (high correlation) but at high income levels, expense levels generally get higher, but the correlations decrease (in other words, people with high income don’t necessarily need to spend more).

This data analysis could effectively be used by large money-handling companies (such as credit card companies, banks, or insurance agencies) to target specific audiences and develop models of their own to predict spending in the recipients of their services.

Self-taught myself Python from Udemy course. The code was completed and compiled through Jupyter Notebook. (File name: Income Data EDA Analysis.ipynb). I have also posted the code as a .py, .html, and .pdf file.

# Project 2: Creating and Implementing an ML Model through Tensorflow and Arduino 
 
Using a data set received from WWO (World Weather Online), I was able to retrieve data from a specific area in the world (I chose Canazei, Italy for its unique altitude and climate in order to get specific temperature and humidity values useful for predicting variable types of weather). Then, using the Tensorflow library, I created a ML model that I used to predict, given a certain pressure and humidity, whether it would snow.

I used the TinyML cookbook to learn basic Machine Learning principles in order to familiarize myself with data analysis. The code that I used can be found here: https://github.com/PacktPublishing/TinyML-Cookbook/blob/main/Chapter03/ColabNotebooks/preparing_model.ipynb

Once I created the machine learning model, I coded a program in Arduino using C and used the Arduino Nano BLE to collect input data from my surroundings (namely, temperature and humidity) to determine whether it would snow. This is incredibly applicable, since if an ML model can take in input from temperature data and be used to predict weather, it can be replicated for other use cases, for inputting past references to data in order to predict future occurrences of scenarios, simply by using the ML model and some basic input.

I purchased the Arduino Nano BLE sensor from https://store.arduino.cc/products/arduino-nano-33-ble, and I used the Arduino editor https://create.arduino.cc/editor to develop, compile, and run my code. This code is in the Github file as ArduinoCode.c, and it uses Tensorflow to utilize the ML model.


