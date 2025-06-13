# Ex03 Time Table
## Date:

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
html:
<!DOCTYPE html>
<html lang="en">
<head>

<title>Time? what</title>
<link rel="stylesheet" href="style.css"> 




</head>

<body>
   <header>
<img src="/static/logo.png" alt="logo?" class = "logo">

</header>
<table class ="firsttab">
    <caption class="tabletitle">SLOT TIMETABLE - SWETHA NIVASINI B R</caption>
    <tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
    </tr>
    <tr>
        <td>8-10</td>
        <td>PYTHON PROGRAMMING</td>
        <td>MODULE COMPLETION</td>
        <td>TASK COMPLETION</td>
        <td>ASSESSMENT HOUR</td>
        <td>DATA SCIENCE</td>
    </tr>
    <tr>
        <td>10-12</td>
        <td>ASSESSMENT HOUR</td>
        <td>DATA SCIENCE</td>
        <td>DATA SCIENCE</td>
        <td>ADV C PROGRAMMING</td>
        <td>PYTHON PROGRAMMING</td>
    </tr>
    <tr>
        <td>12-1</td>
        <td colspan="5" class="lunch">LUNCH</td>

    </tr>
    <tr>
        <td>1-3</td>
        <td>MACHINE LEARNING</td>
        <td>ADV C PROGRAMMING</td>
        <td class="mentor">MENTOR MEET</td>
        <td>MACHINE LEARNING</td>
        <td>MODULE COMPLETION</td>
    </tr>

<table class="secondtab">
<tr>
    <th>S.No</th>
    <th>Subject Code</th>
    <th>Subject Name</th>
</tr>
<tr>
 <td>1</td>
 <td>19AI414</td>
 <td>DATA SCIENCE</td>
</tr>
<tr>
    <td>2</td>
    <td>19CS304</td>
    <td>ADV C PROGRAMMING</td>
</tr>
<tr>
    <td>3</td>
    <td>19AI404</td>
    <td>PYTHON PROGRAMMING</td>
</tr>
<tr>
    <td>4</td>
    <td>19CS504</td>
    <td>MACHINE LEARNING</td>
</tr>
</table>

</body>





</html>

css:
.logo{
display: block;
margin: 0 auto;
width: 1250px;
margin-bottom: 30px
}
.tabletitle{
    text-align: center;
    color: black;
    font-size: 20px;
    font-weight: bold;
}
.firsttab{
    
    margin: 20px auto;
    border-collapse: collapse;
    border-color: white;
    margin-bottom: 50px;
    border-width: 5px;
    border-color: rgb(2, 10, 61);
}
body{
font-family: Arial,sans-serif;
text align: centre;
background-color: #f4f4f4;
margin: 0;
padding: 20px;
}

.secondtab{
    margin-top: 50px;
    margin: 20px auto;


}
.secondtab th {
    border: 1px solid black;
    padding: 10px;
    background-color: rgb(2, 10, 61);
    color: white;
}
.firsttab th {
    border: 1px solid black;
    padding: 10px;
    background-color: rgb(2, 10, 61);
    color: white;
    border-color: aliceblue;
}

.lunch {
    
    text-align: center;
    vertical-align: middle;
    font-weight: bold;
}
table, th, td {
    border: 2px solid black; 
    border-collapse: collapse; 
    padding: 10px; 
    text-align: center; 
}
.mentor{
    color: rgba(237, 251, 251, 0.817);
    background-color: rgb(74, 234, 220);
    font-weight: bold;
}
.firsttab td:first-child {
    background-color: rgb(2, 10, 61);
    color: rgb(238, 240, 242);
    font-weight: bold;
    text-align: center;
    padding: 10px;
    border-color: aliceblue;
}

header h1 {
    margin-bottom: 0px;
}

```


## OUTPUT


![Screenshot 2025-05-27 211507](https://github.com/user-attachments/assets/54075bff-ba8d-4682-ac8d-049958d873ca)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
