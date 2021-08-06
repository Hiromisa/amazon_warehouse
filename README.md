# Project: amazon warehouse

This is a project for Lede week 9.  
Using an Amazon warrehouse list I obtained, analyzed its expansion and visualized with QGIS.
The link to my GitHub Pages is [here](https://hiromisa.github.io/amazon_warehouse/)

---
## Background
	The COVID-19 pandemic has accelerated the use of e-commerce. 
	The company which received the biggest tailwind is Amazon, 
	and its growth was supported by fullfillment centers across the United States. 
	Warehouses are also places where work-related issues often happens. So we decided to analyze Amazon's warehouses.
---
## Data
	Based on dataset published by the company and several third parties, 
	as well as news from around the US, I have created a list of Amazon's warehouses. 
	It is the list as of the end of July 2021, also includs those in the planning stages.

---
## Websites mainly referenced
	https://www.mwpvl.com/html/amazon_com.html
	https://selleressentials.com/amazon/amazon-fulfillment-center-locations/

---
## Analysis
	Using PANDAS, I organized the data by opening year. 
	For warehouses where sqft information was unknown, I assigned median. 
	For locations that did not have information on the opening year, I referenced local news. 
	All information is current as of the end of July.

	I plot all the location on QGIS to analyze their distribution. Many of the them are located at transportation hubs. 
	I didn't find any significant correation between the racial composition of the region and warehouses' location. 

---
## Visualization
	I converted QGIS data into images, then made a gif using Photoshop.





