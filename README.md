# Ex02 Time Table
# Date:28/11/25
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>

<img src="sat.jpg"
width="594px,">

<br>
   <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
    <caption><b>SLOT TIME TABLE - sathish v (25012470)</b></caption>
    <tr align="center">
    <th bgcolor="yellow">Day/Time</th>
    <th bgcolor="yellow">Monday</th>
    <th bgcolor="yellow">Tuesday</th>
    <th bgcolor="yellow">Wednesday</th>
    <th bgcolor="yellow">Thursday</th>
    <th bgcolor="yellow">Friday</th>
    <th bgcolor="yellow">saturday</th>
</tr>
    <tr align="center">
    <th bgcolor="yellow">8–10</th>
    <td>Fundamentals of web Application Development</td>
    <td>Fundamentals of web Application Development</td>
    <td>Fundamentals of web Application Development</td>
    <td>free slot</td>
    <td>Free slot</td>
    <td>python PROGRAMMING</td>
</tr>
    <tr align="center">
    <th bgcolor="yellow">10-12</th>
    <td>FREE SLOT</td>
    <td>python PROGRAMMING</td>
    <td>FREE slot</td>
    <td>FREE SLOT</td>
    <td>free slot</td>
    <td>free slot</td>
</tr>
<tr>
    <th bgcolor="yellow">12-1</th>
    <td colspan="6" align="center">L U N C H</td>
</tr>
    <tr align="center">
    <th bgcolor="yellow">1-3</th>
    <td>Fundamentals of web Application Development</td>
    <td>FREE SLOT</td>
    <td>mentor meet</td>
    <td>FREE SLOT</td>
    <td>Fundamentals of web Application Developmen</td>
    <td>python PROGRAMMING</td>
</tr>
    <tr align="center">
    <th bgcolor="yellow">3-5</th>
    <td>FREE SLOT</td>
    <td>python PROGRAMMING</td>
    <td>python PROGRAMMING</td>
    <td>python PROGRAMMING</td>
    <td>free slot</td>
    <td>free slot</td>
</tr>
</table>
<br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
    <th>S. No.</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19 AI301</td>
<td>PYTHON PROGRAMMING (python PROGRAM)</td>
</tr>
</table>
</body>
</html>
 ```


# OUTPUT
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/e188287c-5ccb-40b4-87e2-05305db6284b" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
