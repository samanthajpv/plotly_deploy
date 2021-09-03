# plotly_deploy
An interactive webpage-dashboard using Plotly.js

## Project Overview
The purpose of this project was to create an interactive webpage that would display data visualizations using Plotly.js. The data loaded in the page is from an external JSON dataset on belly button samples. User will be able to select test subject ID numbers and the dashboard will automatically update and reflect the data from the chosen ID.

### Resources
- Data Source: [samples.json](https://github.com/samanthajpv/plotly_deploy/blob/49332a6270230bf6cef416963e77dba00c826c03/samples.json)
- Language: JavaScript, HTML
    - Library and Framework: Bootstrap, D3.js, Plotly.js
- Software: VSCode
- Code:
    - [charts.js](https://github.com/samanthajpv/plotly_deploy/blob/49332a6270230bf6cef416963e77dba00c826c03/static/js/charts.js)
    - [index.html](https://github.com/samanthajpv/plotly_deploy/blob/49332a6270230bf6cef416963e77dba00c826c03/index.html)
- [Link to interactive webpage](https://samanthajpv.github.io/plotly_deploy/)

## Method
- **Test Subject ID No.**: The webpage was designed to listen for changes such as the selection of ID numbers from the drop-down list. This calls the functions created in the JavaScript file to get the data corresponding to the selected ID number and update the demographic info and charts.
- **Demographic Info**: The demographic information of the test subject is displayed in a panel. 
- **Charts**: The three charts were created using Plotly.js. The first is a horizontal bar chart that displays the top 10 bacterias found. The second is a gauge chart that shows the frequecy of belly button washing per week. The third is a bubble chart where the size of each bubble is based on the sample value.
- **Customization**: To make the dashboard more appealing to users, an image was added to the jumbotron as well as a paragraph about the webpage with customized font-style. The layout has the the bar and bubble charts aligned and a margin was added at the bottom of the page.

<p align="middle">
    <img src="https://github.com/samanthajpv/plotly_deploy/blob/01fb338626cbff289558d6da4a7234c913a8d1a2/resources/db.gif" width="700" height="400"/>
    <h5 align="center">Interactive Webpage</h5>
</p>

## Reference
(1) Trilogy Education Services. (2021, September). *Module 12 Challenge*. https://courses.bootcampspot.com/courses/626/assignments/13330?module_item_id=213210
