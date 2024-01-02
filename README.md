# Ex-05-Timetable

# AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html>
 
<body>
    <IMG src="C:\Users\admin\Desktop\GIT WEB\ODD2023-WT-Ex-03-Timetable\logo.png"
	height="100" width="1000" align="center" border="7">

    <h1> TIME TABLE </h1 >
       
    <table border="10" cellspacing="0" align="center" >
        <!--<caption>Timetable</caption>-->
        <tr bgcolor="#728FCE">
            <th align= "center"  colspan="1"  height="40" width="80"><b>NAME</b></th>
            <th align= "center"  colspan="2"  bgcolor="LightSteelBlue" height="40" width="80"><b>Sunil Kumar T</b></th>
            <th align= "center"  colspan="1"  height="40" width="80"><b>REF.NO</b></th>
            <th align= "center"  colspan="2"  bgcolor="LightSteelBlue" height="40" width="80"><b>23001650</b></th>
        </tr>
        <tr bgcolor="#A0D6B4">
            <th align= "center"  colspan="6" height="40" width="50"> <b>SEMESTER-1 ODD-JUNIOR(2023-2024)</b></th>
        </tr>
        <tr>
            <td align="center" bgcolor="LightBlue" height="100"
                width="200"><br>
                <b>Day/Period</b></br>
            </td>
            <td align="center" bgcolor="LightSteelBlue" height="50"
                width="200">
                <b>I<br>8:00-10:00</b>
            </td>
            <td align="center" bgcolor="LightSteelBlue" height="50"
                width="200">
                <b>II<br>10:00-12:00</b>
            </td>
            <td align="center" bgcolor="LightSteelBlue" height="50"
                width="200">
                <b>12:00-1:00</b>
            </td>
            <td align="center" bgcolor="LightSteelBlue" height="50"
                width="200">
                <b>III<br>1:00-3:00</b>
            </td>
            <td align="center" bgcolor="LightSteelBlue" height="50"
                width=200">
                <b>IV<br>3:00-5:00</b>
            </td>
        </tr>
        <tr>
            <td align="center" bgcolor="LightSteelBlue" height="50">
                <b>Monday</b></td>
            <td align="center" height="50">---</td>
            <td align="center" height="50">19AI304 Fundamentals Of C Programming</td>
            <td rowspan="5" align="center" height="50">
                <h1>L<br>U<br>N<br>C<br>H</h1>
            </td>
            <td colspan="1" align="center"
                height="50">19AI303 Engineering Mechanics And Product Development</td>
            <td align="center" height="50">---</td>
        </tr>
        <tr>
            <td align="center" bgcolor="LightSteelBlue" height="50">
                <b>Tuesday</b>
            </td>
            <td colspan="1" align="center"
                height="50">---
            </td>
            <td align="center" height="50">19AI304 Fundamentals Of C Programming</td>
            <td align="center" height="50">19CY205 Principles of chemistry</td>
            <td align="center" height="50">---</td>
            
            
        </tr>
        <tr>
            <td align="center" bgcolor="LightSteelBlue" height="50">
                <b>Wednesday</b>
            </td>
            <td align="center" height="50">19AI303 Engineering Mechanics And Product Development</td>
            <td align="center" height="50">19AI414 Fundamentals Of Web Application</td>
            <td align="center" height="50">---</td>
            <td align="center" height="50">---</td>
        </tr>
        <tr>
            <td align="center" bgcolor="LightSteelBlue" height="50">
                <b>Thursday</b>
            </td>
            <td align="center" height="50">19AI414 Fundamentals Of Web Application</td>
            <td align="center" height="50">19MA222 Probability And Queuing Models</td>
            <td align="center" height="50">19ENY701 Soft Skils</td>
            <td  align="center"height="50">---</td>
        </tr>
        <tr>
            <td align="center" bgcolor="LightSteelBlue" height="50">
                <b>Friday</b>
            </td>
            <td align="center"height="50">----</td>
            <td align="center" height="50">19AI414 Web Application</td>
            <td align="center" height="50">19CY205 Principles of Chemistry</td>
            <td align="center" height="50">19MA222 Proabibility Of Queuing Models</td>
        </tr>
    </table>
</body>
 
</html>
```
# OUPUT
![output](/Screenshot%202023-11-15%20044331.png)
