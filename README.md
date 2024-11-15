# Ex03 Time Table
## Date:15/11/2024

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
```
<html>
<body>
<table border="2" cellspacing="15" cellpadding="5">
    <caption>SLOT TIMETABLE-NIKILA D(24900699)</caption>
    <tr bgcolor="yellow">
        <th>DAY/TIME</th>
        <th> MONDAY</th>
        <th> TUESDAY</th>
        <th>WEDNESDAY</th>
        <th>THURSDAY</th>
        <th>FRIDAY</th>
        <th>SATURDAY</th>
    </tr>
    <tr>
    <td>8-10</td>
    <td>FREE SLOT</td>
    <td>WEB</td>
    <td>PYTHON</td>
    <td>FREESLOT</td>
    <td>PHYSICS</td>
    <td>FREESLOT</td>
</tr>
<tr>
    <td>10-12</td>
    <td>C PROGRAMMING</td>
    <td>PHYSICS</td>
    <td>CAREER</td>
    <td>PYTHON</td>
    <td>C PROGRAMMING</td>
    <td>PYTHON</td>
</tr>
<tr>
    <td>12-1</td>
    <td colspan="6">LUNCH BREAK</td>
</tr>
<tr>
<td>1-3</td>
<td>BEEE</td>
<td>PYTHON</td>
<td>MENTOR</td>
<td>FREESLOT</td>
<td>WEB</td>
<td>WEB</td>
</tr>
<tr>
    <td>3-5</td>
    <td>BEE</td>
    <td colspan="5">FREEE SLOT</td>
</tr>
</table>
<table border="2" cellspacing="15" cellpadding="5">
    <caption COURSES >
        <tr bgcolor="cyan">
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPEMENT(WEB)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI301C</td>
            <td>PYTHON AND LINEAR ALGEBRA</td>
        </tr>
        <tr>
            <td>3</td>
            <td>SH3214</td>
            <td>PHYSICS FOR QUANTUM COMPUTING</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE305</td>
            <td>BASIC ELECTRICAL AND ELECTRONIC ENGINEERING</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPEMENT SKILLS</td>
        </tr>
        <tr>
            <td>7</td>
            <td>ECA-M-SCOFT</td>
            <td>MENTOR MEET</td>
        </tr>
</table>
</html>
</body>
```

## OUTPUT
![alt text](<Screenshot (11).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
