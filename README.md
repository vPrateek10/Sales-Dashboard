
# SN Global-Sales Dashboard

## Problem Statement

This dashboard helps the organization understand their customers better. It helps the organization know of their sales insights. Through different KPI's, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average sales & profit, thus since by using this dashboard they have identified this problem, they can further work on better profit margins.
 
 
 # Report Snapshot (Power BI DESKTOP)

 ![Screenshot (74)](https://github.com/vPrateek10/Sales-Dashboard/assets/111632231/bf42f94d-7969-4f0b-a94b-df3c1e0568a4)

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : It was observed that in none of the columns errors & empty values were present in the dataset.
- Step 3 : In the report view, under the view tab, theme was selected.
- Step 4 : Since the data contains various values, thus in order to represent various KPI's using charts, a new visual was added using the visualizations pane in report view.
- Step 5 : Visual filters (Slicers) were added.
- Step 6 : In the report view, under the insert tab, text box wes added to the canvas, in that name of the organization was mentioned.
- Step 7 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 8 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
- Step 9 : Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
  Although, by default, while calculating average, blank values are ignored.
- Step 10 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers.
 While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender.
- Step 11 : Ratings Visual was used to represent different ratings mentioned below,
  (a) Baggage Handling
  (b) Check-in Services
  (c) Cleanliness
  (d) Ease of online booking
  (e) Food & Drink
  (f) In-flight Entertainment
  (g) In-flight Service
  (h) In-flight wifi service
  (i) Leg Room service
  (j) On-board service
  (k) Online boarding
  (l) Seat comfort
  (m) Departure & arrival time convenience
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.
