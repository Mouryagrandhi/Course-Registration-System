# Course-Registration-System


Example
 Sample Input:
 7
 add_student
 S001 Ayon 2 2
 C101 C102
 add_course
 C101 IntroToProgramming 3 30 D 0
 add_course
 C201 DataStructures 3 30 A 1
 C101
 add_course
 C202 Algorithms 3 25 B 1
 C201
 enroll
 S001 C201
 print
 C201
 print
 C203
 Sample Output:
 Enrolled students in C201:
 S001
 Invalid Course C203

 Example
 Sample Input:
 10
 add_student
 S001 Ayon 2 2
 C101 C102
 add_student
 S002 Shankar 2 1
 C101
 add_course
 C101 DataStructures 3 1 A 0
 add_course
 C201 Algorithms 3 2 B 1
 C101
 enroll
 S001 C101
 enroll
 S002 C101
 enroll
 S002 C201
 drop
 S001 C101
 print
 C101
 print
 C201
 Sample Output:
 Enrolled students in C101:
 S002
 Enrolled students in C201:
 S002
