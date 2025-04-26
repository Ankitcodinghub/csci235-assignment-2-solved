# csci235-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSCI235 Assignment 2 Solved](https://www.ankitcodinghub.com/product/csci235-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;49372&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI235  Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
The tasks of this assignment cover <strong>stored PL/SQL procedure, function, and trigger</strong>. The assignment covers the topics discussed in lecture 7, 8, and 9.

<strong>Assignment Specification: </strong>

<strong>&nbsp;</strong>Preliminary actions

<strong>&nbsp;</strong>

Download SQL script dbCreateTruck-2020SP20.sql from Moodle. Execute the script to create and to load a sample database for trips made by drivers. The database contains information about the employees working for a transportation company, drivers employed by the company, trucks owned by the company, trips made by the drivers and trucks, and all legs of each trip. It is strongly recommended to discover a conceptual schema (UML diagram) of the database. However, there will be no mark awarded for producing the conceptual schema.

<strong>&nbsp;</strong>

<h1>Task 1 (7.0 marks) Stored PL/SQL Procedure</h1>
<strong>&nbsp;</strong>

Implement a stored PL/SQL procedure that insert into a database full information about an employee i.e., the values of the following attributes E#, NAME, DOB, ADDRESS, HIREDATE, L#, STATUS, EXPERIENCE (only for mechanics).

&nbsp;

Your procedure should enforce a logical consistency constraint such that “the sets of drivers and mechanics must be disjoint”. It means that it is not allowed to have in the tables MECHANIC and DRIVER the rows with the same employee number (E#) and/or the same driving license number (L#).

&nbsp;

Execute your procedure twice. The first execution should insert full information about a new employee. The second execution should fail due to the violation of logical consistency constraint given above.

&nbsp;

&nbsp;

<h1>Deliverables</h1>
<strong>&nbsp;</strong>

Hand in your solution1.lst in pdf format. Your report MUST have no errors and the report MUST list all SQL statements processed. All SQL statements of the script must be executed with SET ECHO ON, SET FEEEDBACK ON and SET SERVEROUTPUT ON options of SQL*Plus. It is a good idea to set the options at the beginning of the script. The script must be implemented with SQL*Plus. Oracle database server used for the testing and the final execution of the script is up to you. <strong>The printouts that do not satisfy the requirements listed above will score NO MARKS!</strong>

<strong>&nbsp;</strong>

&nbsp;

&nbsp;

&nbsp;

<h1>Task 2 (5.0 marks) Stored PL/SQL Trigger</h1>
&nbsp;

Implement <strong>a row trigger</strong> that enforces the following consistency constraint.

&nbsp;

A column totalTripMade in the relational table DRIVER is currently does not contain any value. Create a row trigger that automatically updates the values in the column (totalTripMade) when a new trip made by a driver is inserted into the relational table TRIP. Your trigger, once activated, will compute the total number of trips made by the driver and update the totalTripMade column in the relational table DRIVER. NOTE: You do not need to consider any other cases that may change the value in the column totalTripMade; that is, NO NEED to consider delete and update cases.

&nbsp;

When ready, process the SQL script solution2.sql and record the results of processing in a file solution2.lst.

&nbsp;

<h1>Deliverables</h1>
<strong>&nbsp;</strong>

Hand in your solution2.lst in pdf format. Your report MUST have no errors and the report MUST list all SQL statements processed. All SQL statements of the script must be executed with SET ECHO ON, SET FEEEDBACK ON and SET SERVEROUTPUT ON options of SQL*Plus. It is a good idea to set the options at the beginning of the script. The script must be implemented with SQL*Plus. Oracle database server used for the testing and the final execution of the script is up to you. <strong>The printouts that do not satisfy the requirements listed above will score NO MARKS!</strong>

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1>Task 3 (3.0 marks) Stored PL/SQL function</h1>
&nbsp;

Implement a stored PL/SQL function LONGTRIP(DLNUM) that finds the length (the total number of legs) of the longest trip performed by a driver identified by a driving license number (L# attribute in table DRIVER and parameter DLNUM parameter in the function). Remember to include or consider the drivers that performed no trips; that is to say, do not ignore drivers that do not perform any trip. If a driver has not performed any trip, then output the longest trip a 0.

&nbsp;

Use a stored function LONGTRIP in SELECT statement to list the names of all drivers together with the length of the longest trip performed by each driver.

&nbsp;

&nbsp;

<h1>Deliverables</h1>
<strong>&nbsp;</strong>

Hand in your solution3.lst in pdf format. Your report MUST have no errors and the report MUST list all SQL statements processed. All SQL statements of the script must be executed with SET ECHO ON, SET FEEEDBACK ON and SET SERVEROUTPUT ON options of SQL*Plus. It is a good idea to set the options at the beginning of the script. The script must be implemented with SQL*Plus. Oracle database server used for the testing and the final execution of the script is up to you. <strong>The printouts that do not satisfy the requirements listed above will score NO MARKS!</strong>

&nbsp;

&nbsp;

<h1>Submissions</h1>
<strong>&nbsp;</strong>

This assignment is due by 9:00 pm (2100 hours) Sunday, 10 May 2020, Singapore time.

&nbsp;

Submit the files <strong>solution1.pdf</strong>, <strong>solution2.pdf, solution3.pdf </strong>through Moodle in the following way:

1) Zip all the files (Solution1.pdf, solution2.pdf and solution3.pdf into one zipped folder. Name your zipped file as YourName-A3)

<h1>2)&nbsp;&nbsp;&nbsp;&nbsp; Access Moodle at <a href="http://moodle.uowplatform.edu.au/">http://moodle.uowplatform.edu.au/</a></h1>
<ul>
<li>To login use a Login link located in the right upper corner the Web page or in the middle of the bottom of the Web page</li>
<li>When successfully logged in, select a site CSCI235 (SP220) Database Systems</li>
<li>Scroll down to a section Submissions of Assignments 6) Click at Submit your Assignment 1 here link.</li>
<li>Click at a button Add Submission</li>
<li>Move the zipped file created in Step 1 above into an area provided in Moodle. You can drag and drop files here to add them. You can also use a link <em>Add… </em></li>
<li>Click at a button Save changes,</li>
<li>Click at check box to confirm authorship of a submission,</li>
<li>When you are satisfied, remember to click at a button Submit assignment.</li>
</ul>
&nbsp;
