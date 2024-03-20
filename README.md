# Ex03 Time Table
## Date:20/03/2024

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
       <title> TIME TABLE </title>
   </head>
 <body align="center">
 <table border="6" cellspacing="6" cellpadding="8" align="center" bgcolor="PINK">
<img src="logo.png" align="center" height="70" width="800">
<caption><b>SLOT TIMETABLE- JAYAHARI E(212221040065)</b></caption>

   <tr>
        <th bgcolor="red">Day/Time</th>
        <th bgcolor="red">Monday</th>
        <th bgcolor="red">Tuesday</th>
        <th bgcolor="red">Wednesday</th>
        <th bgcolor="red">Thursday</th>
        <th bgcolor="red">Friday</th>
  </tr>
  <tr>
        <th bgcolor="red">8-10</th>
        <td>WDM</td>
        <td>DPSD</td>
        <td>FWAD</t>
        <td>DIA</td>
        <td>CE</td>
 </tr>
 <tr>
        <th bgcolor="red">10-12</th>
        <td>DIA</td>
        <td>FWAD</td>
        <td>Free Slot</t>
        <td>CE</td>
        <td>DPSD</td>
 </tr>
 <tr> 
        <th bgcolor="red">12-1</th>
        <TD colspan="5" Align="center"><B>L U N C H </B></TD> </tr>
 <tr>
        <th bgcolor="red">1-3</th>
        <td>FWAD</td>
        <td>NN</td>
        <td>Free Slot</t>
        <td>WDM</td>
        <td>EES</td>
 </tr>
 <tr>
        <th bgcolor="red">3-5</th>
        <td>Free Slot</td>
        <td>Free Slot</td>
        <td>NN</t>
        <td>DPSD</td>
        <td>Free Slot</td>
</tr>
</body>
</html>
<table cellspacing="8" cellpadding="0" align="center">
<html>
<head>
    <title> Subject code </title>
</head>
 <body>
 <table border="6" cellspacing="7" cellpadding="8" align="center">

<tr> 
        <th>S.NO</th>
        <th>Subject Code</th>
        <th>Subject</th>
</tr>        
<tr>
     <td>1</td>
     <td>19AI414</td>
     <td>Fundamentals of Web Application Development(FWAD)</td>
</tr>    
<tr>
     <td>2</td>
     <td>19AI411</td>
     <td>Neural Networks(NN)</td>
</tr> 
<tr>
     <td>3</td>
     <td>19AI412</td>
     <td>Web Data Mining(WDM)</td>
</tr>     
<tr>
     <td>4</td>
     <td>19EC307</td>
     <td>Communication Engineering(CE)</td>
</tr>   
<tr>
     <td>5</td>
     <td>19CS402</td>
     <td>Design and Analysis of Algorithm(DIA)</td>
</tr>  
<tr>
     <td>6</td>
     <td>19EC303</td>
     <td>Digital Principles and System Design(DPSD)</td>
</tr>  
<tr>
     <td>5</td>
     <td>19EY705</td>
     <td>Employment Enhancement Skills</td>
</tr>  

</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-20 110328.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
