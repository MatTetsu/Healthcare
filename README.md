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
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
Within the dataset, there were a few issues that I missed when picking the dataset:
- Some of the gender values seem to be incorrectly inputed
- Some of the finacial values seem to be negative
- Some of the rows were duplicated (in the overall dataset) and would drop any that made it into the worked on dataset
If I was to put more time into this project then I would work out a way to clean them properly 


## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

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

## Credits 
- I have used stack overflow for help writing the code like the machine learning (https://stackoverflow.com/questions)
- I have used ChatGPT and CoPilot to help me fix code that I was struggling to fix
- I have used he Code Institute LMS for the visualisations within the notebook
- I have asked Neil Lenus, who is a personal friend, to help me work out how to shrink the dataset to a more manageable size
- I have asked Emma and Neil (two staff memebers from Code Institute) for help as I had an issue pushing my commits up to github
- I have watched this video (https://www.youtube.com/watch?v=VaOhNqNtGGE&t=1s) to help me learn Power Bi


### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media
