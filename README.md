# Ex03 Time Table
## Date : 01/04/2024

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
### Html 
```html
<html>
    <head>
        <title>
            MY SLOT
        </title>
        <link rel="stylesheet" href="my.css">
    </head>
    <body class="bg">
        <center>
            <img src="logo.png" with="100px", height="100px"><br><br><br>
            <h2 class="name">SLOT TIME TABLE MAHARA JOTHISH E (212221040094)</h2>
            <table border="6" class="table1">
                <tr class="dt">
                    <th>Day/Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thuresday</th>
                    <th>Friday</th>
                </tr>
                <tr class="ta">
                    <td class="dt">8-10</td>
                    <td>FUN WEB</td>
                    <td class="fs">ETH</td>
                    <td>COM DESIGN</td>
                    <td class="fs">FREE SLOT</td>
                    <td>DPSD</td>
                </tr>
                <tr class="ta">
                    <td class="dt">10-12</td>
                    <td class="fs">COM DESIGN</td>
                    <td>SNLT</td>
                    <td>GAME PRO</td>
                    <td>FREE SLOT</td>
                    <td>GAME PRO</td>
                </tr>
                <tr class="ta">
                    <td class="dt">12-01</td>
                    <td colspan="5" style="color: rgb(12, 131, 12)">LUNCH BREAK</td>
                </tr>
                <tr class="ta">
                    <td class="dt">01-03</td>
                    <td>ALG & NUM</td>
                    <td>CNS</td>
                    <td class="fs">DPSD</td>
                    <td>FUN WEB</td>
                    <td>FUN WEB</td>
                </tr>
                <tr class="ta">
                    <td class="dt">03-05</td>
                    <td class="fs">DPSD</td>
                    <td class="fs">FREE SLOT</td>
                    <td>FREE SLOT</td>
                    <td class="fs">SS</td>
                    <td class="fs">FREE SLOT</td>
                </tr>
            </table>
            <br> <br> 
            <table border="6" class="table2 ta">
                <tr>
                    <th>S. No.</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <td>1.</td>
                    <td>19AI414</td>
                    <td><b>Fundamental of Web Application Development [FUN WEB]</b></td>
                </tr>
                <tr>
                    <td>2.</td>
                    <td>19CS409</td>
                    <td><b>COMPILER DESIGN [COM DESIGN]</b></td>
                </tr>
                <tr>
                    <td>3.</td>
                    <td>19MA212</td>
                    <td><b>ALGEBRA AND NUMBER THEORY [ALG & NUM]</b></td>
                </tr>
                <tr>
                    <td>4.</td>
                    <td>19EC303</td>
                    <td><b>DIGITAL PRINCIPALS AND SYSTEM DESIGN [DPSD]</b></td>
                </tr>
                <tr>
                    <td>5.</td>
                    <td>19CS417</td>
                    <td><b>ETHICAL HACKING [ETH]</b></td>
                </tr>
                <tr>
                    <td>6.</td>
                    <td>19EY703</td>
                    <td><b>SYSTEM OF NUMERICAL AND LOGICAL TERMINOLOGIES [SNLT]</b></td>
                </tr>
                <tr>
                    <td>7.</td>
                    <td>19CS412</td>
                    <td><b>CRYPTOGRAPHY AND NETWORK SECURITY [CNS]</b></td>
                </tr>
                <tr>
                    <td>8.</td>
                    <td>19EY701</td>
                    <td><b>SOFT SKILLS [SS]</b></td>
                </tr>
                <tr>
                    <td>9.</td>
                    <td>19AI513</td>
                    <td><b>GAME PROGRAMMING [GAME PRO]</b></td>
                </tr>
            </table>
        </center>
    </body>
</html>
```

### External css
```css
.name{
    font-family: 'Times New Roman', Times, serif;
    background-color: red;
}
.bg{
    background-color: rgb(101, 174, 160);
}
.table1{
    background-color: rgb(172, 177, 74);
}
.table2{
    background-color: rgb(200, 149, 149);
}    
.dt{
    background-color: rgb(166, 224, 232);
}
b{ 
    color:rgb(36, 99, 105); 
}
.ta{
    text-align: center;
}
```

## OUTPUT
![alt text](<Screenshot (15).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
