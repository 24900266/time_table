# Ex03 Time Table
# Date:18.10.24
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>𝐓𝐈𝐌𝐄 𝐓𝐀𝐁𝐋𝐄</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: blanchedalmond;(247, 246, 246);
        }
        table {
            border-collapse: collapse;
            margin: 20px auto;
            background-color: whitesmoke;(125, 202, 215);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: rgb(142, 177, 226);
        }
        td {
            background-color: whitesmoke;
        }
        .header img {
            width: 1000px;
        }
    </style>
</head>
<body>
    <div class="header" style="text-align: center;">
        <img src="logo.png" alt="Saveetha Logo">
        <h3>𝗧𝗜𝗠𝗘 𝗧𝗔𝗕𝗟𝗘 - 𝗣𝗥𝗘𝗘𝗧𝗛𝗔.𝗞(𝟮𝟰𝟵𝟬𝟬𝟮𝟲𝟲)</h3>
    </div>
    
    <table border="1" width="80%">
        <tr>
            <th>Day/Time</th>
            <th> 8-10 </th>
            <th> 10-12 </th>
            <th> 12-1 </th>
            <th> 1-2 </th>
            <th> 3-5 </th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>Free slot</td>
            <td rowspan="2">Free slot</td>
            <td rowspan="6">Lunch</td>
            <td>Web</td>
            <td>Free slot</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td>English</td>
            <td>Python</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>Free slot</td>
            <td>Career</td>
            <td>Mentor meet</td>
            <td>Chem</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td>Human Values</td>
            <td>Python</td>
            <td>Free slot</td>
            <td>Chem</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>English</td>
            <td rowspan="2">Web</td>
            <td rowspan="2">Python</td>
            <td rowspan="2">Free slot</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td>Free slot</td>
        </tr>
    </table>

    <table border="4" width="300" height="400" style="margin: 20px auto;">
        <tr>
            <th>S.NO</th>
            <th>Subject Name</th>
            <th>Subject Code</th>
        </tr>
        <tr>
            <th>1.</th>
            <td>Fundamentals of Web Applications</td>
            <td>19AI401</td>
        </tr>
        <tr>
            <th>2.</th>
            <td>Maths for AI/Python/Linear Algebra</td>
            <td>19MA301</td>
        </tr>
        <tr>
            <th>3.</th>
            <td>Principles of Chemistry</td>
            <td>19CY205</td>
        </tr>
        <tr>
            <th>4.</th>
            <td>Digital Electronics</td>
            <td>19EE404</td>
        </tr>
        <tr>
            <th>5.</th>
            <td>Career Development Skills</td>
            <td>19EY708</td>
        </tr>
        <tr>
            <th>6.</th>
            <td>Human Values and Professional Ethics</td>
            <td>SH7801</td>
        </tr>
    </table>
</body>
</html>

```
# OUTPUT
![alt text](<Screenshot 2024-12-05 223935.png>)
![alt text](<Screenshot 2024-12-05 224943.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
