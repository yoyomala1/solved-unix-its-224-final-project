Download Link: https://assignmentchef.com/product/solved-unix-its-224-final-project
<br>
<strong>Directions:</strong> Complete the following projects. As in all assignments please copy output into the text file you submit to your instructor. In order to verify the completion of all projects your instructor will view the directory and files you have created in your “exam” directory. If you completed the exam using a virtual machine, please cat the files and copy and paste them to the bottom of your submitted document.  Also include a copy and paste of the exam directory.

.<strong>Project Objectives:</strong>

<strong>.</strong>Make a directory (ch 2)

Working with delimited files (use vi) (delimited files – ch 2, vi – ch 3)

Change file permissions (ch 2)

Copy files (ch 4)

Translate (ch 5)

Paste (redirect output) (ch 4)

Sort (ch 4)

Cut (redirect output) (ch 4)

Sed (ch 5) (stream editor)

Define a function (ch 7)

Create a menu driven program

<ol>

 <li>Make a directory called exam in your home directory, change to that directory. (2 pts)</li>

</ol>

In problems 2 (a-d) and 3 (a-b) you will create several files that correspond to courses you take at Helena College. Question 2 focuses on Fall courses. Question 3 focuses on Spring courses.

2a. Develop a list of your 3 favorite “General Education” courses (name the file <strong>“gened-fall-courses</strong>). Include rubric and course number (ex. “WRIT101”), title of course, semester class is offered (enter “fall” for all classes). Delimit the fields using a colon (“:”). <strong>(2 pts)</strong>

Example. <strong><u>BIOL220:Microbiology Lecture:Fall</u></strong>

2b. Create a “Gen Ed” course file that includes information about the classes listed in “gened-fall-courses” (previous question). Include building (DON), room (122), and instructor of corresponding classes. Name this file <strong>“gened-fall-courses-info”</strong> Make sure the list in this file matches the order of the gened-fall-courses file. Delimit the fields using a colon (“:”).<strong>(2 pts)</strong>

Example. <strong><u>DON:131:Johnson</u></strong>

2c. Develop a list of 3 Fall “Computer Technology” courses (name the file <strong>“ct-fall-courses”</strong>). <strong>One course must be a CSCI course!!!</strong>  Include rubric and course number (ex. “CT115”), title of course, and semester class is offered (enter “fall” for all classes). Delimit the fields using a colon (“:”). <strong>(2 pts)</strong>

Example. <strong><u>CT115:Web Pages:Fall</u></strong>

2d. Create a “CT” course file that includes the building (DON), room (122), and instructor of the corresponding classes in the “Computer-Technology” ct-fall-courses file (name this file <strong>“ct-fall-courses-info”</strong>). Delimit the fields using a colon (“:”). <strong>(2 pts)</strong>

Example.<strong> DON:122:Scott</strong>

NOTE! Make sure the GenEd and CT files contain the same fields.

3a. Create a file that contains 2 Spring CT classes (name the file <strong>“ct-spring-courses”. </strong>Delimit the fields using a colon (“:”). <strong>(2 pts)</strong>

Example. <strong><u>CSCI100:Intro to Programming:Spring</u></strong>

3b. Create a file that includes the building (DON), room (122), and instructor of corresponding CT Spring classes listed in ct-spring-courses. Name the new file <strong>“ct-spring-courses-info”</strong>. Delimit the fields using a colon (“:”). <strong>(2 pts)</strong>

Example. <strong>DON:122:Scott </strong>

4a. Create one complete Fall Gen Ed class list (course list AND course info). Title this file <strong>“gened-fall-class-list”</strong>. <strong>(2 pts) </strong>

Your output should look something like this.

&gt;cat gened-fall-class-list

BIOL220:Microbiology Lecture:Fall:DON:131:Johnson

4b. Create one complete CT class list (course list AND course info). Title this file <strong>“ct-fall-class-list”.</strong> <strong>(2 pts).</strong>

Your output should look something like this.

&gt;cat ct-fall-class-list

CT115:Web Pages:Fall:DON:121:Lytinnen

4c. Create a file that includes ALL Gen Ed (first) and CT courses (second). Title it “<strong>fall-courses”.</strong> <strong>(2 pts)</strong>

4d. Create one complete Spring class list from “ct-spring-courses” and “ct-spring-courses-info”. Name it <strong>“spring-courses”</strong>. <strong>(2 pts).</strong>

4e. Create a master class list combining all fall (first) and spring (second) classes. Name the file <strong>“ay-courses”</strong> (AY stands for Academic Year) <strong>(2 pts)</strong>

5a. Create a file named “<strong>instructors”</strong> that contains Fall and Spring courses listing Course Title, Instructor, and semester. <strong>(2 pts)</strong>

Example. <strong><u>Microbiology Lecture:Fall:Johnson</u></strong>

5b. Alphabetize this file by Name of Course and save it as <strong>“sorted-course-name”.</strong> <strong>(2 pts)</strong>

Due to the statewide common course number initiative all “CSCI” courses need to be renamed to <strong>“CS”</strong>.

6a. Find all “CSCI” courses and retitle them to “CS”. Call the new file <strong>“ay-courses-cs-updated”. (2 pts)</strong>

6c. Make the following files easier to read. Remove the delimiter and save each of the updated files with a “.txt” extension. <strong>(4 pts)</strong>

fall-courses

spring-courses

ay-courses-cs-updated

sorted-course-name




<ol start="7">

 <li>Create a menu driven program (named <strong>“coursemenu”</strong>) that uses the TXT tiles you created in 6c and will view: <strong>(12 pts)</strong></li>

</ol>

1 – Fall Courses

2 – Spring Courses

3 -A master class list (contains ALL info in ALL classes)

4 – A class list containing Course Title, Instructor, and semester




<ol start="8">

 <li>Create a function with a file name of <strong>“classlist”</strong>that will run the “coursemenu” program when you type <strong>“classes”</strong>at the command prompt. <strong>(4 pts)</strong></li>

</ol>

After completing each step, before submitting, If you completed the exam using a virtual machine on your own computer, please cat each file used in the exam and copy and paste them into the document.  Also copy and paste the directory listing of the exam directory.


