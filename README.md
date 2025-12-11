# Ex03 Time Table
## Date:11-12-2025

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
    <head>
        <title>TimeTable</title>
    </head>
    <body>
        <img src="logo.png" height="100" width="590">
        <h2>SLOT TIMETABLE-VISHVA S(25012833)</h2>
        <table border="3" cellspacing="3" cellpadding="8" width="550">
            <tr bgcolor="lightgreen">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">8-10</th>
                <td>FREE</td>
                <td>FREE</td>
                <td>CE</td>
                <td>CE</td>
                <td>FREE</td>
                <td>PYTHON</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">10-12</th>
                <td>FREE</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>WEB</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">1-3</th>
                <td>FREE</td>
                <td>CE</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>CE</td>
            </tr>
            <tr bgcolor="pink">
                <th bgcolor="lightgreen">3-5</th>
                <td>FREE</td>
                <td>PYTHON</td>
                <td>PYTHON</td>
                <td>PYTHON</td>
                <td>WEB</td>
                <td>FREE</td>
            </tr>
        </table>
        <br>
        <table border="3" cellspacing="3" cellpadding="3" width="585">
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/85018e77-a032-4353-9e4c-f9f3e01ccb2e" />

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
