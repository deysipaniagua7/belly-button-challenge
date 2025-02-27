# belly-button-challenge

This is the repository that holds my Module 14 belly-button-challenge.

Module Overview: The module asked us to build an interactive dashboard to explore the Belly Button Biodiversity dataset which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
We had to complete 3 parts: Bar Chart, Bubble Chart, and Metadata and Deployment.

-Bar Chart: We used D3 library to read in samples.json from a provided URL link. We then created a horizontal bar chart with a dropdown menu to display the top 10 Bacteria Cultures Found (OTUs by Number of Bacteria) found in that individual.

-Bubble Chart: We created a bubble chart to display the Bacterial Cultures Per Sample (Number of Bacteria by OUT ID).

-Metadata and Deployment: We displayed the sample’s metadata (demographic info) by looping through each key-value pair from the metadata JSON object and creating a text string. WE also appended an html tag with that text to the #sample-metadata panel.
All plots are updated when a new sample is selected. Finally we were asked to deploy the app to GitHub Pages.

The main "belly-button-challenge" repo contains an 1) "index.html" file to generate the horizontal bar chart/bubble chart and 2) a "samples.json" file which houses the dataset for the module hw.

The ".vscode" subfolder contains a "settings.json" file.

The "static/js" subfolder contains a "app.js" file that houses my javascript code and a ".gitkeep" file.

Please note, I used in-class activities/notes and the following resources to complete my assignments:

-https://stackoverflow.com/questions/75319317/how-do-i-delete-many-filtering-by-two-conditions

-https://stackoverflow.com/questions/77179677/adding-hover-text-over-bubble-chart-in-plotly-js

-https://stackoverflow.com/questions/64013150/append-key-value-pair-in-separate-tags-in-html-using-jquery

-https://www.geeksforgeeks.org/mongodb-comparison-query-operators/#

-https://www.yusufsezer.com/js-add-options/

-https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries

-https://plotly.com/javascript/bubble-charts

-https://plotly.com/python/bubble-charts/#hover-text-with-bubble-charts

-https://www.codementor.io/@awanshrestha/creating-a-bubble-chart-with-javascript-274sh6uogv

-https://www.javascripttutorial.net/javascript-dom/javascript-append/
 
