# Write_a_Data_Science_Blog_Post
This project is a part of Capstone Project for Udacity Data Scientist Nanodegree program.

## **Table of Contents:**
1. [Project Introduction](README.md#project-introduction)
2. [File Description](README.md#file-description)
3. [Libraries used](README.md#libraries-used)
4. [Results](README.md#results)
5. [Licensing, Acknowledgements](README.md#licensing-acknowledgements)

## **Project Introduction**
In this project, I will look into the simulated Starbucks Dataset in which customer behaviour, such as 
receive and completing offers, and also the demographic of customers are tracked.

Following questions will be examined and answered:
- How much starbucks customer completed a reward?
- What kind of offer type most customer view and completed?
- Could a prediction be made, either a customer will take a reward or not? So a targeted marketing could be done!

---

## Methodology
**CRISP-DM** will be used as the methodology to answering the business questions above. 
1. Business Understanding  
To understand how well the business is working , the business questions will be defined.
   The question will not only be a prediction question, but also some descriptive statistic question.
2. Data Understanding  
From the business questions, the dataset will be analyzed, so that the useful data feature could selected and cleaned accordingly.
3. Data Preparation  
The raw data are mostly not clean, in this phase, we will clean the data, so it will be ready for training
   the prediction later. The feature will be also extracted from the dataset
4. Data analysis and data model  
Based on cleaned data from previous section, the dataset wil be analyzed and presented.For prediction question, 
   classification algorithms will be used to train the prediction model. The performance metrics will be defined 
   and justified.
5. Results  
The results will be presented in a Medium article.
6. Deploy  
In this project there will be no deployment.


----

## **File Description**
    .
    ├── data
    |   └── portfolio.json                  # containing offer ids and meta data about each offer (duration, type, etc.)
    |   └── profile.json                    # demographic data for each customer
    |   └── transcript.                     #  records for transactions, offers received, offers viewed, and offers completed
    ├── Starbucks_Capstone_notebook.ipynb   # Jupyter Notebook that contains the analysis
    └── README.md

The dataset is provided by Starbucks.

---

## **Libraries Used**<br/>
- [ipython-autotime](https://pypi.org/project/ipython-autotime/)
- [pandas](https://pypi.org/project/pandas/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [seaborn](https://pypi.org/project/seaborn/)
- [scikit-learn](https://pypi.org/project/scikit-learn/)

---

## **Results**<br/>
The finding from the jupyter notebook can be found in [this medium post](https://veltenwinter.medium.com/8000-for-a-night-in-airbnb-munich-e511a8ab1c3c)

---

## **Licensing, Acknowledgements**<br/>
Credit and thanks too: 
- Udacity for providing a great data scientist course.
- Starbucks to providing a great data.