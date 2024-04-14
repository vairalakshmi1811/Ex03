# Ex.03 Slot Time Table
## DATE:08/04/2024
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
        <title>time table</title>
    </head>
    <body>
        <img src="D:\official\sec logo.png" height="200" width="1200px"/>
        <h1 align="center">SLOT TIME TABLE</h1>
        <h2 align="center">VAIRALAKSHMI(212223250024)</h2>
        <table border="5" width="85%" height="30%" align="center" cellspacing="4.5" cellpadding="3" bgcolor="pink">
            <tr bgcolor="green">
                <th>TIMING/DAYS</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <th bgcolor="green">08-10</th>
                <th>Horticulture</th>
                <th>-</th>
                <th>engineering mechanis</th>
                <th>agronomy</th>
                <th>agronomy</th>
                <th>survey</th>
            </tr>
            <tr> 
                <th bgcolor="green">10-12</th>
                <th>survey</th>
                <th>complex variables</th>
                <th>survey</th>
                <th>web designing</th>
                <th>web designing</th>
                <th>fluid mechanics</th>
            </tr>
            <tr> 
                <th bgcolor="green">12-01</th>
                <td  colspan="6" align="center" bgcolor="skyblue" >LUNCH</td>
            <tr>
                <th bgcolor="green">01-03</th>
                <th>fluid mechanis</th>
                <th>Horticulture</th>
                <th>creative skills</th>
                <th>Theory of machines</th>
                <th>complex variables</th>
                <th>-</th>
            </tr>
            <tr><th bgcolor="green">03-05</th>
                <th>-</th>
                <th>-</th>
                <th>-</th>
                <th>-</th>
                <th>-</th>
                <th>engineering mechanics</th>

            </tr>
       </table><br>
       <table border="5" align="center" width="750px" bgcolor="skyblue">
        <tr align="center" bgcolor="yellow">
            <td>S.NO</td>
            <td>COURSE CODE</td>
            <td>COURSE NAME</td>
        </tr>
        <tr>
            <th>01</th>
            <th>19AG201</th>
            <th>Principles of agronomy</th>
        </tr>
        <tr>
            <th>02</th>
            <th>19AG203</th>
            <th>Principles of Horticultural crops and plant protection</th>
        </tr>
        <tr>
            <th>03</th>
            <th>19AG301</th>
            <th>Fluid mechanics and open channel hydraulis</th>
        </tr>
        <tr>
            <th>04</th>
            <th>19AG304</th>
            <th>Theory of machines</th>
        </tr>
        <tr>
            <th>05</th>
            <th>19AG306</th>
            <th>Surveying and levelling</th>
        </tr>
        <tr>
            <th>06</th>
            <th>19AG310</th>
            <th>Engineering mechanics</th>
        </tr>
        <tr>
            <th>07</th>
            <th>19CS307</th>
            <th>Web designing and internet applications</th>
        </tr>
        <tr>
            <th>08</th>
            <th>19EY702</th>
            <th>Creative skills for communication</th>
         </tr>
         <tr>
            <th>09</th>
            <th>19MA203</th>
            <th>Complex variables and differential equations</th>
         </tr>
       </table>
    </body>
</html>
```

## OUTPUT
<img width="959" alt="table-output1" src="https://github.com/vairalakshmi1811/Ex03/assets/165985148/222a6e17-24cd-45cf-b491-7c0445a4838a">
<img width="959" alt="table-output2" src="https://github.com/vairalakshmi1811/Ex03/assets/165985148/3397e415-355b-4dea-a86c-2cd8c275ec84">


table-output2.png
## RESULT
 Slot time table is created successfully.
