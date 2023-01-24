# INVENTORY DIVE DEEP
Pipeline of inventory for country and sites with control for deep diving
<p>Schemas, Tables, Columns and Values are changed from the original ones to avoid sensitive data being released outside the company</p>
<p>Tool used:</p>
<ul>
    <li>SQL</li>
    <li>Quicksight</li>
</ul>
<p style="text-align: left;">This project has been created to have complete check and control of the inventory present in the countries and warehouses.</p>
<p style="text-align: left;">The data is sourced with a SQL query directly from the Data Lake which is automatically refreshed every Monday.</p>
<p style="text-align: left;">The controls at the top give us the possibility to deep dive into different kinds of items and different granularity(ex: countries and warehouses).</p>
<p style="text-align: left;">With the historical data returned, we can deep dive into the situation for the past week and check the variance Week on Week and have a graph with the trend.</p>
<p style="text-align: left;"><br></p>
<p style="text-align: center;"><strong>ACHIEVEMENT</strong></p>
<p style="text-align: left;">The trend graphs help us in spotting the period where the bulk fullness had a spike in France and we were able to decrease the volume by 10% giving a smoother inbounding of the items.</p>
<p style="text-align: left;">The filter for a product type can see where most of the volume is found and be able to take action in balancing the sites in the country.</p>
