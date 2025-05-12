# Ex03 Time Table
## Date:15.03.2025

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
   <title> TIME TABLE </title>
   <body>
   <center>
   <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfVHM7lQHBY3fMmzXE1m0bYnMg3dsccFDu2g&s"height="150px"width="500px">

<br>
<table border="6" bgcolor="CYAN" cellspacing="10" cellpadding="10">
<caption> SLOT TIME TABLE -G.RESHMA (24003213) </caption>
<br>

<tr bgcolor="YELLOW">
     <th> Day/Time </th>
     <th> Monday </th>
     <th> Tuesday </th>
     <th> Wednesday </th>
     <th> Thursday </th>
     <th> Friday </th> 
</tr>

<tr align="center">
   <th bgcolor="PINK"> 8-10 </th>
   <td> FREE SLOT</td>
   <td> EVS</td>
   <td> FREE SLOT</td>
   <td> C program </td>
   <td> digital electronics</td>
</tr>

<tr align="center">
    <th bgcolor="PINK"> 10-12 </th>
    <td> English</td>
    <td> FREE SLOT</td>
    <td> digital electronics</td>
    <td> EMPD</td>
    <td> FWAD</td>
</tr>

<tr align ="center">
    <th bgcolor="PINK"> 12-1 </th>
    <td colspan="6" align="center"> LUNCH

 <tr align="center">
    <th bgcolor="PINK"> 1-3 </th>
    <td> chemistry</td>
    <td>C program</td>
    <td> Mentor meet</td>
    <td> CDS</td>
    <td> EMPD</td>
</tr>
<tr align="center">
    <th bgcolor="PINK"> 3-5 </th>
    <td> FREE SLOT </td>
    <td> English</td>
    <td>FWAD </td>
    <td>chemistry</td>
    <td>EVS</td>
</tr>

</tr>

</table>
<br>
<table border="7" cellspacing="10" cellpadding="10">
<tr align="center">
<th> S.NO. </th>
<th> Subject Code</th>
<th> Subject Name </th>
</tr>

<tr align="center">
<td> 1. </td>
<td> 19AI414 </td>
<td> Fundamentals of Web Applicaton Development(FWAD) </td>
</tr>

<tr align="center">
<td> 2. </td>
<td> 19AI304</td>
<td> C PROGRAM </td>
</tr>

<tr align="center">
<td> 3. </td>
<td> 19EY308</td>
<td> CD</td>
</tr>

<tr align="center">
<td> 4. </td>
<td> 19EN101</td>
<td> English </td>
</tr>

<tr align="center">
<td> 5. </td>
<td> 19AI303</td>
<td> EMPD</td>
</tr>

<tr align="center">
<td> 6. </td>
<td> 19CS305</td>
<td>DIGITAL ELECTRONICS</td>
</tr>z

<tr align="center">
    <td> 7. </td>
    <td> 19cy205</td>
    <td>CHEMISTRY</td>
    </tr>

    <tr align="center">
        <td> 8. </td>
        <td> SH4801</td>
        <td>EVS</td>
        </tr>
```
## OUTPUT
![Screenshot (27)](https://github.com/user-attachments/assets/054c2f74-e397-4d11-b78b-7c4e08eb8239)
![Screenshot (29)](https://github.com/user-attachments/assets/3dcde4cd-02f3-48dc-ae89-669e623f0fc2)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
