 Schedule
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Schedule</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body, html {
            width: 100%;
            height: 100%;
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
            text-align: center;
            overflow-x: hidden;
        }
        table {
            width: 60%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #ffffff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #007BFF;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        .highlight {
            background-color: #ffeb3b;
        }
    </style>
</head>
<body>
    <h1>My Busy Day Schedule</h1>
    <table>
        <tr>
            <th>Time</th>
            <th>Task</th>
        </tr>
        <tr>
            <td>7:00 AM</td>
            <td>Wake up and exercise</td>
        </tr>
        <tr>
            <td>7:40 AM</td>
            <td>Shower and get dressed</td>
        </tr>
        <tr class="highlight">
            <td>8:10 AM</td>
            <td>Breakfast</td>
        </tr>
        <tr>
            <td>8:30 AM</td>
            <td>Check emails and plan tasks</td>
        </tr>
        <tr>
            <td>8:50 AM</td>
            <td>Do my homework</td>
        </tr>
        <tr>
            <td>12:30 PM</td>
            <td>Lunch break</td>
        </tr>
        <tr class="highlight">
            <td>2:00 PM</td>
            <td>Go for a walk with my dog</td>
        </tr>
        <tr>
            <td>6:00 PM</td>
            <td>Training</td>
        </tr>
        <tr>
            <td>7:40 PM</td>
            <td>Dinner</td>
        </tr>
        <tr>
            <td>9:00 PM</td>
            <td>Relax and watch a film</td>
        </tr>
    </table>
</body>
</html>
