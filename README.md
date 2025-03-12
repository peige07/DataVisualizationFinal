<h2>Fundamentals of Data Visualization Final Project: Super Store Data Analysis</h2>

Note: I chose to use plotly for many visualization, unforunately viola & binder would not render these. In order to get around this I will be adding the images of the visulizaitons to this read me. Additionally you can view the [code from my note book here](https://github.com/peige07/DataVisualizationFinal/blob/main/DataVisualizationFinal.ipynb)

1. **Dataset Overview and Source**

For my project, I have chosen the Superstore dataset, which is widely used in data analytics demonstrations. It simulates sales data for a retail store covering multiple product categories, regions, and time periods. You can find various versions of this dataset on sites like [Tableau](https://community.tableau.com/s/question/0D54T00000CWeX8SAL/sample-superstore-sales-excelxls).

Most versions of this dataset span multiple years (2014–2017) and include around 10,000 rows. This makes it a moderately sized, tabular dataset—complex enough to yield interesting insights. Due to Altairs row limitations most of my exploration will be done with aggegrate data.

2. **Goals and Key Questions**

*Overall Goal:*

My primary goal is to understand sales performance and profitability across different product categories, sub-categoires and states.

*Specific Questions:*

- What correlations exist within our data that are strongly linked to sales and profit?
    - **Answer analysis and code to support assertion found below:** Based on the creation of correlation matrix's and heatmaps, this data does not have any "Strong Correlation" the strongest correlation we have is between sales and profit (.48 correlation) which would be considered a moderate correlation.
- Which product categories and sub-categories yield the highest sales and profit?
    - **Answer analysis and code to support assertion found below:** The category with the highest profit is "Technology" and the highest profitable sub-category is "Copiers".
- What states account for the most sales and profit?
    - **Answer analysis and code to support assertion found below:** Based on the analysis below the top 3 most profitable states are: California, New York and Washington.

3. **Key Elements of Design**

All of my visualizations had to do with 'profit' as such I chose to focus on a simple and intutive color scheme. If a category, subcategory or state was profitable it green and if it was not profitable it is red. For more consumers this is inline with what they would assume and allows for easier digestion of the visualizations.

4. **Evaluation of Approach**

I evaluated my deisgn choice with several non-technical family members to see if my approach was simple and approachable. Based on my straigh forward design choices they were all able to accurately and quickly understand the data presented.

5. **Synthesis of Findings**

Overall, my approach was effective—I efficiently completed my core objective. However, I recognize that this dataset offers virtually limitless insights. In the future, I plan to conduct a more comprehensive analysis to uncover additional trends and conclusions. For now, I focused on a targeted analysis due to time constraints.

**Images from analysis:**

![Altair Correlation Between Sales and Profit](https://github.com/peige07/DataVisualizationFinal/raw/main/VisualizationImages/Altair%20Sales%20%26%20Profit.png)
<Br>
![Category Sales and Profit](https://github.com/peige07/DataVisualizationFinal/blob/main/VisualizationImages/Category%20Sales%20%26%20Profit.png)
<Br>
![Sub-Category Sales and Profit](https://github.com/peige07/DataVisualizationFinal/blob/main/VisualizationImages/Subcategories%20Profit%20and%20Sales.png)
<Br>
![State Sales & Profit](https://github.com/peige07/DataVisualizationFinal/blob/main/VisualizationImages/States%20Profit%20and%20Sales.png)
<Br>
![Map Sales & Profit](https://github.com/peige07/DataVisualizationFinal/blob/main/VisualizationImages/Map%20Profit%20and%20Sales.png)


