# Software Requirements Specification for Website of Department of ICT

## Introduction

The name of the project is Website of ICT department. It is an internet-based application
which aim to provide information to all the students, admins & teachers of ICT department
and as well as outsider for some extent. This system can be used as a information
management system for the department of ICT.
Admin, student & teacher can create account using log in function. They can upload or
change information as per their authority to do so.
The front-end will be HTML pages with Java Script for client side as well as Node & React.
All this will interact with a database, which will be MongoDB.
### 1.1 Purpose
The purpose of this document is to present a detailed description of the Website of ICT
department. IT will explain the purpose and features of this system like the interface of this
system, what it will do, the constrains under which it must operate and how the system will
react to external stimuli. This document is intended for both the client and developer of the
system.
### 1.2 Intended Audience and Reading Suggestions
There are different types of intended audience for this document, such as developer, tester,
clients and most importantly for the users. We have divided the rest of the document in
different subsections. We suggest you begin with understanding the definitions, acronyms
and abbreviation. Then sequentially go through the contents.
### 1.3 Project Scope
This software system will be a website for the department of ICT. This software will ensure
to maximize the throughput of the administrative, academic and overall productivity by
providing tools to assist the ICT department. This system will be easy to use and understand 
while providing with users need. It is a user-friendly portal to interact, manage and access
information.

## Overall Description

### 2.1 Product Perspective
The product will be a standalone application and may be run on multiple systems within an
internet connection. The product will require a keyboard, mouse and monitor to interface
with the user. The minimum hardware requirements for the product are specified in this
document.
### 2.2 Product Features
Some key features of the product will be, login portal, dashboard, profile management,
research/thesis paper. Profiling management includes profile of ICT departments’ students,
teachers & admins. From the dashboard everyone will be able to see notices like, exam schedule, events, club activities etc. Research and thesis papers will also be accessible from
the system. But to access these papers you will need to create a profile first.
### 2.3 User Classes and Characteristics
The target audience for the system is the ICT departments’ Administrators, students, faculty,
external, staff(technical/non-technical). The user for this system are:
 Administrator: The super user of the system. Mainly focuses on administrative and
academic related issues.
 Student: A user with limited access right.
 Faculty: A user with academic access right.
 Staff: A user with technical access rights.
 External user: User of other departments with limited access right.
### 2.4 Operating Environment
This system can be run on any web browser with stable internet connection. As it is a webbased
system, it doesn’t have any constrain on the operating system that the user is using.
And it can be run on any modern devices like, mobile phone, desktop, laptop, pad.
### 2.5 Design and Implementation Constraints
The current constrains on the project are related to the provision of these resources:
 As we are bound on time, we may not be able to fully develop the system with all the
features and functions.
 Our team has only hand full of developers, it will be hard for us to develop the
software as we want.
 To test, host and run the system we will need money which is also a constrain.
 The web portal will be constrained by the capacity of the database.
 The user cannot change their details without getting permission from the admin.
 The internet connection is also a constraint for the application. Since the application
cannot be run without the internet.
### 2.6 User Documentation
User can access the system with a stable internet connection and a web browser. User will
have to type the URL for the system, and they will be presented with the system.
### 2.7 Assumptions and Dependencies
Several factors that may affect the requirements specified in the SRS include:
 It is assumed that every user will have a profile in the system according to their access
limit.
 The complaints and the feedback given by the students and other members of the
department are assumed to be reliable.
 The schedule for the exam, registration window will be open for only few days
only after these pages will be inactive until next exam or registration period.
 In the case that the project is delayed, there are some requirements that could be
transferred to the next versio

## System Features

