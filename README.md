# Ex03 Time Table
## DATE
30/09/2023
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

## CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
        .table1{
            background-color: rgb(255, 255, 255);
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px;
        }
        .table2{
            border-color: gray;
            text-align: center;
            width: 800px;
            height: 250px; 
        }
        .name{
            padding-left: 185px;
        }
        .row1{
            background-color: rgb(254, 254, 254);
        }
        .c1{
            background-color: rgb(253, 249, 249);
        }
    </style>
</head>
<body>
    <img src = "http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x150/1623542614/logo_1.png" width = "800" height="150">
    <h3 class = "name">SLOT TIMETABLE - RITIK SAMUEL (212221040138)</h3>
    <table border="1" class = "table1">
        <tr class = "row1">
            <th bgcolor="sky blue">   DAY/TIME </th>
            <th bgcolor="sky blue">   MONDAY </th>
            <th bgcolor="sky blue">   TUESDAY </th>
            <th bgcolor="sky blue">   WEDNESDAY </th>
            <th bgcolor="sky blue">   THURSDAY </th>
            <th bgcolor="sky blue">   FRIDAY </th>
            </tr>
            <tr>
             <th bgcolor="sky blue"> 8-10 </th>
             <td> -- </td>
             <td> MPMC </td>
               <td> -- </td>
             <td> FWAD </td>
             <td> -- </td>
            </tr>
            <tr>
             <th bgcolor="sky blue"> 10-12 </th>
             <td> Computer Arc </td>
             <td> -- </td>
             <td> MAD </td>
             <td> Computer Arc </td>
             <td> -- </td>
            </tr>
            <tr>
             <th bgcolor="sky blue"> 12-1 </th>
              <td colspan="5" align="center">LUNCH TIME</td>
            </tr>
            <tr>
             <th bgcolor="sky blue"> 1-3 </th>
             <td> -- </td>
             <td> MAD </td>
             <td> -- </td>
             <td> MPMC </td>
             <td> Compiler </td>
            </tr>
            
           
           <tr>
            <th bgcolor="sky blue"> 3-5 </th>
            <td> Crypto </td>
            <td> FWAD </td>
            <td> Compiler </td> 
            <td> MPMC </td> 
            <td> Statictis </td>
           </tr>
        </table>
         <table border= "4" cellspacing="0px" cellpadding="10px"  align="left" >
        <tr>
        <th> S.No </th>
          <th> SUBJECT CODE </th>
        <th> SUBJECT NAME </th>
        </tr>
        <tr> 
        <td> 1. </td>
        <td> 19AI414 </td>
        <td> Fundamental of web application and development </td>
        </tr>
        <tr>
        <td> 2. </td>
        <td> 19CS305 </td>
        <td> Computer Architecture </td>
        </tr>
        <tr>
        <td> 3. </td>
        <td> 19CS412 </td> 
        <td> Cryptography and Network Security </td>
        </tr>
        <tr>
        <td> 4. </td>
        <td> 19CS409 </td>
        <td> Compiler Design </td>
        </tr>
        <tr>
        <td> 5. </td>
        <td> 19CS414 </td>
        <td> Mobile Application and Application Development </td>
        </tr>
        <tr>
        <td> 6. </td>
        <td> 19EC408 </td>
        <td> Microprocessor and Microprocessor </td>
        </tr>
        </table>
           
     </body>
</html>
```
## OUTPUT

![Slot](https://github.com/ritiksamuel/slot/assets/130056055/e1a9c9e2-99b9-482c-9895-ef6edce1f9a6)

![slot code](https://github.com/ritiksamuel/slot/assets/130056055/97467590-fe89-471a-bffa-874c99d97920)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
