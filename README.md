# Ex03 Time Table
## Date:17.04.25

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
        
    </head>
    <body>
        
        <center>
            
            
            <img src="/static/logo.png" height="100" width="550">
            
            <h1>SLOT TIMETABLE </h1>

            <br><h2> AAKIL AHAMED.S       <br> (reg no:212224040002)</h2>
            <hr color="black">
        </center>
        
        
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="yellow">
            <tr align="center">
                <th bgcolor="lime">DAY/TIME</th>
                <th bgcolor="lime">8:00-10:00</th>
                <th bgcolor="lime">10:00-12:00</th>
                <th bgcolor="lime">12:00-1:00</th>
                <th bgcolor="lime">1:00-3:00</th>
                <th bgcolor="lime">3:00-5:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="lime">MONDAY</th>
                <td>FREE SLOT</td>
                <td>PYTHON</td>
                <td>LUNCH</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>FREE SLOT</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="lime">TUESDAY</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>LUNCH </td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>FREE SLOT</td>
                
                
            </tr>
            <tr align="center">
                <th bgcolor="lime">WEDNESDAY</th>
                <td>FREE SLOT</td>
                <td>BEEE</td>
                <td>LUNCH</td>
                <td>MENTOR MEET</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr align="center">
                <TH bgcolor="lime">THURSDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
                <TD>LUNCH</TD>
                <TD>MATHS</TD>
                <TD>DIGITAL ELECTRONICS</TD>
            </tr>
            <TR align="center">
                <TH bgcolor="lime">FRIDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>PYTHON</TD>
                <TD>LUNCH</TD>
                <TD>HUMAN VALUES</TD>
                <td>FREE SLOT</td>

            </TR>
            <TR align="center">
                <TH bgcolor="lime">SATURDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>DIGITAL ELECTRONICS</TD>
                <TD>LUNCH</TD>
                <TD>BEEE</TD>
                <TD>MATHS</TD>

            </TR>
        </table>
        <BR>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO : </th>
                <TH>SUBJECT CODE :</TH>
                <TH>SUBJECT NAME :</TH>
            </tr>
            <TR align="center">
                <td>1.</td>
                <td>19AI414</td>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
            </TR>
            <TR align="center">
                <TD>2.</TD>
                <TD>19MA201</TD>
                <TD>MATHS</TD>
            </TR>
            <TR align="center">
                <TD>3.</TD>
                <TD>19HS801</TD>
                <TD>HUMAN VALUES</TD>
            </TR>
            <TR align="center">
                <TD>4.</TD>
                <TD>19PH814</TD>
                <TD>PHYSICS FOR QUANTUM COMPUTING</TD>
            </TR>
            <TR align="center">
                <TD>5.</TD>
                <TD>19EE404</TD>
                <TD>DIGITAL ELECTRONICS</TD>
            </TR>
            <TR align="center">
                <TD>6.</TD>
                <TD>19AI303</TD>
                <TD>PYTHON</TD>
            </TR>
            <TR align="center">
                <TD>7.</TD>
                <TD>19EE305</TD>
                <TD>BASIC ELECTRICAL,ELECTRONICS AND MEASUREMENT ENGINEERING</TD>
            </TR>
        </table>
        
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-17 111432.png>)
![alt text](<Screenshot 2025-04-17 111458.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
