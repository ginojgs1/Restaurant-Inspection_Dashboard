
# Restaurant inspection_Dashboard

### Dashboard Link : https://app.powerbi.com/reportEmbed?reportId=ac44c4aa-f577-438e-b6e4-2a4af7116e01&autoAuth=true&ctid=7a95ad65-55ee-41e3-ba46-acbdf605ee3d

## Problem Statement

ABC is a leading restaurant inspection firm thatis spread across the globe. Based on the region, it has identified the facility city. There are inspectors assigned to each region. The regionhas a number of facilities. Restaurant inspection data is created based on the violationsidentified and sanitary grade A,B,and C is provided. It needs to create a report to add visuals with data present region-wise and add rolesto ensure users can view based on region.



### Task 

Key Objective 1

1.Add a clustered column chart to show the number of inspections on the x-axis and the facility region on the y-axisname the chart “Inspection Volume”

2.Add a Decomposition Tree chart to showthe Number of Violations. Thiscan be created by adding a Measure “Violation” it uses thecolumn “violation_code”in Restaurant Inspection Data Tableto count the total number of violations.Put this measure in Analyze field, add facility_region (From “Region Lookup”Table), and violation_description (From “Restaurant Inspection Data”Table) inExplain By field.

Add a measure “% of Total Violations”which calculates total number of violations usingthecolumns “violation_code” and “serial_number” (From “RestaurantInspection Data” table)add this measure to the Tooltip field.Title the chart “Violations by Region & Type”, and adjust the formatting to match the other visuals (white font, black background, centered)

a.“Expand” the Decomposition tree and split the data by facility_region (first) then violation_description (second) 

b.Format the data bars Positive bar color to Yellow (hex #e1c233)

c.Format the Tree primary color to Blue (hex #118DFF)

Hint:

![Image](https://github.com/user-attachments/assets/dbc5dd8f-3bc7-4eab-8129-9e324de75970)

3.Add a Donut chart to show Grade “A”, Grade “B”, and Grade “C” (on Values) and “sanitation_grade”from the “Sanitary Grade Lookup”table (on Legend).

a.   Title the chart “Sanitation Grade”, and adjust the formatting to matchthe other visuals (white font, black background, centered)

b.   Update the Data colors and set: 

i.  A = #FFD710

ii.B = #119E30

iii.C = ##E66C37

c. Turn the Legend Off 

d. Turn on Detail labels and set the Label style to “Category” 

e. Update the page name from “Page 1” to “Inspections & Violations”

Key Objective 2

1.Make any formatting tweaks that you see fit (alignment, chart styles, separation lines, etc.), and save your completed report.

Key Objective 3

1.Create two roles:Lead Inspector and Chief Inspector.

2.Lead Inspector should be able to view results for regions 1–10(Region Codes).

3.Chief Inspector should be able to view results for all the regions 1–16(Region Codes).

4.Validate the DAX code and saveit.

5.Test the role on the Desktop

a.Confirm that the Report view updates as expected.

b.   Confirm, from the Data view, that the data updated isas expected

6.Publish the updated “Restaurant Inspections-report” report to Power BIService and use “Test as role” to confirm it’s working.

a.Make sure to saveit.

b.   Confirm you’re overwriting an existing dataset.

c.   Confirm by testing both roles.



Note: sample of dashboard.


![Image](https://github.com/user-attachments/assets/c0cff4f3-1b1c-4344-9890-aad3b8b23843)



        
