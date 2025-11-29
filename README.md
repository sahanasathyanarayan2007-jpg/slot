# Ex02 Time Table
## Date:27-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
time.html
```
<html>
    <head>
        <title>Slot timetable</title>
    </head>

    <body>
        <center>
            <img src="logo.png" height="100" width="540"
        </center>
        <br>
        <table align="center" border="5" cellspacing="2" cellpadding="4" width="540" bgcolor="Skyblue">
            <caption><b>SLOT TIME TABLE-SAHANA S (25004522)</b></caption>
            <tr align="center">
                <th bgcolor="pink">Day/Time</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
                <th bgcolor="pink">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="pink">8-10</th>
                <td colspan="2">COMMUNICATIVE ENGLISH</td>
                <td>FWAD</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>


            
                
            </tr>
            <tr align="center">
                <th bgcolor="pink">10-12</th>
                <td colspan="3">FWAD</td>
                <td colspan="2">FREE SLOT</td>
                <td>COMMUNICATIVE ENGLISH</td>
        
            </tr>
            <tr align="center">
                <th bgcolor="pink">12-1</th>
                <td colspan="6">L U N C H</td>

            </tr>
            <tr align="center">
                <th bgcolor="pink">1-3</th>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td>MENTOR MEET</td>
                <td>COMMUNICATIVE ENGLISH</td>
                <td>FREE SLOT</td>
                <td>PYTHON PROGRAMMING</td>

            </tr>
            <tr align="center">
                <th bgcolor="pink">3-5</th>
                <td>PYTHON PROGRAMMING</td>
                <td colspan="3">FREE SLOT</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" border="5" cellspacing="2" cellpadding="4" width="540">
            <tr align="center">
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
                
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            

            </tr>
            <tr>
                <td>2</td>
                <td>19EN101</td>
                <td>COMMUNICATIVE ENGLISH</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>

            
 
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (25).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
