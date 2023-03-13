# FIRE-INCIDENT-REPORT 2011-2019
Data analysis of a fire incident report collated from 2011 till 2019

## SOURCE: https://www.kaggle.com/datasets/reihanenamdari/fire-incidents

## INTRODUCTION

Fire incidence refers to any occurrence of fire, whether accidental or intentional, that causes damage or destruction to property or poses a threat to people's safety. Fires can occur in a variety of settings, including homes, businesses,industrial sites, and natural environments. The causes of fires vary widely, has been reported extensively in the dataset chosen. Preventing fires is an important aspect of fire incidence management. This can include measures such as maintaining electrical systems, keeping flammable materials away from heat sources, installing smoke detectors and fireextinguishers, and educating people on fire safety. Firefighters and other emergency responders also play a crucial role in responding to fires, containing them, and protecting people and property from harm. This report analyzes the most common causes of fire incidence, value loss, method of control, civilian casualities and level of damage over a period of time.

 ## ABOUT DATASET

The dataset was downloaded as a CSV file containing 28 columns and 11215 rows in total. The details include civillian casualities, count of persons rescued, estimated dollar loss, extent of fire, method of fire control, possible causes, presence or absence of smoke alarm, fire alarm system, ignition source and more. 
![Fire data page](https://user-images.githubusercontent.com/127628101/224685019-9fe551e2-9232-4bac-a64e-f258372c5eec.png)
Please note that the visualization reported in this project represent approximately half of the entire dataset for easy reporting as an upcoming data analyst.

## STEP ONE: DATA PROCESSING
Here are some of the important steps taken to ensure a clean data:
1. Download data from source e.g Kaggle.
2. Check for missing values and handle them appropriately (e.g., remove rows with missing values or fill in missing values ).
3. Check for inconsistent or incorrect data types (e.g., converting strings to numbers where necessary).
4. Remove duplicates, if any.
5. Handle outliers (e.g., removing outliers or transforming the values to bring them within the range).
6. Clean and preprocess the text data, if any (e.g., removing punctuations, converting to lowercase, etc.).
7. Rename columns and data to meaningful and descriptive names, if necessary, eg Extinguished by Occupants simply to 'By Occupants'.
8. Save the cleaned data back to a new CSV file, or continue using the cleaned data in the dataframe for visualization.
 
Note that the specific steps and the level of detail required may vary depending on the data and the requirements of the analysis and visualization.

## STEP TWO: ANALYZE CLEAN DATA
1) First, I included the date table and extracted the year and quarter.

![Date Table FR](https://user-images.githubusercontent.com/127628101/224692842-ade3bece-8c86-46f7-8690-b081aee2dc66.png)

2) Then I created a model to connect my dataset together.

![Data Model Fire report](https://user-images.githubusercontent.com/127628101/224693211-4b5982c2-1e27-469f-a62e-9583500eeadc.png)

Generally, this dataset did not require the use of Pivot table for various data collation, I simply used the card option on PowerBi to generate the Total number of civillian casualities, displaced persons, persons rescued and total dollar loss.

![DATA COLLATION](https://user-images.githubusercontent.com/127628101/224696033-621bc1d5-e61b-43b2-8686-8305caba311d.png)

## STEP THREE: DATA VISUALIZATION
To visualize a dataset as a dashboard on Microsoft excel, I followed these steps

1. Prepare an idealistic sketch of how you want your dashboard to look using appropriate shape and styles.

2. Choose a chart type: Decide on the type of chart that best represents your data and serves your purpose, such as a bar chart, line chart, pie chart, etc.

3. Create a chart for each data you want to analyze.

4. Customize your chart: You can customize the chart by changing its colors, adding a title, axis labels, and data labels. You can also format the data series, modify the chart type, and add a data table.

5. Add additional charts: You can repeat the process to add multiple charts to the dashboard.

6. Add interactive elements: You can enhance your dashboard by adding interactive elements, such as drop-down lists, check boxes, and buttons, using Excel’s Forms controls.

7. Reference your values were necessary to visualize data such as total number or counts of data.

8. Ensure to save your dashboard after editing.

I wanted my visuals to include the images of fire ocurrence, so i downloaded the image from google and added it to my back ground. Please see the final look of my dashboard below.

![FIRE REPORT DASHBOARD NEW](https://user-images.githubusercontent.com/127628101/224700008-995b7664-b825-4ec6-9757-b46e8cee833c.png)

## CONCLUSION
Based on the dataset, it has become easy to deduce that:
- The most common causes of fire incidence are "Burners (Top range burners) as well as undetermined causes. and the most effective method of fire control.
- A large amount of incident wards have the fire alarm system installed.
- A total of 184million has been recorded as dollar loss due to damages caused by the incident.
A total number of 697 had been successfully rescued over the period of time.
- The top three area of fire occurence include the cooking area, Porch and Sleeping area.
