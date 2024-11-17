# Ex03 Time Table
## Date:17.11.2024

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
<!DOCTYPE html>
<html>
    <head><title>SEC timetable</title</head>
        <body>
            <center>
                <img src=""/static/logo.png" height="100" width="550"
            </center>
            <table border="5"width="600">
                <tr>
                    <th bgcolor="yellow">day/time</th>
                    <th bgcolor="yellow">Monday</th>
                    <th bgcolor="yellow">Tuesday</th>
                    <th bgcolor="yellow">Wednesday</th>
                    <th bgcolor="yellow">Thursday</th>
                    <th bgcolor="yellow">Fridayday</th>
                   <th bgcolor="yellow">Saturday</th>
                </tr>
                <tr>
                    <th bgcolor="yellow">8-10</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Environmental science</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    </tr>
                <tr>
                    <th bgcolor="yellow">10-12</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Physics</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">C programming</th>
                    <th bgcolor="cyan">Probality and queueing models</th>
                </tr>
                <tr>
                    <th bgcolor="yellow">12-01</th>
                    <th bgcolor="green">Lunch</th>
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>  
                    <th bgcolor="green">Lunch</th>                  
                </tr>
                <tr>
                    <th bgcolor="yellow">01-03</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th bgcolor="cyan">Communicative english</th>
                    <th bgcolor="cyan">Mentor meet</th>
                    <th bgcolor="cyan">Web development</th>
                    <th bgcolor="cyan">Probability and queueing models</th>
                    <th bgcolor="cyan">Physics</th>
                </tr>
                <tr>
                    <th bgcolor="yellow">03-05</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">B.eee</th>
                    <th colspan="3" align="center"bgcolor="cyan">FREE SLOT</th>
                    <th bgcolor="cyan">Career developmemt</th>
                    <th bgcolor="cyan">Web developmemt</th>
                </tr>
            </table>
            <br>
            <table border="3" width="600">
                <tr>
                    <td>S.no</td>
                    <td>Subject code</td>
                    <td>Subject name</td>
                </tr>
                <tr>
                    <td>01</td>
                    <td>19AI304</td>
                    <td>C programming</td>
                </tr>
                <tr>
                    <td>02</td>
                    <td>19AI414</td>
                    <td>Web development</td>
                </tr>
                <tr>
                    <td>03</td>
                    <td>19EE305</td>
                    <td>B.eee</td>
                </tr>
                <tr>
                    <td>04</td>
                    <td>19EN101</td>
                    <td>Communicative english</td>
                </tr>
                <tr>
                    <td>05</td>
                    <td>19EY708</td>
                    <td>Career developmemt</td>
                </tr>
                <tr>
                    <td>06</td>
                    <td>19MA222</td>
                    <td>Probability and queueing models</td>
                </tr>
                <tr>
                    <td>07</td>
                    <td>SH3214</td>
                    <td>Physics</td>
                </tr>
                <tr>
                    <td>08</td>
                    <td>SH3214</td>
                    <td>Environmrntal science</td>
                </tr>
            </table>
        </body>
    
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-17 201248.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
