# Healthcare trends prediction

This healthcare project aims to predict if other paitents are likely to get a medical condition by looking at common trends within this dataset



## Dataset Content
The dataset I chose was (https://www.kaggle.com/datasets/prasad22/healthcare-dataset) despite being 50,000 rows long I shortened it to 10,000


## Business Requirements
The business goal of this dataset is to predict other patients likelyhood to get a certain medical condition to help give them the correct attention.


## Hypothesis and how to validate?
People with certain medical conditions tend to go more to certain insurance providers

People with certain medical conditions get billed differently

People with certain blood types are more likely to get a medical conditions

Elderly people are charged more than younger people


## Project Plan
* Extract, Transform, Load: Cleaning the data, by checking for missing values, checking for duplicates, and correcting data types.
* Exploratory Data Analysis: Understanding characteristics, distributions, and relationships within the dataset.
* Statistical Analysis: Hypothesis testing to validate inital assumptions about feature relationships.
* Feature Engineering: Adding additional features to the dataset to help with visualisations, Age Ranges, Length of Stay
* Machine Learning: Training and evaluating baseline predictive models.
* Dashboarding: Making interactive visualisations in PowerBi.
* Conclusions: Summarising key findings and providing action recmmendations.


## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* I used Python as its the primary language for data manipulation, analysis, and machine learning. I used python libraries such as Pandas and Numpy to help clean the dataset. I also used the python libraries Matplotlib, Ploty, and Seaborne to help me make visualisations within the Jupyter notebook. I also used Scikitlearn for machine learning.
* I used PowerBi to make interactive dashboards, I used barcharts, box plots, scatter graphs, and pie charts to show correlations between different columns in the dataset.

## Ethical considerations
I have deleted the names for data protections, instead I have allocated them a patient ID number so that they can be assessed more closely if necessary.
I have deleted the names of the patients for identity protection, but I assigned them a patient ID (randomly) so doctors know who they ar
I did also consider dropping the doctor and hospital columns for ethics reasons, but deamed it unnecessary.


## Dashboard Design
There is also an anomaly within the billing amount, which has skewed the billing amount visualisations
<img width="1431" height="806" alt="image" src="https://github.com/user-attachments/assets/39aecfc7-aaf9-48d1-b75a-28af92d7fd2b" />
This is the first page, which has visualisations linked to blood type. With a pie chart to show the spread of different blood types, this allows us to eyeball if there is too much of a certain bloodtype, so we understand that the specific blood type is not skewing the visualisations by being bigger than others. Next to it we have a Bar graph seperated by medical conditions, this allows us to see if there is a common medical condition with a blood type, for example we can see that cancer is very common with people with o+ blood type. The box plot allows us to see the bounds that people with certain blood types had to pay.
<img width="1425" height="790" alt="image" src="https://github.com/user-attachments/assets/287b9bad-ed46-4ce7-8fa7-e6142eba7f2d" />
This is the second page, which has visualisations linked to medical conditions. The pie chart, again, allows us to see if there is any statical biases because there is too many of a certain medical condition, like the blood type one, there is not. There are 2 bar charts here, the first is an inverse of the one on the blood type one, this groups the data differently. The other bar chart is for what medication was given to people with a medical condition, to see what helps certain medical conditions more. lastly is a box plot to help us find the bounds of what people had to pay linked to their medical conditions.



## Unfixed Bugs
Within the dataset, there were a few issues that I missed when picking the dataset:
- Some of the gender values seem to be incorrectly inputed
- Some of the finacial values seem to be negative
- Some of the rows were duplicated (in the overall dataset) and would drop any that made it into the worked on dataset
If I was to put more time into this project then I would work out a way to clean them properly 


## Development Roadmap
An issue I faced with this dataset was that I didn't fully look at the dataset properly when I picked it. In the future I plan to mannually make an edit to the dataset to clean the gender column (by making an educated guess off of their name, this has some issues as some people do not identity with the gender they were assigned at birth, which may have an issue later on) but I would like to use the gender column to see if there is correlations within the dataset for genders to get specific medical conditions, if they were billed differently to others within their gender/medical conditions, or if they were given different medication due to gender. I would also like to try and clean the billing amount properly as it would help properly sort out the bounds people were charged, so it would clean the mean, median, and range of the billing ammounts.

## Technology used:
Github as a cloud 
VS Code
- Jupyter Notebooks for cleaning and visualising the data
- Python 3.12.8 for writing the code
- Pandas for helping cleaning the data 
- Numpy for helping cleaning the data
- Matplotlib for visualisations
- Seaborn for visualisations
- Plotly for visualisations
- ScikitLearn for machine learning
- PowerBi for visualisations
- ChatGPT to help fix code that was not working
- CoPilot to help fix code that was not working

## Visualisations:

Box Plots:
- Billing amount ranges separated by age ranges
- Billing amount ranges separated by insurance provider
- Billing amount ranges separated by medical condition

Bar Graphs:
- Medical conditions separated by blood type
- Blood type separated by medical condition
- Age range separated by insurance provider
- Medical conditions separated by insurance provider
- Insurance provider separated by medical conditions

Pie Charts
- Medical conditions
- Age Ranges
- Insurance Provider
- Blood Type

Scatter Graphs
- Billing amount Seperated  by Age

3D Scatter Graphs
- Date of admission by Discharge Date, and Length of stay, coloured by age ranges

## Conclusion

## Credits 
- I have used stack overflow for help writing the code like the machine learning (https://stackoverflow.com/questions)
- I have used ChatGPT and CoPilot to help me fix code that I was struggling to fix
- I have used he Code Institute LMS for the visualisations within the notebook
- I have asked Neil Lenus, who is a personal friend, to help me work out how to shrink the dataset to a more manageable size
- I have asked Emma and Neil (two staff memebers from Code Institute) for help as I had an issue pushing my commits up to github
- I have watched this video (https://www.youtube.com/watch?v=VaOhNqNtGGE&t=1s) to help me learn Power Bi
