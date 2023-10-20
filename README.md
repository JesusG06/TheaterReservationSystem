<h1>Theater Reservation System</h1>


<h2>Description</h2>
Project consists of the backend system for an online ticket reservation system that handles customer demands. The program will allow attendees to select seats and display the current seating arrangement of the small theater. At the end of the program, a report will be generated for the owner indicating how many seats were sold/unsold and how much money was earned. The seating arrangement for each auditorium will be stored in a file. Each line in the file will represent a row in the auditorium. Each auditorium is held in a two-dimensional array. Empty seats in an auditorium are represented by a period (.); reserved seats are represented by the pound symbol (#). Reserved seats in the file are represented by a letter (A, C, or S) to indicate whether that seat is reserved by an adult, child, or senior. This program is still a work in progress as it has some bugs, but the main structure of the program is functional.
<br />
<h3>How the program runs: </h3>
<li>Prompt the user for the filename of the auditorium</li>
<li>The main menu is displayed</li>
<li>The user choses whether they want to reserve seats or exit the program</li>
<li>If the user choses to reserve seats, the auditorium is displayed</li>
<li>Prompt the user for row number</li>
<li>Prompt the user for starting seat</li>
<li>Prompt for number of adult, child, and senior tickets</li>
<li>If selected seats are available, complete the booking and prompt main menu again</li>
<li>If user selected unavailable seats, display best available seats</li>
<li>Prompt user if they want to reserve best available seats</li>
<li>If option is yes, then the booking is complete</li>
<li>Return to main menu</li>
<li>Loop to top of workflow until user selects exit</li>

<h2>Languages and Utilities Used</h2>

- <b>Java</b> 


<h2>Environments Used </h2>

- <b>Eclipse</b> 

<h2>Program walk-through:</h2>

<p align="center">
Input base auditorium: <br/>
<img src="https://i.imgur.com/GvCd4ca.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Input seat reservation:  <br/>
<img src="https://i.imgur.com/ALZmNNU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter number of adult, child, and senior tickets: <br/>
<img src="https://i.imgur.com/KfUCdbW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/mYXpmfk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next auditorium file shows the seats just reserved:  <br/>
<img src="https://i.imgur.com/NHeckKR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once user chooses exit, the total prices are displayed:  <br/>
<img src="https://i.imgur.com/7TG2FKs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
