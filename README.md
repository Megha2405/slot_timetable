# Ex02 Time Table
## Date:07/02/2026

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Class Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f4f6;
            text-align: center;
        }

        .logo {
            width: 150px;
            margin-top: 20px;
        }

        h2, h3 {
            margin-top: 15px;
        }

        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        th, td {
            border: 2px solid #000;
            padding: 12px;
            font-weight: bold;
        }

        th {
            background: #ffeb3b;
        }

        .time {
            background: #ffeb3b;
        }

        .subject {
            background: #4dd0e1;
        }

        .subject-details {
            background: #ffffff;
        }

        .subject-details th {
            background: #dcdcdc;
        }
    </style>
</head>
<body>

    
    <img src="/static/logo.png" height="100" width="500">

    <h2>SAVEETHA ENGINEERING COLLEGE</h2>
    <h3>Megha S(212224230157)</h3>

    
    <table>
        <tr>
            <th>Day / Time</th>
            <th>8–10</th>
            <th>10–12</th>
            <th>1–3</th>
            <th>3–5</th>
        </tr>

        <tr>
            <td class="time">Monday</td>
            <td class="subject">FWAD</td>
            <td class="subject">FAI</td>
            <td class="subject">Cryptography</td>
            <td></td>
        </tr>

        <tr>
            <td class="time">Tuesday</td>
            <td class="subject">FWAD</td>
            <td class="subject">FAI</td>
            <td class="subject">Cryptography</td>
            <td></td>
        </tr>

        <tr>
            <td class="time">Wednesday</td>
            <td class="subject">FAI</td>
            <td class="subject">FWAD</td>
            <td class="subject">Cryptography</td>
            <td></td>
        </tr>

        <tr>
            <td class="time">Thursday</td>
            <td class="subject">FWAD</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>

        <tr>
            <td class="time">Friday</td>
            <td class="subject">FWAD</td>
            <td class="subject">FAI</td>
            <td class="subject">Cryptography</td>
            <td></td>
        </tr>

        <tr>
            <td class="time">Saturday</td>
            <td class="subject">FAI</td>
            <td class="subject">Cryptography</td>
            <td></td>
            <td></td>
        </tr>
    </table>

    <h3>Subject Details</h3>

    <table class="subject-details">
        <tr>
            <th>S.No</th>
            <th>Subject Name</th>
            <th>Subject Room</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
            <td>T1-U8</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Fundamentals of Artificial Intelligence (FAI)</td>
            <td>T1-P13</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Cryptography</td>
            <td>T1-E7</td>
        </tr>
    </table>

</body>
</html>

```


## OUTPUT
![alt text](<slot_timetable/Screenshot 2026-02-08 205921.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
