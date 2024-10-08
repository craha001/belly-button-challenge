# belly-button-challenge
For this weeks module 14 challenge, the goal was to use D3.js and Plotly to make a visual dashboard for Belly Button diversity from samples provided by https://robdunnlab.com/projects/belly-button-biodiversity/. Individuals 
who use the dashboard can look at different samples bacteria cultures. The code has four functions necessary for getting the task completed.The overall challenge includes our bubble chart which displays distribution of bacter cultures for each sample 
and the markers are sized by the number of bacteria.  Also on the dashboard is a bar chart showing the top ten bacteria cultures found for each sample and their corresponding OTU ID. OTU stands for operational taxonomic unit. There is also
an interactive dropdown menu as mentioned before to look at different sample ID's. Lastly, there is a Metadata panel which shows demographic info for each chosen sample from the user.

Each of the functions can be found in the belly-button-challenge folder under the app.js file. 

## Function 1:
Using D3.js, the first function called buildMetadata is used to fetch the metadata and filter it out in order to get the necessary data for our charts and dropdown menu.

## Function 2:
Again, using D3.js the function buildCharts was created to set up our bar chart and bubble chart. The goal in this part of the code was to pull the sample data, filter it, and then use this
information to build our graphs. Then with plotly, we were able to render the charts.

## Function 3:
Here a function was created to in order to form our dropdown menu. In the same function, we use the first sample in order to create our charts based on the specific ID and the next function will 
be used to render new sample ID information. 

## Function 4:
Last function optionChanged, is a simple two lines of code where the buildCharts and buildMetadata works based on the users selected sample ID from the dropdown menu.

## Contributions:
I collaborated on this assignment with Nicolas Ortega and Brendan Golden. Also, for assistance building the code I used ChatGPT.

