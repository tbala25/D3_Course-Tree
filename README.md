# D3_Course-Tree

README

The Visualization:
https://tbala25.github.io/D3_Course-Tree/

Template Code Sources:
http://bl.ocks.org/d3noob/fa0f16e271cb191ae85f
https://bl.ocks.org/mbostock/4339083


Using the Visualization:
The tree defaults to rendering with Northeastern and the programs open
Clicking on a college or program causes the courses within it to expand out. Clicking on the program again will make it collapse back in.
Selecting a college or course will update the information to the right with that selection’s data
Clicking and dragging anywhere within the tree (whitespace or a course) will allow you to pan around the visualization
Zooming in and out is accomplished by using the scroll wheel on a mouse or using a two-finger drag on a multitouch trackpad

Data:
The code, style and all, is all contained in the index.html file
The data is stored in the data1.csv file, which can be edited in Excel
To add or update data points, just open data1.csv and add content to the document. 
Without modifying the code, the document must be named data1.csv and it must be in CSV format
The CSV file is alphabetized by course, and then the colleges are alphabetized below that, with NEU at the very bottom
Within each level (college, courses), the order they appear in the tree is determined by the order they are in in the CSV file. Thus, it’s important to keep the document sorted properly.
Adding new courses should cause no problems, just so long as they are added and formatted properly. There’s no limit to how many rows you can add
