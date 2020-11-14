# Database Sets
Create your own data sets to display on maps.

!!! Warning "Alpha Version"
    Feature still under development.
    
## Creating a set
Enter a name for the set in the input field and hit enter. 
Your set and a tab for it were created and you are ready to edit its details:

|  |  |
|--|--|
| Name | The name of the set is also displayed in the tabs |
| Description | Describe the data the set holds |
| Color Mode | Choose on how the data gets colored |
| Color Low | This color is used for the lowest value of the set |
| Color High | This color is used for the highest value of the set |
| ... | ... under development |

!!! Information "Low and high values"
    Lowest and highest values are chosen globally at the moment = If the highest or lowest values for that set are on another map those values will still be used for coloring. If you would like a mode where low and high are calculated from the displayed systems only please let me know (use the [feedback forum](https://feedback.userreport.com/7ab42bbb-8bf8-4955-9573-c0b1213b1ba7/#ideas/popular) please). 

### Individual color mode
Will color each distinct value or label with an own color. If a label and a value were entered the vlaue will be used for selecting a color automatically.

### Linear and Logarithmic color modes
Only numeric values can be colored using these modes. The lowest and highest value's colors can be set via the set's details. Other value's colors get interpolated. To understand how those modes work it is best to enter some values to a set and switch the modes. Use like 1,2,3,4,5,10,20,50,1000,5000 for seeing the difference easily.

## Adding Data
To add data you need to load a map. Opening a database set's details will show all systems on that map in a table. Edit the data and watch the map display it right away. You can right-click a system, to bring it to top and put the cursor in the value's input field to edit right away.

## Data Display
When opening a set's details the display options `Node` and `Label` will get activated automatically. You can  display your data via `Sectors` or `Tags` aswell. Please select them via the data displays menu. 

!!! Information "Feedback"
    Feedback very welcome ! Please use the [feedback forum](https://feedback.userreport.com/7ab42bbb-8bf8-4955-9573-c0b1213b1ba7/#ideas/popular)  


<!--stackedit_data:
eyJoaXN0b3J5IjpbNjA0MjA3OTEsMjk3OTExNzg1LDUwMjM1NT
Y2MCw3MzA3Mjk1MjIsNDA5NzUwMCwtMjI1MjA1MTUxLDIwMjQ0
OTE1NTRdfQ==
-->