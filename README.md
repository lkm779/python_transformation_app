# python_transformation_app
# Data Cleaning

> This is a project based on the guidance provided by the client in which different data is analysed, filtered and transformed and implemented in a Dash app for the client to experience visual data charts



## Project Brief
The Client is the administration of a retail 
store which is interested in using data collected over time from their various branches to understand consumer behaviour in the different regions of the country.
Our plan is to create interactive visualisations for them generated from their data which tells a story about their customers. 
They’ve provided 10 years worth of data collected from all available branches. The data is inconsistent in terms of format and content as the data collection and storage strategy 
is decided by the manager of a store branch. This project is split into two parts, data cleaning and visualisations.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Project Status](#project-status)
- [Challenges](#challenges)
- [Room for Improvement](#room-for-improvement)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
<!-- * [License](#license) -->

## General Information

- This is a one week time project developed under the supervision of Fahid and the guidance of the Clients brief documentation.
- What problem does it (intend to) solve?

-	Track the most purchased and least purchased products & product categories overall, per region and per city (limit to top 5 and least 5)
-	Track the best performing branches overall per region and per city (performance is measured in both item quantity sold and monetary value of sales made, limit to best 10 and worst 10)
-	Per hour sales for the top 10 branches identified
-	Identify the top 10 and bottom 10 profitable branches and indicate how profitable they are. (Calculate profitability by subtracting expense from total sales)

-How?
Take the raw data provided from branches and reginonal managers and convert them into a accessible and easy to read web format.

## Technologies Used

Python
Pandas
Jupyter
Plotly Express
Petl
Glob, OS, JSON, CSV
Heroku
Bootstrap for the design which contains CSS frameworks and JS
Github
Vscode

## Features

List of the ready features in the app:

-	Track the most purchased and least purchased products & product categories overall, per region and per city (limit to top 5 and least 5)
-	Track the best performing branches overall per region and per city (performance is measured in both item quantity sold and monetary value of sales made, limit to best 10 and worst 10)
-	Per hour sales for the top 10 branches identified
-	Identify the top 10 and bottom 10 profitable branches and indicate how profitable they are. (Calculate profitability by subtracting expense from total sales)



## Setup

Open your terminal and then type

$ git clone https://github.com/lkm779/python_transformation_app

This clones the repo

cd into the new folder 

Create environment and install the required dependencies mentioned in the technologies used



You are done!the React project in the new folder that's created.




## Challenges:
-Timing and planning: Timing was challenging, in the sense of setting realistic deadlines or task in time hence the dimensions, requirements, and dependencies of the project. 
-Manipulation: Manipulating the first raw data folders. Basically dividing both CSV and JSON folders into two, to then create separate concatenated tables of all of the files included in the folders with their respectively branch names as columns.
-Data: The large quantity of data it did present as a challenge, as waiting times on jupyter kernel notebook for outputs sometimes took up to 10 minutes to load.



## Room for Improvement

Include areas you believe need improvement / could be improved. Also add TODOs for future development.

The main areas to be improved are
• Reduce files size by clearing unused orirrelevant data to improve loading times, efficiency and flow.
• Improve cohesion between all of the data folders and outputs
• More descriptive documentation and comments as well as structured code


And some Stretch Goals
• Allow users to observe an interactive map of stores performance by region



## Acknowledgements

- This project was based on:
https://www.youtube.com/
https://petl.readthedocs.io/en/stable/index.html
And all the documentation available on Aula in addition to the prerecorded sessions.
