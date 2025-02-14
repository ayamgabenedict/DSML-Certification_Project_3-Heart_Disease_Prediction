# Heart Disease Prediction Documentation - Project #3

## Context

Heart Disease is among the most prevalent chronic diseases in the United States, impacting millions of Americans each year and exerting a significant financial burden on the economy. In the United States alone, heart disease claims roughly 647,000 lives each year — making it the leading cause of death. The buildup of plaques inside larger coronary arteries, molecular changes associated with aging, chronic inflammation, high blood pressure, and diabetes are all causes of and risk factors for heart disease.

While there are different types of coronary heart disease, the majority of individuals only learn they have the disease following symptoms such as chest pain, a heart attack, or sudden cardiac arrest. This fact highlights the importance of preventative measures and tests that can accurately predict heart disease in the population prior to negative outcomes like myocardial infarctions (heart attacks) taking place.

The Centers for Disease Control and Prevention has identified high blood pressure, high blood cholesterol, and smoking as three key risk factors for heart disease. Roughly half of Americans have at least one of these three risk factors. The National Heart, Lung, and Blood Institute highlights a wider array of factors such as Age, Environment and Occupation, Family History and Genetics, Lifestyle Habits, Other Medical Conditions, Race or Ethnicity, and Sex for clinicians to use in diagnosing coronary heart disease. Diagnosis tends to be driven by an initial survey of these common risk factors followed by bloodwork and other tests.

## Heart Disease Prediction

**“AIHealth”** is a new age startup laying foundations in the healthcare
domain by solving some of the most prominent problems by using Data
Science and Machine Learning. They are using a lot of open source data to
do a lot of experimentation. You were recently hired as a Data Scientist in
their research team and your role is to create a model to determine
probability of a patient having heart disease or attack.

## Objective

This project aims to achieve two main objectives:

1. Provide the best performing model to determine probability of a patient
   developing a heart disease or attack.
2. Providing the most important drivers for a heart disease or attack.

# Getting Started

## Required Tasks

## Installing Dependencies

1.  **Python 3.13.1**

    Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

2.  **Virtual Enviornment**

    It is recommended to work within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virtual environment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

3.  **PIP Dependencies**

    Once you have your virtual environment setup and running, install dependencies by navigating to the `/PROJECT_3` directory and run:

```bash
pip install -r requirements.txt
```

This will install all of the required packages necessary for the Heart Disease Prediction.

##### Key Dependencies

