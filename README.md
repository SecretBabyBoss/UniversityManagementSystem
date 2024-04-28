This is a CLONE, and I made this project from Youtube.

UNIVERSITY MANAGEMENT SYSTEM (UMS) is a flagship product of Easy Solution which covers all aspects of Universities, Colleges or Schools. UMS covers every minute aspects of a universities work flow and integrates all processes with user friendly interface. With hundreds of satisfied customers UMS is first choice of several state, governments/semi- government universities and institutions. UMS is an outcome of hard work done by our expert technical team in supervision of several renowned educationists which includes Controller of examination, faculties. UMS is a rare combination of experience and precision. UMS streamline path of information flow in organization by taking care of following departments:
Fee Department
Examination Department
Attendance
Faculty information portal
Student information portal

Technologies Used: Core Java (Swing & AWT) Database Used: MySQL IDE used: Netbeans

Database Queries:
1 - Create database

create database universitymanagementsystem;

2 - Use database you just created

use universitymanagementsystem;

3 - Create login table

create table login(username varchar(25), password varchar(25));

4 - Insert some values in the login table

insert into login values('admin', '12345');

5 - Create student table

create table student(name varchar(40), fname varchar(40), rollno varchar(20), dob varchar(40), address varchar(100), phone varchar(20), email varchar(40), class_x varchar(20), class_xii varchar(20), aadhar varchar(20), course varchar(40), branch varchar(40));

6 - Create teacher table

create table teacher(name varchar(40), fname varchar(40), empId varchar(20), dob varchar(40), address varchar(100), phone varchar(20), email varchar(40), class_x varchar(20), class_xii varchar(20), aadhar varchar(20), education varchar(40), department varchar(40));

7 - Create student leave table

create table studentleave(rollno varchar(20), date varchar(50), duration varchar(20));

8 - Create teacher leave table

create table teacherleave(empId varchar(20), date varchar(50), duration varchar(20));

9 - Create table to store subjects

create table subject(rollno varchar(20), semester varchar(20), subject1 varchar(50), subject2 varchar(50), subject3 varchar(50), subject4 varchar(50), subject5 varchar(50));

10 - Create table to store marks

create table marks(rollno varchar(20), semester varchar(20), marks1 varchar(50), marks2 varchar(50), marks3 varchar(50), marks4 varchar(50), marks5 varchar(50));

11 - Create table for fee structure

create table fee(course varchar(20), semester1 varchar(20), semester2 varchar(20), semester3 varchar(20), semester4 varchar(20), semester5 varchar(20), semester6 varchar(20), semester7 varchar(20), semester8 varchar(20));

12 - Insert some values in the table

insert into fee values("BTech", "48000", "43000","43000","43000","43000","43000","43000","43000");

insert into fee values("Bsc", "40000", "35000","35000","35000","35000","35000","","");

insert into fee values("BCA", "35000", "34000","34000","34000","34000","34000","","");

insert into fee values("MTech", "65000", "60000","60000","60000","","","","");

insert into fee values("MSc", "47500", "45000","45000","45000","","","","");

insert into fee values("MCA", "43000", "42000","42000","49000","","","","");

insert into fee values("Bcom", "22000", "20000","20000","20000","20000","20000","","");

insert into fee values("Mcom", "36000", "30000","30000","30000","","","","");

13 - Create table to store student fee details

create table collegefee(rollno varchar(20), course varchar(20), branch varchar(20), semester varchar(20), total varchar(20));


Added JAR files in Libraries: mysql-connector-j-8.3.0 rs2xml jcalendar-1.4
