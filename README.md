# Ex.03 Slot Time Table
## AIM
  To create slot time table.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the college logo using ```<img>``` tag.

### STEP-3
  Use the ```<table>``` tag with proper cell spacing and cell padding.  

### STEP-4
  Give your name and register number as table title using ```<caption>``` tag.

### STEP-5
  Enter the slot times and days as table header using ```<th>``` tag.
  
### STEP-6
  Type the subjects in the respective slots using ```<tr>``` and ```<td>``` tags.
 
### STEP-7
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
            <img src = "C:\sunil\saveetha logo.png" height = "90" width ="1000" >   
        </center>
           <br>
           <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="darkvoilet">
           <center><h3><b>SLOT TIME TABLE - SUNIL G (212223250022)</b></h3></center>
           <tr align="center">
           <th bgcolor="deeppink">Day/Time</th>
           <th bgcolor="deeppink">MONDAY</th>
           <th bgcolor="deeppink">TUESDAY</th>
           <th bgcolor="deeppink">WEDNESDAY</th>
           <th bgcolor="deeppink">THURSDAY</th>
           <th bgcolor="deeppink">FRIDAY</th>
           <th bgcolor="deeppink">SATURDAY</th>
           </tr>
           <tr align="center">
           <th bgcolor="deeppink">8-10</th>
           <td> PRINCIPLES OF HORTICULTURE</td>
           <td> FREE SLOT </td>
           <td> ENGINEERING MECHANICS </td>
           <td> FREE SLOT</td>
           <td> FREE SLOT </td>
           <td> FREE SLOT </td>
           </tr>
           <tr align="center">
           <th bgcolor="deeppink">10-12</th>
           <td> WASTE AND BY PRODUCTS</td>
           <td> MATHS  </td>
           <td> COMPUTER PROGRAMING</td>
           <td> WEB DESIGNING </td>
           <td> WEB DESIGNING </td>
           <td> FLUID MECHANICS</td>
           </tr>
           <tr>
           <th bgcolor="deeppink">12-1</th>
           <td colspan="6" align="center">L U N C H</td>
           </tr>
           <tr align="center">
           <th bgcolor="deeppink">1-3</th>
           <td> FLUID MECHANICS </td>
           <td> PRINCIPLES OF HORTICULTURE</td>
           <td> CREATIVE SKILLS</td>
           <td> THEORY OF MACHINES</td>
           <td> MATHS </td>
           <td> FREE SLOT </td>
           </tr>
           <tr align="center">
           <th bgcolor="deeppink">3-5</th>
           <td> FREE SLOT </td>
           <td> C PROGRAMING</td>
           <td> WASTE AND BY PRODUCTS </td>
           <td> FREE SLOT</td>
           <td> FREE SLOT</td>
           <td> FLUID MACHANICS</td
           </tr>
           </table>
           <br>
           <table align="center" cellspacing="2" cellpadding="4" border="2">
           <tr align="center">
           <th>S.NO.</th>
           <th>SUBJECT CODE</th>
           <th>SUBJECT NAME</th>
           </tr>
           <tr>
           <td align="center">1.</td>
           <td align="center">19CS307</td>
           <td> WEB DESIGNING </td>
           </tr>
           <tr>
           <td align="center">2.</td>
           <td align="center">19AG203</td>
           <td>PRINCIPLES OF HORTICULTURE</td>
           </tr>
           <tr>
           <td align="center">3.</td>
           <td align="center">19AG301</td>
           <td>FLUID MACHANICS</td>
           </tr>
           <tr>
           <td align="center">4.</td>
           <td align="center">19AG304</td>
           <td>THEORY OF MACHINES</td>
           </tr>
           <tr>
           <td align="center">5.</td>
           <td align="center">19AG408</td>
           <td>WASTE AND BY PRODUCTS</td>
           </tr>
           <tr>
           <td align="center">6.</td>
           <td align="center">19CS306</td>
           <td>COMPUTER PROGRAMING</td>
           </tr>
           <tr>
            <td align="center">7.</td>
            <td align="center">19EY702</td>
            <td>CREATIVE SKILLS</td>
            </tr>
            <tr>
            <td align="center">8.</td>
            <td align="center">19MA203</td>
            <td>MATHS</td>
             </tr>
           </table>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/sunil2410/Ex03_Web-Design/assets/168617270/893aabc7-b9ce-41b2-9fbc-055e733ea331)

## RESULT
 Slot time table is created successfully.