- [Seaborn](https://seaborn.pydata.org/) is a Python data visualization library based on [matplotlib](https://matplotlib.org/). It provides a high-level interface for drawing attractive and informative statistical graphics.

- [Pandas](https://pandas.pydata.org/) is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

- [Numpy](https://numpy.org/) offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.

- [Matplotlib](https://matplotlib.org/) is a comprehensive library for creating static, animated, and interactive visualizations in Python

- [Scikit-learn](https://scikit-learn.org/stable/) Simple and efficient tools for predictive data analysis, accessible to everybody, and reusable in various contexts.imblearn

- [Imblearn](https://imbalanced-learn.org/stable/) Imbalanced-learn (imported as imblearn) is an open source, MIT-licensed library relying on scikit-learn (imported as sklearn) and provides tools when dealing with classification with imbalanced classes.

## Running the program

##### Note

`This project was executed on a machine running` **Windows 10** . `Any OS will work fine just some minor changes. You can easily "google" your way out!` <br><br>
Ensure you are working in your virtual environment.<br>
Navigate to the `/PROJECT_3` directory and open [Visual Studio](https://visualstudio.microsoft.com/downloads/) from that directory. <br>
For this project, you can use any other preferred _Integrated Development Environment (IDE)_ or you can choose to run everything completely on [Google Colab](https://colab.google/) (Colab is a hosted Jupyter Notebook service that requires no setup to use and provides free of charge access to computing resources, including GPUs and TPUs. Colab is especially well suited to machine learning, data science, and education).

## Tasks

| No  | Completed | Task Description                                                                                                                                               |
| :-- | :-------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.  |  **[x]**  | Import libraries and load dataset.                                                                                                                             |
| 2.a |  **[x]**  | Perform Exploratory Data Analysis including univariate analysis to understand the distribution of features.                                                    |
| 2.b |  **[x]**  | Perform Exploratory Data Analysis including multivariate analysis to determine the correlations and analysis of target variables.                              |
|     |
| 2.c |  **[x]**  | Perform Exploratory Data Analysis to determine if new features can be created, based on the given data.                                                        |
| 2.d |  **[x]**  | Perform Exploratory Data Analysis to layout binary classification experimentation space (i.e. determine the list of models you would like to experiment with). |
| 3.  |  **[x]**  | Use precision-recall curves to determine best threshold.                                                                                                       |
| 4.  |  **[x]**  | Publish the performance of all the models on the same hold-out/ test dataset.                                                                                  |
|     |
| 5.  |  **[x]**  | List out the most important drivers of heart disease or attack.                                                                                                |
| 6.  |  **[x]**  | Use techniques such as oversampling, undersampling to handle class-imbalance.                                                                                  |
| 7.  |  **[x]**  | Additional: Using model pipeline to create end to end training and inference pipelines.                                                                        |
|     |

## Datasets

The Dataset directory in this project contains the [heart_disease_health_indicators_BRFSS2015.csv](https://www.kaggle.com/datasets/alexteboul/heart-disease-healthindicators-dataset) file. Below is a description of the various columns in this file.

```
    • HeartDiseaseorAttack: Target variable determining whether patient had prior heart disease or heart attack.
    • HighBP: Binary flag determining whether a patient has high blood pressure.
    • HighChol: Binary flag determining whether a patient has high cholesterol levels.
    • BMI: Numeric value representing the Body Mass Index.
    • Smoker: Binary flag determining whether a patient smokes or not.
    • Diabetes: Binary flag determining whether a patient has diabetes or not.
    • Fruits: Binary flag determining whether a patient consumes fruits in daily diet or not.
    • device_type_used
    • Veggies : Binary flag determining whether a patient consumes vegetables in daily diet or not.
    • HvyAlcoholConsump: Binary flag determining whether a patient is a heavy
    • consumer of alcohol.
    • days_to_departure
    • MentHlth: Numeric value representing mental fitness, ranging from 0 to 30.
    • PhysHlth: Numeric value representing physical fitness, ranging from 0 to 30.
    • Sex: Determining gender of the patient.
    • Age: The age of the patient binned into buckets between 1-13
    • Education: The education level of the patient binned into buckets between 1-6.
    • Income: The income of the patient binned into buckets between 1-8

```

## Author

- [Benedict Ayamga](https://github.com/ayamgabenedict)

## Submission & Acknowledgements

- [Edureka](https://www.edureka.co/) This project is submitted to Edureka as part of the requirements for `Data Science and Machine Learning Internship Program`.

## Screenshots

**The following are screenshoots of the outputs of required tasks in this project:**

![Q1 output](imgs/Q1_a_output.png)

![Q1 output](imgs/Q1_b_output.png)

![Q2 output](imgs/Q2_a_output.png)

![Q2 output](imgs/Q2_b_output.png)

![Q2 output](imgs/Q2_c_output.png)

![Q3 output](imgs/Q3_a_output.png)

![Q3 output](imgs/Q3_b_output.png)

![Q3 output](imgs/Q3_c_output.png)

![Q3 output](imgs/Q3_d_output.png)

![Q3 output](imgs/Q3_e_output.png)

![Q3 output](imgs/Q3_f_output.png)

![Q4 output](imgs/Q4_a_output.png)

![Q4 output](imgs/Q4_b_output.png)

![Q4 output](imgs/Q4_c_output.png)

![Q4 output](imgs/Q4_d_output.png)

![Q4 output](imgs/Q4_e_output.png)

![Q4 output](imgs/Q4_f_output.png)

![Q4 output](imgs/Q4_g_output.png)

![Q5 output](imgs/Q5_a_output.png)

![Q5 output](imgs/Q5_b_output.png)

![Q6_output](imgs/Q6_a_output.png)

![Q6_output](imgs/Q6_b_output.png)

![Q6_output](imgs\Q6_c_output.png)

![Q7_output](imgs/Q7_output.png)

![Q8_output](imgs/Q8_output.png)
