.. |srarr|    unicode:: U+02192 .. RIGHTWARDS ARROW

Tableau Assignment - Creating a Dashboard
--------------------------------------------


**PRACTICUM [GROUP]** - Take 60 minutes to answer the following questions. Once
you have finished we will ask for volunteers and discuss responses as a group.


A) Import the coffee_chain_assignment.csv file into Tableau.
   
   Answer: Select "Text file" from the "Connect" menu, navigate to the location
   of the coffee_chain_assignment.csv file you downloaded and click "Open".

B) Create a calculated field called Profit.

   Answer: Right click in the empty space below the dimensions in the left
   toolbar and select "Calculated Field". Type "Profit" where "Calculation1"
   is visible and ``[Sales]-[Total Expenses]`` in the space below.

C) Convert "Area Code" from numeric to geographic data type.

   Right click on the "Area Code" pill then click on "Geographic Role" and
   select "Area Code (US)" from the dropdown menu.

D) Create a hierarchy of geographic with "State" as a category and "Area Code" 
   as a subcategory. 

   Answer: Right click on the "State" pill and select "Hierarchy" |srarr| 
   "Create Hierarchy" and name the hierarchy "Geography". Drag and drop the
   "Area Code" pill just below the "State" pill to turn it into a subcategory.

E) Create a map using the geographic hierarchy.

   Answer: Double click on the "State" pill in measures.

F) Color code each state by profitability.

   Answer: Drag the "Profit" pill to colors in the "Marks" box.

G) Create "Side by side" bar chart to display "Cogs", "Marketing" and
   "Other Expenses" organized by state.

   Answer: Drag the "State" pill to columns and the "Marketing", "Cogs" and
   "Other Expenses" to rows. Then select "side-by-side bars" from the "Show
   Me" menu.

H) Create a pie chart showing sales by product type.

   Answer: Drag the "Product Type" pill to columns and the "Sales" pill to rows
   then select "pie charts" from the show me menu.

I) Create a new dashboard using the previous visualizations.

   Answer: Click on "Dashboard" |srarr| "New Dashboard" and choose a minimum
   pixel size of 1200 width and 560 height. Select "Floating from the "Objects"
   menu and drag the sheets from the "Sheets" menu. Resize and edit to desired
   appearance.

J) Use each of the three visualizations as filters to create an interactive 
   dashboard.

   Answer: Click on the visualizations in the dashboard and click on the funnel
   icon on the right side of the dark outline below the X on each
   visualization. 

K) Use your new dashboard to provide insight into the condition of your
   business and present your dashboard and discoveries to the group.