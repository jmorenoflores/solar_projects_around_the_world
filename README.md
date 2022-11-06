# Project: Code Bridge 2022: Solar Projects Around the World
Overview
Intro
Technologies
Project
Figma
Images
## Intro

Practicum by Yandex hosted the Code Bridge hackathon in September 2022, where data science students and software engineering students were paired together to create a landing page that presented data analysis on a selected dataset from a variety of options. Our team, "99 Problems And Coding is All of Them", selected the Excel Workbook containing data about solar energy projects around the world. The workbook provided contained data on projects that were completed, projects that were in construction, and projects that were being planned. The main columns, or features, that were relevant to our data analysis were the energy capacity, latitude, and longitude of each project, however the data was preprocessed using more columns in order to get a more selective grouping of final data. Once the data was preprocessed, a kernel density plot, hexbin plot, violin boxplot, bar chart, and interactive Google GeoChart were created to present the data effectively.

## Technologies

The webpage was made to be responsive/adaptive using CSS flexbox. Additionally, relative width values were given to elements so that no sizes are fixed. Media queries are included to change the layout of the webpage at specific resolutions.

Semantic HTML5
CSS Flexbox
Positioning and relative units
Property transitions
Media queries
Asynchronous programming (utilizing JSON file)
Google Charts, GeoChart, visualization
Jupyter Notebook (Python)
Python's matplotlib library
Project

[See project live](https://timothyhorth.github.io/code_bridge_2022/)
- Figma

The link below will take you to the Figma layout that was used to design the landing page. It provides a basic outline of what the landing page looks like, but was not fully updated to keep up with the actual landing page as it progressed.

[Link to the project on Figma](https://www.figma.com/file/xpGtabtGxGkdDDArc8XDNH/Code-Bridge-2022?node-id=0%3A1)
- Images

Most images were exported from Figma as either a PNG, JPEG, or SVG, and then stored in the /images folder. The graphs and plots created by the Data Science student were cropped as required and then directly placed into the /images folder.
