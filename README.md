# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
<!DOCTYPE html>
<html>
<head>
<title>SEC Timetable</title>
</head>

<body>
<table border="5" width="600">
<tr>

<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr>
<th bgcolor="yellow">8-10</th>
<th colspan="3" align="center" bgcolor="cyan">FREE
SLOT</th>
<th bgcolor="cyan">PHY</th>
<th bgcolor="cyan">CHE</th>
</tr>
<tr>
<th bgcolor="yellow">10-12</th>
<th bgcolor="cyan">GER</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">PHY</th>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<th colspan="5" align="center" bgcolor="cyan">LUNCH</th>
</tr>
<tr>
<th bgcolor="yellow">1-3</th>
<td colspan="2" align="center" bgcolor="cyan">FREE
SLOT</th>
<th bgcolor="cyan">MAT</th>
<th bgcolor="cyan">MAT</th>
<th bgcolor="cyan">SS</th>
</tr>
<tr>
<th bgcolor="yellow">3-5</th>
<th colspan="2" align="center" bgcolor="cyan">FREE
SLOT</th>
<th bgcolor="cyan">GER</th>
<th bgcolor="cyan">CHE</th>
<th bgcolor="cyan">FWAD</th>
</tr>
</table>
<br>
<table border="3" width="600">
<tr>
<td>S.NO.</td>
<td>Subject Code</td>
<td>Subject Name</td>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement (FWAD)

</td>
</tr>
<tr>
<td>2.</td>
<td>19EN612</td>
<td>German Basic (GER)</td>
</tr>
<tr>
<td>3.</td>
<td>19PH206</td>
<td>Physics for Information Technology (PHY)</td>
</tr>
<tr>
<td>4.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td>5.</td>
<td>19MA201</td>
<td>Calculus and Matrix Algebra (MAT)</td>
</tr>
<tr>
<td>6.</td>
<td>19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
</table>
</body>
</html>

## OUTPUT
![image](https://github.com/23007965/slot/assets/138971238/c5ca127d-d95e-4b84-93f3-186ff141bf44)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
