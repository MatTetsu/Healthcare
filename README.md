# Project XYZ

**Project XYZ** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
The dataset I chose was (https://www.kaggle.com/datasets/prasad22/healthcare-dataset) despite being 50,000 rows long I shortened it to 10,000


## Business Requirements
The business goal of this dataset is to predict other patients likelyhood to get a certain medical condition to help give them the correct attention.


## Hypothesis and how to validate?
* List here your project hypothesis(es) and how you envision validating it (them) 

## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
I have deleted the names for data protections, instead I have allocated them a patient ID number so that they can be assessed more closely if necessary.


I have deleted the names of the patients for identity protection, but I assigned them a patient ID (randomly) so doctors know who they are

I did also consider dropping the doctor and hospital columns for ethics reasons, but deamed it unnecessary 


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

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


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



## Credits 
- I have used stack overflow for help writing the code like the machine learning (https://stackoverflow.com/questions)
- I have used ChatGPT and CoPilot to help me clean code that I was struggling to fix
- I have used he Code Institute LMS for the visualisations within the notebook
- I have asked Neil Lenus, who is a personal friend, to help me work out how to shrink the dataset to a more manageable size
- I have asked Emma and Neil (two staff memebers from Code Institute) for help as I had an issue pushing my commits up to github

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media
