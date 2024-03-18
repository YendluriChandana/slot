# Ex03 Time Table
## Date:18/03/2024

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
        <title>My Time Table</title>
<caption>SLOT TIME TABLE-YENDLURI CHANDANA(212223100063)</caption>
<body bgcolor="lavender" align="center">
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<table border="6" align="center">
<tr>
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">wednesday</th>
<th bgcolor="pink">thursday</th>
<th bgcolor="pink">friday</th>
<th bgcolor="pink">saturday</th>
</tr>
<tr>
<th bgcolor="pink">8-10</th>
<th bgcolor="orange">Chemistry</th>
<th bgcolor="orange">Free Slot</th>
<th bgcolor="orange">FWAD</th>
<th bgcolor="orange">DIP</th>
<th bgcolor="orange">DIP</th>
<th bgcolor="orange">Probability</th>
</tr>
<tr>
<th bgcolor="pink">10-12</th>
<th bgcolor="orange">PMC</th>
<th bgcolor="orange">FWAD</th>
<th bgcolor="orange">Free Slot</th>
<th bgcolor="orange">Probability</th>
<th bgcolor="orange">Creative Skills</th>
<th bgcolor="orange">Free Slot</th>
</tr>
<tr>
<th bgcolor="pink">12-1</th>
<th  bgcolor="orange" colspan="6">L U N C H</th>
</tr>
<tr>
<th bgcolor="pink">1-3</th>
<th bgcolor="orange">FWAD</th>
<th bgcolor="orange">Physics</th>
<th bgcolor="orange">Physics</th>
<th bgcolor="orange">EDM</th>
<th bgcolor="orange">PMC</th>
<th bgcolor="orange">Chemistry</th>
</tr>
<tr>
<th bgcolor="pink">3-5</th>
<th bgcolor="orange">Advanced C programming</th>
<th bgcolor="orange">EDM</th>
<th bgcolor="orange">Advanced C programming</th>
<th  bgcolor="orange" colspan="3">F R E E S L O T</th>
</tr>
</table>
<table border="9" align="center">
<tr>
<th>S.NO.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<th>1</th>
<th>19AI414</th>
<th>Fundemnetals of web application Development(FWAD)</th>
</tr>
<tr>
<th>2</th>
<th>19MA222</th>
<th>Probability</th>
</tr>
<tr>
<th>3</th>
<th>19EY702</th>
<th>Creative Skills</th>
</tr>
<tr>
<th>4</th>
<th>19EE309</th>
<th>Programming Microcontrollers(PMC)</th>
</tr>
<tr>
<th>5</th>
<th>19CY205</th>
<th>Principles of Chemistry in Engineering</th>
</tr>
<tr>
<th>6</th>
<th>19AI406</th>
<th>Digital Image Processing Technique(DIPT)</th>
</tr>
<tr>
<th>7</th>
<th>19AI305</th>
<th>Advnced C Programming</th>
</tr>
<tr>
<th>8</th>
<th>19AI302</th>
<th>Rngineering Design and Modelling(EDM)</th>
</tr>
<tr>
<th>9</th>
<th>19PH214</th>
<th>Physics for Quantum Computing</th>
</tr>

</table>
    </head>
</body>
</html>
```




## OUTPUT
![alt text](<Screenshot 2024-03-18 104518.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
