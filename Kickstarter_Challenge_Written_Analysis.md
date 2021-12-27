# Kickstarting with Excel

## Overview of Project
This project was to compare Kickstarter projects by category to discover what was successful, and what was not.

### Purpose
To drill down into the Theater category of Kickstarter projects to see if there was a correlation between the time of year and the success or failure of a project.  Further insight came while analyzing the Plays subcategory to see if there was correlation between the size of the goal and success or failure
## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
There was no real correlation between success or failure based on the time of year of the projects.  However, there was a definite spike in the number of Kickstarter projects during the summer months, and a higher number of successfully funded projects during that time as well.

### Analysis of Outcomes Based on Goals
When conducting a deep dive into the Theater/Plays subcategory, the success of the project based on goal size seemed to follow an inverted bell curve.  While smaller or very large projects tended to be successfully funded, the middle segments did not seem to be nearly as successful.  This may be due to small projects having an easier hurdle to success, and larger projects being big ideas or movements that can get broad based support behind it.

### Challenges and Difficulties Encountered
The only real challenge encountered in the project was with the countifs statement when trying to only bring in, for example, successful Theater/Plays projects only.  The difficulty was when trying to only return between two numbers (i.e. 1000 to 4999), as I didn't realize each number had to be expressed in separate criteria range and criteria within the function.  I was able to find help on Google using this [link](https://www.extendoffice.com/documents/excel/2412-excel-count-cells-between-two-values.html).	

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

##### That the summer months have are both busier with total projects started through Kickstarter, and also see a correlation of successful projects that increase in those summer months.

- What can you conclude about the Outcomes based on Goals?

#####	As stated earlier, the percentage of successful projects seems to follow an inverted bell curve, with smaller or very large projects having the most success.

- What are some limitations of this dataset?

#####	All of the data has very broad based descriptors, such as Plays or what country it originated from.  Having more detail on these data points could lead to a more detailed analysis that could help discover what sets successful projects apart.

- What are some other possible tables and/or graphs that we could create?

#####	You could incorporate some tables or graphs that bring in two variables, staff pick and spotlight.  These could provide additional detail on what is successful or not based on those two identifiers.
