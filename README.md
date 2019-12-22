# hostel-management
This is a C project which is a NON-GUI based hostel management system.<br>
This system lets you handle the database of students of a institute.<br>
You can perform following operations with this project.<br> 
-> add student information.<br>
-> delete student information.<br>
-> search student information (only initials of name irrespective of case will do!).<br>
-> update student information.<br>
-> note the students which are inside or outside the hostel.<br>
-> display batchwise, genderwise and all student information.<br>

Whole data is stored in form of linked-list as well as text-file. <br>
When this program is in use the linked list will do.<br>
When you call functions and add edit some thing it will be added to linked-list and a new updated text-file will be formed.<br>
When user closes the program and again starts it the text-file will be used in making a new linked-list.<br>


TO RUN THE PROGRAM JUST DOWNLOAD IT GO INSIDE THE DIRECTORY WHICH CONTAINS THE HOSTEL-MANAGEMENT-SYSTEM IN TERMINAL AND WRITE FOLLOWING COMMANDS-
>TO UNZIP THE FILE 
```bash
$ tar -zxvf Hostel_Management_System.tar.gz
```
> GO TO THE UNZIPPED DIRECTORY AND RUN FOLLOWING COMMANDS IN TERMINAL TO COMPILE AND EXECUTE
```bash
$ make all
$ ./main
```
