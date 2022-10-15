<h1 align="center">Data Analysis on Wallmart's Retail Dataset</h1>
<h4 align="center">15-10-2022</h4> 

<h3>Business Task</h3> 
<p>The purpose of this analysis is to gain insights into:</p>
<ol>
  <li>Wallmart's profit across all states in the United states;</li>
  <li>the relationships between customers' age and the company's profits</li>
</ol>
<h3>Data Sources</h3> 
<p>The Wallmart dataset is google as part of a Youtube tutorial on "how to use Tableau to analyse data. <p>
<p>A summary of the dataset is as follows:<p>
<div>
   The fields of the dataset are as follows: 
   <p align="center">City, Customer Name, Customer Segment, Order Data, Order Priority, Product Category, Product Container, Product Name, Product-Sub-Category, Region, Ship Date</p>
</div>

<h3>Data Visualization Tool</h3>
<p>Tableau was visualization software used.</p> 

<h3>Data Visualization Process</h3>
<p>The following data cleaning steps were observed:</p> 
<ol>
   <li>The excel workbook is categorized into five sheets. ReadMe, Dashboard, Pivot Table, Working Sheet, bike_buyers_dataset. The working sheets tab contains the cleaned data from the bike_buyers_dataset. </li>
   <li>The filter feature was applied in other to easily observe the entries per field. </li>
   <li>Duplicates were removed.</li>
   <li>The fine and replace feature of excel was used to replace “M” and “S” to “Married” and “Single” respectively in the Marital Status field. The same was done to “M” and “F” in the gender field which was changed to “Male” and “Female” respectively. </li>
   <li>A new column titled “Age Brackets” was created and the “IF” condition was applied to group the ages in the “Age” field into groups of “Adolescent”, “Middle Age” and “Old”.</li>
</ol>
<h3>Summary of Analysis </h3>
<p>Pivot tables were used to analyse and gain quick insights into the bike buyers dataset.</p>
<p align="center">
   <img src="images/pivottable-image.png"> 
</p>
<h3>Visualizations and Key Findings</h3> 
<p>Three pivot tables were created and three charts were derived from each of these tables. The charts are as follows: </p>
<p align="center">
   <img src="images/bike-buyers-dashboard-image.png"> 
</p>
<p>The following insights were discovered: </p>
<ol>
<li>Customers of middle ages bought more bikes than other age brackets.</li>  
<li>The average income of the male customers is higher than that of the female customers. </li> 
<li>The closer the customer commute, the higher the tendency to buy a bike.</li> 
</ol>
<h3>Recommendations </h3>
<ol>
<li>Customers of middle ages should be the focus of marketing campaigns.</li>  
<li>More outlets should be opened in the future in other to reduce the customer commute distance.</li>  
</ol>
<br>
<h4 align="center">Download workbook of the entire analysis <a href="https://github.com/shittuadams/excel-data-analysis-project-on-bike-buyers-dataset/blob/main/Bike%20Buyers%20Dataset%20Analysis.xlsx" target="_blank">here</a>.</h4>
