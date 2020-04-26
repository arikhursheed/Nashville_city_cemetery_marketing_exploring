I Had a great opportunity to join Nashville Software School, it is where I start learning advance Excel as a tool for data visualization with storytelling and use a variety of strategies and formulas to manipulate data and gain insight from the data. This project was assigned to me individuality to work on finding marketing materials from the data and present them.

The Project:

 The city of Nashville provides a dataset of known burials in city cemeteries from 1846 through 1979. This dataset holds factual information, but it also offers a fascinating glimpse into historical trends in medicine, literacy, racial equality, and more.

  Create charts that can be used in marketing materials. Considering theses questions: Are there months with higher burials? What are the top five causes of death for each month? Choose a visualisation that conveys the differences well.

Data examination and manipulation in the process to gain insight for storytelling. 

 ![Top 5 causes of death for each month](/assets/total_causes_death_each_month.png)

 1.	Using a pivot table to find the 10 most common (known) recorded causes of death, and evaluate the counts of each type. have metrics, plot them in a **bar chart**. In the analysis of the top 10 causes of death, notice for spelling mistakes that are affecting counts. For example, Cholera and Cholrea are the same cause of death. finally, create a new column in the original dataset to update spelling errors to make count of the top 10 causes more accurate. **refresh pivot table** to apply changes.

 ![Top 10 cause of death](/assets/Top_10_cause_of_death.png)

 2.	Creating a line chart showing the number of burials per decade. Notice for the years were there the most burials. From the chart 1860-1869 had the highest number of total burials. It is the period time where the civil war took place.

 ![Total burial per-decade](/assets/Total_burial_per-decade.png)

 3. Examining deaths for each decade beginning with the 1850s. Notice the total number of deaths and the proportion of male deaths to female deaths. Use **pivot table** with a **slicer** to do this and create a clustered bar chart to show how male and female deaths have changed over time.

 4. looking at how age at time of death has changed over time. Add a column to the original dataset to classify each row to one of the following categories (0-18, 19-25, 26-40, 41-64, and 65+). The formula deals with missing values then a series of pie charts or donut charts will manage to show the breakdown of each age group for these four periods: before 1880, 1881-1900, 1900-1920, after 1920.

 6. Creating a new column titled Last Name. Extract the last name from the Name column by subsetting to all characters to the left of the comma (String Information – LEN, SEARCH) which will result in many errors for rows missing commas.  

     a. Drilling down to those rows without a comma and notice that The
          most common last names buried in the cemetery is "infant,", and   Ranks the Top in mortality.

     b.	There was a particularly famous person buried in this cemetery and  
         it is Ex-president Polk. 

     c. most infants were buried in an old grave or the section/lot not  
         specified 

 7. Noticing interesting patterns regarding where (`Section/Lot`) people were buried and that is most infants were buried in an old grave or the section/lot not specified 

Overall process

 Creating a new sheet for each pivot table or analysis work done to create a visualization and give each sheet a descriptive/meaningful name. putting all final charts (along with the related story) on their own worksheet. Only include charts on the final sheet that deliver what has been asked for.
 
 ![Final deliver](/assets/final_deliver.png)