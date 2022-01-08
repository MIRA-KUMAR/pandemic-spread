# Characterisation of Pandemic Spread

The challenge reports a global outbreak of a disease in 2009. The information about the pandemic is shown for 11 countries across a period of 4 months is provided in the dataset. We were tasked with analysis and visualization of the information in such a manner that the visualizations enable healthcare professionals, government officials, and citizens to analyze the factors of the pandemic, its spread, and respond swiftly and effectively for such future epidemics. 


# Obtaining Dataset:
A static dataset is used in the project. It was obtained from -   http://visualdata.wustl.edu/. The dataset contains several data points describing patient information and attributes with categorical, quantitative and sequential data. 


# Data Visualizations:
We have developed a series of five visualizations that effectively depict our analysis, help interpret and characterize the epidemic and solve the challenges raised by the Mini Challenge.
These visualizations are then integrated in an interactive website. 

# Streamline Graph:
This visualization represents the number of people hospitalized and died in each country. 

        Dropdown interaction: Selection of a country from the dropdown or selection of survival options (Hospitalized/Dead) will show the streamgraph visualization of the selected options.
        Hover interactions: On hovering the mouse over a stream, the corresponding country’s name is displayed.
        Additional feature: 
        On clicking on a specific stream (or, country), other streams will be faded for better visibility. Also, based on the country selected from the streamgraph, other graphs will be updated. 
        A ‘RESET’ button is added to reset the graph, i.e, display the visualization for all countries. 


# Grouped Bar Chart:
The grouped bar chart is categorized into five different age groups and each bar shows the Hospitalized, Dead and Recovery counts for each age group. 

        Dropdown interaction: Selection from Countries dropdown will give the visualization of that Country. 
        Hover interactions: On hovering the mouse over the bars, the values are displayed.
        Observations: We have noticed that throughout the countries, the patients between the ages 40-60 years of age are getting affected more. The hospitalized count and death counts are higher for this age group compared to other age groups. We have also noticed that the difference between the Hospitalized and Recovered counts (i.e, Dead counts) is marginal for all age groups and for most of the countries. 
        
        
# Bubble chart: To show the importance of symptoms
This visualization represents the cardinal importance of each symptom analyzed. It’s based on the percentage of the patients with specific syndromes and who died with a specific set of symptoms and who were hospitalized and then recovered with specific symptoms. This helps the medical professionals to treat which patients first with which symptoms and also for the analysis. We can analyze the combinations of dangerous systems in a specific country and based on that one can analyze and make the decisions. 

        Dropdown interaction: Selection from Countries and survival dropdown graph will give the analysis of that particular selected combination. 
        Hover interactions: Hovering shows us the syndrome name and how many people are affected with the syndrome. 
        Additional features: 
        Upon clicking on a symptom, the most frequently occurring symptom with the current one will be highlighted. 
        A ‘RESET’ button is added to reset the graph, i.e, bringing down the opacity value of all bubbles. 


# Cleveland Dotplot:
The main aim of this visualization represents the number of male and female deaths for each country using the Cleveland dot plot. This helps us to compare how the deaths vary between the two genders. Using the given dataset, the number of deaths of both genders male and female are calculated and later plotted in the form of the Cleveland dot plot

        Dropdown interaction: The dropdown interaction is used to highlight the particular country on the graph as shown below. It also gets back to the original visualization when “ALL” is selected on the country dropdown. 
        Streamline graph interaction: This interaction is used to highlight the respective country using the on-click interaction of the streamline graph.
        Hover interaction: This hover event gives us the exact number of male and female deaths for the respective country when we hover over it on the graph.


# Double Circular Bar Chart: 
This visualization gives us the comparisons between average life span of different places and also percentage of deaths. The outer bar plots are used to examine the average lifespan for various places whereas the inner bar plots depict the percentage of deaths.

          Dropdown interaction: This dropdown interaction is used to highlight the respective country on the visualization when the country is selected on the dropdown as shown in the figure below. It also reflects back to the original visualization when “ALL” is selected on the country dropdown. 
          Streamline graph interaction: The on-click event on the streamline graph will also affect the circular bar chart and the specific country will be highlighted.
          Hover interaction: The interaction helps us to get the exact number of days of average lifespan and the exact percentage of death of the particular country when we hover on it as shown in the below figure. 
          
