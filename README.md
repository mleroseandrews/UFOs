# UFOs
### Overview of Project
The main goal was to build a webpage for UFO data with a table using data stored in a JavaScript array.  The table can be filtered by date, city, state, county and or UFO shape.  The webpage was construced using Bootstrap for added visualizations.  

### Results
There are 5 possible filters which can be used individually or in combination to further refine the results. The user will enter in the search criteria in the dialog box under each search criteria and press filter button. This will apply the filter and display the new results matching the search criteria defined. 

### Summary
- One drawback of the webpage is that the data being input by the user is case sensitive . The user must enter in the filter criteria as formatted in the table. Another drawback is that the filters only allow for one input at a time. So users cannot filter a date range or filter for two shapes or two cities at the same time.

- Two additional recommendations for further development:
1. Add in a user input validation step. Starting with reformatting any kind of date, taking in to account any case corrections for the city, state, country and shape filters. One possible work around to having to script in the validation steps is providing the user with a drop-down menu of all possible selections for the filter rather than having them type it in themselves.
2. Add in a date range filter and add the ability to filter using two or more selections for the city, state, or shape inputs. 
