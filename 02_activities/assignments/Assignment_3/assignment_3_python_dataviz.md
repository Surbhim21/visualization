For each visualization, describe and justify: 

Title : "Number of Traffic Signals Installed Over Time by Control Mode"
    > What software did you use to create your data visualization?
    Python (Plotly)

    > Who is your intended audience? 
    This visualization is designed for city transportation planners and engineers to observe trends in traffic signal deployment.
    
    > What information or message are you trying to convey with your visualization? 
    It conveys how different types of control modes have evolved in Toronto over the years, highlighting periods of infrastructure expansion or policy shifts.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I used an interactive histogram with distinct colors representing each control mode. Tooltips and hover interaction were included to enhance exploration. The chart title and axis labels were made clear and descriptive.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    The visualization was created using Python code in Jupyter Notebook. I saved the final visualization as a PNG image using Plotly  which allows consistent reproduction of the chart regardless of the viewing platform. If the visualization was created in a tool like Excel or Power BI which are not reproducible may reduce transparency and make it harder for others to verify or make any changes.
    
    > How did you ensure that your data visualization is accessible?  
    A colorblind-friendly palette was selected. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    City transportation planners may use this to guide where updates are needed in traffic signal deployment. It can influence investment in pedestrian-friendly infrastructure.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
     I excluded rows with missing activation years and grouped by control mode, as this was most relevant for year-over-year trends.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Data cleaning included converting date formats, handling missing values, and transforming variables. I also spent time exploring which fields were most complete and meaningful.