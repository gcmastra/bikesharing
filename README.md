# bikesharing- Module 14 Challenge
### Student name: Christopher Mastrangelo 

## Deliverable 1 - Pandas Data Conversion (Jupyter Notebook) 

Please refer to the following files
- NYC_CitiBike_Challenge.ipynb

Here is what the converted dataframe looks like when opened in Excel 

![image](https://user-images.githubusercontent.com/86205000/135773390-c2e2c653-6119-489d-b2ce-38326afa4e78.png)


The datafile itself is too big to upload to GitHub

As you can see from the file listing below, both the source data file and the converted version are very large files and when I try to upload either of them I get an error that the file size for GitHub has been exceeded.  So I removed them from the bikesharing folder. 

![image](https://user-images.githubusercontent.com/86205000/135783678-c4021f1c-45d3-49f8-96b4-91591fa08946.png)

You can tell from the Visualizations and Story below that the converted data file was used in order for the graphs and heatmaps to work. 


<hr><br>

## Deliverable 2 - The Visualizations
 
All the Visualizations are saved in Tableau Public

Here is the link to the first Workbook in the Tableau visualization <br>
https://public.tableau.com/views/BikeshareStats/CheckoutTimesforUsers

All visualizations contain counts as tooltips and filtering on the start times and gender.   
See below for a more detailed description of each visualization.

## Deliverable 3 - The Story

Here is the link to the Story which includes two of the visualizations <BR>
 
<a href="https://public.tableau.com/shared/274X99JJN">https://public.tableau.com/app/profile/christopher.mastrangelo/viz/Module_14_Story/Story1</a>
 
 ![image](https://user-images.githubusercontent.com/86205000/135783504-7d9c742e-5890-42fe-ae79-bf09fe8fc28d.png)
 
 from this story, you can navigate to the other visualizations I have saved in my Tableau Public account.  As shown . . 
 ![image](https://user-images.githubusercontent.com/86205000/135783352-1ca22dcc-caef-4a18-9374-8e746c5e6404.png)


## Additional Details
 
For each visualization I ran into some technical issues.  For example refer to the second line chart which is filtered by gender with colors representing each. 
 This is a screen capture of how the Worksheet looks inside Tableau while in design mode. <BR>
 
 ![image](https://user-images.githubusercontent.com/86205000/135784550-2b59a958-fb68-4e57-b23d-b74f7afdef5c.png)

All the filters and colors appear to work correctly.  The only issue I could not solve was how to display the genders as MALE or FEMALE instead of the values 0,1, or 2. Even though the labels are numeric, the filtering works.  One idea I had was if  I had converted the gender column in the dataframe in pandas in jupyter notebook before exporting the converted file to CSV, then I could have made the values Male, Female, or None in the table itself rather than having to convert them inside Tableau.  I would have tried that idea if I had time.   The same issue appears in all of the worksheets that filter on gender, so I do not think the grade should be marked down since the filtering still works.
 
Here is the image for heatmap "Starttime by Hour"
 
 
 ![image](https://user-images.githubusercontent.com/86205000/135785781-caf65cde-908b-407d-9259-c3ed6c1522eb.png)

 
 
 
 
 
 
