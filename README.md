# Ex03 Time Table

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
<html>
     <head>
              <title> web </title>
     </head>
     <body bgcolor="black" TEXT="white">
<center>
     <img src="/static/images/saveethalogo.png"  height="100" width="1000" align="center" /></center>
          
          <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor=sky blue" align="center" >
          <CAPTION align=“top”> SLOT TIME TABLE - P.Ritik Samuel(212221040138) </CAPTION>
          <br>
          <br>
               <tr> 
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
            <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
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

![image](https://github.com/ritiksamuel/slot/assets/130056055/6af3497c-e0b8-47a9-be98-6ebe880765d3)


## HTML VALIDATOR


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
