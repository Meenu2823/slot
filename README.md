# Ex03 Time Table
## Date: 03.04.24

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
### HTML Code:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Time table</title>
    {% load static %}
    <link rel="stylesheet" href="{% static 'css/table.css' %}">
</head>
<body>
   <img src="{% static 'images/SEC LOGO NEW.png' %}" style="width: 60%;height: 10%;padding-left: 20%;" alt="">
   <h1 style="text-align: center;font-size: 20px;"><b>SLOT TIME TABLE - MEENU.S(212223230124)</b></h1>
  
   <table border="2px" class="table">
    <tr class="attributes">
    <th>Time/Day</th>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
    <th>Thursday</th>
    <th>Friday</th>
    </tr>
    <tr>
        <td class="attributes"><b>8-10</b></td>
        <td>FREE SLOT</td>
        <td>DE</td>
        <td>FWAD</td>
        <td>DE</td>
        <td>SQM</td>
    </tr>
    <tr>
    <td class="attributes"><b>10-12</b></td>
    <td colspan="2">FREE SLOT</td>
    <td>ACP</td>
    <td>CSFC</td>
    <td>FREE SLOT</td>
    </tr>
    <tr>
        <td class="attributes"><b>12-1</b></td>
        <td colspan="5">LUNCH</td>
    </tr>
    <tr>
        <td class="attributes"><b>1-3</b></td>
        <td>FREE SLOT</td>
        <td>PHY</td>
        <td>PHY</td>
        <td>SQM</td>
        <td>ACP</td>
    </tr>
    <tr>
        <td class="attributes"><b>3-5</b></td>
        <td>FWAD</td>
        <td>ITDS</td>
        <td>FREE SLOT</td>
        <td>CN</td>
        <td>FREE SLOT</td>
    </tr>
   </table>
   <table border="2px">
    <tr>
        <th><b>S.No</b></th>
        <th><b>Subject Code</b></th>
        <th class="table2"><b>Subject Name</b></th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development(FWAD)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI305</td>
        <td>Advanced C Programming(ACP)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19PH214</td>
        <td>Physics for Quantum Computing(PHY)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19EE404</td>
        <td>Digital Electronics(DE)</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19EY702</td>
        <td>Creative Skills For Communication(CSFC)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19MA211</td>
        <td>Statistics and Numerical Methods(STATS)</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19CS406</td>
        <td>Computer Networks(CN)</td>
    </tr>
    <tr>
        <td>8.</td>
        <td>19AI403</td>
        <td>Introduction To Data Science(ITDS)</td>
    </tr>
   </table>
</body>
</html>
~~~
### CSS Code:
~~~
table{
    text-align: center;
    margin-left: 28%;
    margin-top: 1%;
}
.table
{
    background-color: aqua;
}
.attributes{
    background-color: yellow;
}
td,th{
    width: 100px;
    height: 30px;
}
.table2{
    width:420px;
}
~~~
## OUTPUT

![Screenshot 2024-04-03 213149](https://github.com/Meenu2823/slot/assets/139416219/1f5d622a-d190-4ed0-8ae0-00411fbe6f87)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
