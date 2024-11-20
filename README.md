# Ex03 Time Table
## Date: 20.11.2024

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
    <title>
      Slot_Timetable
    </title>
  </head>
  <center>
  <body>
    <img src="logo.png" width="800"><br><br>
   <CENTER><b>SLOT TIME TABLE -HAREKRISHNAA M (24900263)</b></CENTER><br>
    <table border="5"  width="50%" align="center" bgcolor="cyan">

      <tr>
         <th bgcolor="white">DAY/TIME</th>
         <th bgcolor="white">MONDAY</th>
         <th bgcolor="white">TUESDAY</th>
         <th bgcolor="white">WEDNESDAY</th>
         <th bgcolor="white">THURSDAY</th>
         <th bgcolor="white">FRIDAY</th>
         <th bgcolor="white">SATURDAY</th>
      </tr>

     
      <tr align="center">
         
         <td bgcolor="aqua">8:00AM-10:00AM</td> 
         <td>-</td> 
         <td bgcolor="green" style="color:aliceblue">BEEE</td> 
         <td bgcolor="yellow" style="color:black"> C</td> 
         <td bgcolor="orange" >PHY</td>        
         <td>-</td>
         <td>-</td>

      </tr>
      <tr align="center">
         <td>10:00AM-12:00PM</td> 
         <td bgcolor="pink" style="color:black">CERRER SKILLS</td> 
         <td bgcolor="brown"style="color:aliceblue"> DE </td> 
         <td bgcolor="green"style="color:aliceblue"> BEE </td> 
         <td>-</td>
         <td bgcolor="brown" style="color:aliceblue"> DE </td>
         <td bgcolor="blue" style="color:aliceblue"> FWAD </td>
      </tr>
      <tr>
         <td>12:00PM-1:00PM</td>
         <td align="center" COLSPAN="6">LUNCH BREAK
         </td>
 
      </tr>

      <tr align="center">
      <center><td>1:00PM-3:00AM</td> </center>
      <td bgcolor="yellow">C</td> 
      <td bgcolor="blue" style="color:aliceblue">FWAD</td> 
      <td>-</td> 
      <td bgcolor="gray" style="color:aliceblue">MENTOR MEET</td>
      <td bgcolor="blue" style="color:aliceblue">FWAD</td>
      <td bgcolor="orange">PHY</td>

     </tr>
   </table><br><br>

    <table border="5">

      <tr>
        <th>
          S.No
        </th>
        <th>
          Subject Code
        </th>
        <th>
          Subject Name
        </th>
      </tr>


      <tr>
        <th>
          1.
        </th>
        <th>
          19AI414
        </th>
        <th>
          Fundamentals of Web Application Development(FWAD)
        </th>
      </tr>


      <tr>
        <th>
          2.
        </th>
        <th>
          19EY708
        </th>
        <th>
          carrer developement skills
        </th>
      </tr>

      <tr>
        <th>
         3.
        </th>
        <th>
         19AI304
        </th>
        <th>
           Fundamentals of C programming
        </th>
      </tr>

      <tr>
        <th>
          4.
        </th>
        <th>
          SH3214
        </th>
        <th>
          physics for quantum computing
        </th>
      </tr>

      <tr>
        <th>
          5.
        </th>
        <th>
          19EE305
        </th>
        <th>
          Basic Electrical ,Electronics and Measurment Engineering(BEEE)
        </th>
      </tr>

      <tr>
        <th>
          6.
        </th>
        <th>
          19EE404
        </th>
        <th>
          Digital Electronics(DE)
        </th>
      </tr>
      </tr>
    </table>
  </body>
</center>
</html>
```

## OUTPUT

![alt text](tt.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
