# Belly_Button_Biodiversity
Creating an interactive data visualization for the web using Plotly.js, JavaScript, and HTML.

## Overview of the Project
Roza is a biological researcher who studies bacteria.  She hypothesizes that some species of bacteria synthesize protein that tastes like beef.  Her lab has partnered with Improbable Beef to find the right bacteria that will provide the perfect taste.  Roza believes that bacteria found in the belly button might provide Improbable Beef with the right solution.  She would like to build a dashboard that her research participants and fellow researchers can access to see the results of the study.  Participants will be able to go to a website, select their participant idenfitification number from a drop down selector , and learn what bacteria species reside in their navel.

### Resources
**Code:**
* charts.js
* index.html

**Data:**
* samples.json

**Software:**
* JavaScript
* CSS
* Bootstrap
* HTML
* Chrome Developer Tools
* Visual Studio Code 1.65.1

## Results
Roza has a partially completed dashboard that includes a panel for demographic information and now needs to visualize the bacterial data for each volunteer. Roza's volunteers will be able to identify the top 10 bacterial species in their belly buttons. If Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

Here is the drop down selector that a participant would use to find a summary of their demographic information and research results:

![test_subject_id_selector](https://user-images.githubusercontent.com/94148420/158081086-2c71714e-96df-4f7e-ae89-21f8fea40425.PNG)

Three visualizations to display reseach results were created:
1. Bar Chart
2. Bubble Chart
3. Gauge Chart

### Deliverable 1 - Bar Chart
The bar chart displays the top 10 bacteria cultures found (in descending order) in a participant's belly button and a hover over a specific bar will display the species of bacteria for that result.

![top_10_chart](https://user-images.githubusercontent.com/94148420/158081466-b4f4defe-c700-457c-adfe-c489adb74e40.PNG)

### Deliverable 2 - Bubble Chart
The bubble chart shows the bacteria cultures per sample.  The larger the bubble the larger the sample size.

![bacteria_samples_per_culture](https://user-images.githubusercontent.com/94148420/158088558-593a6004-b777-4024-b930-e36f82a42af0.PNG)

### Deliverable 3 - Gauge Chart
The gauge chart displays the participant's belly button washing frequency based on scrubs per week.

![wash_freq_gauge_chart](https://user-images.githubusercontent.com/94148420/158088738-3001f339-7aca-45c5-a8e1-1be6c6b53888.PNG)

### Deliverable 4 - Customize the Dashboard
The Belly Button Biodiversity Dashboard was customized with the folloing:
1. An image was added to the jumbotron - bacteria image.
2. Background color was added to the webpage - plum.
3. Bolded font was added to the jumbotron and chart headers.
4. The layout of the **Top 10 Bacteria Cultures Found** bar chart and **Belly Button Washing Frequency** guage chart was resized to create more space between the charts.
5. Finally, the webpage is accessed by clicking https://1on1pt.github.io/Belly_Button_Biodiversity/

## Summary
Here is an image of the final dashboard:

![dashboard_final](https://user-images.githubusercontent.com/94148420/158089679-afe7b397-fa4e-4310-a032-469aa07545f6.PNG)