### 3.1 Login into Portal
In this feature, the user can login into the system by providing their respective ID and
password to the portal which are unique and provided by the university.
Purpose: to login into the portal and get benefitted by the features and information.
### 3.2 Change Password
Change the password once you have logged into the system. If the user forgets their
password, a security question will be asked. In the event that he/she is unable to do so, the
user must submit a formal request to the administrator for a password change together with
the required documentation. Alternatively, an OTP will be provided to his/her phone number.
Purpose: Login without any problem, can choose password whenever user wants to do.
Software Requirements Specification for Website of Department of ICT Page 5
### 3.3 View/ change profile details and other confidential information
The user can access or modify parts of his or her personal information, including email id,
contact information, and address information. The profile will include the student's name,
age, permanent address, parent's name, address, and contact information, year, semester,
assigned room, hostel name and number, etc.
Purpose: To maintain his or her current profile status
### 3.4 Help / Manual
Can obtain assistance using the help option, which provides information on the system's
various features. In addition, a copy of the user manual will be sent in this area.
Purpose: In the incidence of confusion, the user can easily resolve the issue and gain a more
thorough understanding of the system's functionality
### 3.5 Schedules
Users can browse timetables and schedules for classes, examinations, seminars, and buses.
Purpose: By obtaining this information, users will be able to organize their activities to make the
best use of their time.
### 3.6 Notices and Aannouncements
The user can browse news and announcements from several departments on the homepage.
Purpose: The user receives department updates and is aware of department and university
events.
### 3.7 Academics
This module on dashboard contains all the information about the academics such as Faculty
information, all the programs, academic calendar.
Purpose: After entering this module, user will have access to all academic content.
3.8 Application of approval
The user can request for different types of approvals like certificates after graduation, vehicle
pass allowance, allowance for sitting in the exam etc. After filling the given format, the
Software Requirements Specification for Website of Department of ICT Page 6
request will be sent to the administrative department for verification of request. After the
verification, the user can get the response.
Purpose: This feature makes the process more convenient, swift, and less laborious.
### 3.9 Feedback
By selecting the domain: Academics, Administration, Hostel, Mess, Transportation, one can
file a complaint or provide feedback via text form. The department head will respond
appropriately.
Purpose: Informing authority having less effort.
### 3.10 Result
By logging into the site, students can view their results from previous semesters, generate a
PDF file, and print it. Users are unable to view the results of other students. Also, they will be
notified by pop-up notification
Purpose: The user can track his or her academic performance conveniently.
### 3.11 Research and Publications
Student and faculty can access the contents of this segment by logging in the portal. Rest of
the audience can only view just the title of research and publications and other documents.
Also, students and faculty members can archive any thesis.
Purpose: to be acknowledged about the previous and running works regarding paper
publications
### 3.12 Club Activities
All of the department's clubs and its previous events, such as festivals and competitions, will
be listed here. In addition, the details of the competition winner will be listed here.
Purpose: Outsiders and new audiences, for example freshers, will be familiar with the
activities of each club

## External Interface Requirements

### 4.1 User Interfaces
When a user accesses the web portal for the very first time, the 'Home Page' of the portal
should display a button that allows them to log in. If a user has not yet registered, they should
be able to do so on the page where they log in if they are using this feature. In addition to
that, there will be a remember me button. Users will be able to view the most recent notices
posted by departments, as well as achievements, club activities, and other news and events,
on the homepage of the website. We are going to add various features to the navigation bar,
such as information about the department, academic information such as graduateundergraduate
programs, semester results, enrollment, course curriculum, and other similar
information. The user will also be able to view the members of the administrative staff and
faculty. Users will be able to view a variety of study topics and the associated works when
they navigate to the research section of the website.
### 4.2 Hardware Interfaces
Client End:
Minimum RAM of 512MB or above
Hard disk of 20GB or above
Server End:
Minimum RAM of 512MB or above
Hard disk of 20GB or above
### 4.3 Software Interfaces
Compatible with any renowned browsers; for example, Google Chrome, Mozilla Firefox,
Brave, Microsoft edge etc.
Need text editor, HTML, CSS, JavaScript, bootstrap, react.js, firebase.
### 4.4 Communications Interfaces
Internet will be used to facilitate communication between the client and server. Initially,
HTTP is used as the protocol.

## Other Nonfunctional Requirements

### 5.1 Performance Requirements
Performance requirements should emphasize on loading web pages very fast to improve user
experience. We are using React as a framework to build frontend UI. The backend will query
the database and those operations will also take very little amount of time. That is the overall
performance requirements for the project.
### 5.2 Reliability
Atomic operations will take place to maintain data integrity. Token based authorization will
be implemented to authorize users. The website will ask users to accept cookies which will
save the session information in the browser.
### 5.3 Security Requirements
The user privilege will be maintained strictly to ensure security. Users will be provided with
three distinct roles to login to this website. The admin panel of the website will have access to
majority of the data in the database. Teachers and students will also get their respective
access to the database. A token-based authorization will ensure further security measures of
this website.
### 5.4 Software Quality Attributes
Correctness, Reliability, Adequacy, Learnability, Robustness, Maintainability, Readability,
Extensibility, Testability, Efficiency, Portability will be maintained.
