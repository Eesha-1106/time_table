# Ex03 Time Table
# Date:18-10-2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using ``<th>`` tag.

## STEP 5
Add your timetable using ``<td>`` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```

<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Timetable</title>
</head>
<body>
 

 <img src="\static\sec.png" width="800px" height="100px"> 
 <h1></h1>
 
 <table width="800px">
   <tr align="center">
     <tH>SLOT TIME TABLE - EESHA RANKA (24900107)</th>
   </tr>
 </table>
 <table border='3'  style="background-color:burlywood" width="800px" height="200px"  >
   <tr style="background-color:yellow" align="center">
     <th width="100">Day/ Time</th>
     <th width="100">Monday</th>
     <th width="100">Tuesday</th>
     <th width="100">Wednesday</th>
     <th width="100">Thursday</th>
     <th width="100">Friday</th>
     <Th width="100">Saturday</Th>
   </tr>
   <tr align="center">
     <th style="background-color:yellow " >8-10</th>
     <td>Free slot</td>
     <td>BEEME</td>
     <td >Free slot</td>
     <td colspan="2">Machine learning</td>
     <td>Statistics</td>
   </tr>
   <tr align="center" >
     <th  style="background-color:yellow ">10-12</th>
     <td>Comm. Eng</td>
     <td>Statistics</td>
     <td>BEEME</td>
     <td>C programming</td>
     <td colspan="2">Web application</td>
   </tr>
   <tr align="center" >
     <th  style="background-color:yellow ">12-1</th>
     <td colspan="6" align="center">L U N C H</td>
   </tr>
   <tr align="center" >
     <th  style="background-color:yellow ">1-3</th>
     <td>web application</td>
     <td>Comm. Eng</td>
     <td>Mentor meet</td>
     <Td>Free slot</Td>
     <td>C programming</td>
     <td>Career developement</td>
   </tr>
 </table>
 <h1></h1>
 <table border="3" width="800px" height="300px">
   <tr>
      <th>S.no</th>
     <th>Subject code</th>
     <th>Subject name</th></tr>
   <tr>
     <th>1.</th>
     <th>19AI414</th>
     <th>Fundamentals of web application</th>
   </tr>
   <tr></tr>
     <th>2.</th>
     <th>19AI410</th>
     <th>Introduction to Machine Learning</th>
   </tr>
   <tr></tr>
     <th>3.</th>
     <th>19AI304</th>
     <th>Fundamentals of C programming</th>
   </tr>
   <tr></tr>
     <th>4.</th>
     <th>19MA211</th>
     <th>Statistics and Numerical Methods</th>
   </tr>
   <tr></tr>
     <th>5.</th>
     <th>19EE305</th>
     <th>Basic Electrical,Electronics and Measurement Engineering(BEEME) </th>
   </tr>
   <tr></tr>
     <th>6.</th>
     <th>19EN101</th>
     <th>communicative English(Comm. Eng)</th>
   </tr>
   <tr></tr>
     <th>7.</th>
     <th>19EY708</th>
     <th>Career Development Skills</th>
   </tr>
 
 </table>
 
</body>
</html>

```

# OUTPUT

![alt text](<timetable ss.PNG>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
