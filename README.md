# Ex03 Time Table
## Date:22-03-2024

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
HTML Program
```
<html>
    <head>
        <title>Saveetha Engineering college</title>
        <link rel="stylesheet" href="fan.css" type="text/css">
    </head>
    <body>
        <center>
            <img src="logo.png" alt="Saveetha">
            <h1>Himavath Time table [212223240053]</h1>
            <table cellpadding="5">

                <tr>
                    <th class="head">Day&time</th>
                    <th class="head">Monday</th>
                    <th class="head">Tuesday</th>
                    <th class="head">Wednesday</th>
                    <th class="head">Thursday</th>
                    <th class="head">Friday</th>
                    <th class="head">Saturday</th>
                </tr>
                <tr>
                    <th class="head">8-10</th>
                    <td class="data">FWA</td>
                    <td class="data">T&A</td>
                    <td class="data">Adv C</td>
                    <td class="data">OS</td>
                    <td class="data" colspan="2">FREE</td>
                </tr>
                <tr>
                    <th class="head">10-12</th>
                    <td class="data">Adv C</td>
                    <td class="data">FREE</td>
                    <td class="data">PQC</td>
                    <td class="data">T&A</td>
                    <td class="data">CS</td>
                    <td class="data">FREE</td>
                </tr>
                <tr>
                    <th class="head">12-1</th>
                    <td class="data" colspan="6">LUNCH BREAK</td>
                </tr>
                <tr>
                    <th class="head">1-3</th>
                    <td class="data">STOCK</td>
                    <td class="data">OS</td>
                    <td class="data"></td>
                    <td class="data">FWA</td>
                    <td class="data">FWA</td>
                    <td class="data"></td>
                </tr>
                <tr>
                    <th class="head">3-5</th>
                    <td class="data">FREE</td>
                    <td class="data">PHY</td>
                    <td class="data">STOCK</td>
                    <td class="data">FREE</td>
                    <td class="data">FREE</td>
                    <td class="data">FREE</td>
                </tr>
            </table>
             <table cellpadding="5">
                <tr>
                    <th>S.No</th>
                    <th>Subject Code</th>
                    <th>Subject Name</th>
                </tr>
                <tr>
                    <tr>
                        <td>1.</td>
                        <td>19AI305</td>
                        <td>Advanced C Programming(Adv C)</td>
                    </tr>
                    <tr>
                        <td>2.</td>
                        <td>19AI414</td>
                        <td>Fundamentals of web Application(FWA)</td>
                    </tr>
                    <tr>
                        <td>3.</td>
                        <td>19CS405</td>
                        <td>Operating System(OS)</td>
                    </tr>
                    <tr>
                        <td>4.</td>
                        <td>19EY702</td>
                        <td>Creative Skill(CS)</td>
                    </tr>
                    <tr>
                        <td>5.</td>
                        <td>19MA219</td>
                        <td>Transfroms and its applications(T&A)</td>
                    </tr>
                    <tr>
                        <td>6.</td>
                        <td>19MS155</td>
                        <td>Stock Market and Company Operations(STOCK)</td>
                    </tr>
                    <tr>
                        <td>7.</td>
                        <td>19PH214</td>
                        <td>Physics for Quantum Computing(PHY)</td>
                    </tr>
                </tr>
            </table>
        </center>
    </body>
</html>
```
CSS program
```
img {
    text-align: center;
    width: 40em;
}
table,th,td {
    border: 2px;
    border-style: solid;
}
.head{
    background-color:  #a355f7;
}
.data{
    text-align: center;
    background-color: #ffa02b;
}
table,img{
    margin: 20px;
}
```
## OUTPUT
![alt text](<Screenshot 2024-03-22 104650.png>)
![alt text](<Screenshot 2024-03-22 104440.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
