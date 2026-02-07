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
            font-family: 'Segoe UI', Tahoma, sans-serif;
            background: linear-gradient(135deg, #e3f2fd, #fce4ec);
            padding: 30px;
        }

        h1 {
            text-align: center;
            color: #2c3e50;
            margin-bottom: 25px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-radius: 12px;
            overflow: hidden;
        }

        th {
            background: linear-gradient(135deg, #3949ab, #1e88e5);
            color: white;
            padding: 15px;
            font-size: 15px;
        }

        td {
            padding: 14px;
            text-align: center;
            font-size: 14px;
            color: #333;
        }

        tr:nth-child(even) {
            background-color: #f5f7fa;
        }

        tr:hover {
            background-color: #e3f2fd;
            transition: 0.3s;
        }

        .subject {
            font-weight: bold;
            color: #1a237e;
        }

        .room {
            font-size: 11px;
            color: #777;
        }
    </style>
</head>
<body>

<center>
<img src="/static/logo.png" height="100" width="500">
</center>


<h1>📘 Weekly Class Timetable</h1>

<table>
    <tr>
        <th>Day</th>
        <th>8:00 – 10:00</th>
        <th>10:00 – 12:00</th>
        <th>1:00 – 3:00</th>
        <th>3:00 – 5:00</th>
    </tr>

    <tr>
        <td><b>Monday</b></td>
        <td class="subject">FWAD<br><span class="room">T1-U8</span></td>
        <td class="subject">FAI<br><span class="room">T1-P13</span></td>
        <td class="subject">Cryptography<br><span class="room">T1-E7</span></td>
        <td>—</td>
    </tr>

    <tr>
        <td><b>Tuesday</b></td>
        <td class="subject">FWAD<br><span class="room">T1-U8</span></td>
        <td class="subject">FAI<br><span class="room">T1-P13</span></td>
        <td class="subject">Cryptography<br><span class="room">T1-E7</span></td>
        <td>—</td>
    </tr>

    <tr>
        <td><b>Wednesday</b></td>
        <td class="subject">FAI<br><span class="room">T1-P13</span></td>
        <td class="subject">FWAD<br><span class="room">T1-U8</span></td>
        <td class="subject">Cryptography<br><span class="room">T1-E7</span></td>
        <td>—</td>
    </tr>

    <tr>
        <td><b>Thursday</b></td>
        <td class="subject">FWAD<br><span class="room">T1-U8</span></td>
        <td>—</td>
        <td>—</td>
        <td>—</td>
    </tr>

    <tr>
        <td><b>Friday</b></td>
        <td class="subject">FWAD<br><span class="room">T1-U8</span></td>
        <td class="subject">FAI<br><span class="room">T1-P13</span></td>
        <td class="subject">Cryptography<br><span class="room">T1-E7</span></td>
        <td>—</td>
    </tr>

    <tr>
        <td><b>Saturday</b></td>
        <td class="subject">FAI<br><span class="room">T1-P13</span></td>
        <td class="subject">Cryptography<br><span class="room">T1-E7</span></td>
        <td>—</td>
        <td>—</td>
    </tr>
</table>

</body>
</html>
```


## OUTPUT
![alt text](<slot_timetable/Screenshot 2026-02-07 214853.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
