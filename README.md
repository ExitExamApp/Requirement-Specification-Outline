Software Requirements Specification

For 

EEprep
Exit Exam Preparation Application

Version 1.0



Prepared by: Abdullah Alathel, Charith Perera, Christopher Gborgli, Clarence Williams and Rephael Edwards

February 9, 2017








Requirements Document
Collaborators: a.alathel93@gmail.com charithp120@gmail.com cagborgli0311@my.mwsu.edu clarence.williams@csoweb.org rephie0000@gmail.com 

Exit Exam Preparation Application	1
Prepared by: Abdullah Alathel, Charith Perera, Christopher Gborgli, Clarence Williams and Rephael Edwards	1
1. Introduction Overview	4
1.1 Purpose of the Document	4
1.2 Scope of Project	4
1.2.1 Main Objective	4
1.2.3 Specific Goals	4
1.3 Overview of Document	5
2. Users	5
2.1 Who are Users?	5
2.2 Use cases and Use case Diagrams	6
2.3 Scenarios	6
3.1 Development Environment	6
3.2 Target Environment	6
3.3 Functional Requirements	7
3.3.1 Issues	7
3.3.2 Major Subsystems	7
3.3.3 Major Functions	7
3.3.4 Major Classes Identified and Listed	7
3.3.5 Minor System Functions	7
3.4 User Interface Specifications	7
3.5 Non-functional Requirements	8
3.5.1 Management	8
3.5.2 Technical	8
3.5.3 Performance	8
3.5.4 Security	8
3.6 System Evolution / Maintenance	8
4. Other Deliverables Required	8
5. Risks	8
6. Other things you think of..	9
7. Glossary of Terms Used in this Document	9
8. References (MLA)	9





1. Introduction Overview
1.1 Purpose of the Document
The customer manages a committee that gives an exit exam for graduating Computer Science students. The customer would like to have a stand alone application that prepares students for the exam, by giving multiple choice questions and feedback based on a specific list of topics the students previously chose. The customer also wants the score of each student who finished to be delivered to her. This document describes how the Exit Exam Preparation Application that will be developed.
1.2 Scope of Project
There are two type of user for this application - student, admin
A Student will be able to
	1.2.1 Main Objective
	The software will enable senior computer science students to take practice tests in preparation for the Exit Exam. The software will also give feedback on questions missed and an explanation for each question asked to the user.

Build a GUI-driven application that will give multiple choice questions for a chosen list of topics, provides feedback for each question, and deliver the scores of students to Dr Halverson
	1.2.3 Specific Goals
Create a “graphical user” interface for the user to view questions and select their answer.
Create an interface for the user to view the answer 
Create a database of questions, their answers and explanations
Create a way for the professor to be notified of the results from each session.

The customer desires an application with graphical user interface
The customer desires to provide feedback for each question

1.3 Overview of Document
The remainder of the document is intended to inform the customer of the intended system.  Hardware and software requirements, major users, both major and minor functions, constraints, and intended user interface are described.




2. Users 
2.1 Who are Users?

Our primary users will be students from Midwestern State University who need to take the entrance exam in order to graduate. The users will choose from a set of answers presented in multiple choice form beneath the questions, while the questions themselves will be categorized and presented in sections. The program will present the grade the student achieved after the exam is completed on the screen and will also email them their score.


2.2 Use cases and Use case Diagrams

	
2.3 Scenarios
	A senior computer science student wanting to practice for his/her Exit Exam can use the EEprep system by entering their first name,last name, and email .After getting into the system, he/she can choose either a  category. The student gets to choose how many questions to answer if the “Random” category is chosen .

3.1 Development Environment
Visual Studio IDE for programming 
Database will be done using SQL
3.2 Target Environment
The development environment will be as follows:
Access to internet connection
Database software
3.3 Functional Requirements
The system 
Must give the user a question to answer and allow them to select the correct answer.
Must give feedback for all questions answered. This includes if the question was answered correctly or incorrectly and an explanation of the answer for the question.
Must give output of the result of the exercise.
Must alert the professor about who did the activity, the time spent on it, when they did it and the results.
Must allow the user to select the number of questions to be asked at the start.
Must access questions and answers from a database.

	3.3.1 Issues
A limited number of questions are available for the initial database development because we do not have access to test banks. 
	3.3.2 Major Subsystems
	3.3.3 Major Functions
Provide feedback for each question
Show the questions in a graphical interface
Deliver each user score to Dr.Halverson
	3.3.4 Major Classes Identified and Listed
Sign in window
Main Window
Quiz Window
Questions Class
	3.3.5 Minor System Functions
Highlight the correct answer
Keep track of the user’s score
3.4 User Interface Specifications
The system should offer:
A login page
A practice test selection page
A practice test page
3.5 Non-functional Requirements 
	3.5.1 Management
The system must be platform independent.
	3.5.2 Technical
The system must have a GUI.
The system must randomly choose a question from the database.
	3.5.3 Performance
The system must send results to the customer.
The system must not work with the actual software used to give the exam.
	3.5.4 Security
Since the system required is a stand alone, no login with password is needed
3.6 System Evolution / Maintenance

4. Other Deliverables Required
At the end of the software development cycle, a project plan, requirements specification document, test plan, prototype, and user manual outline will be delivered to the professors of the Computer Science department at Midwestern State University.
5. Risks
	Developers have little knowledge on SQL IDE which might cause
6. Other things you think of..
7. Glossary of Terms Used in this Document
	GUI - Graphical User Interface
IDE- Integrated Development Environment
8. References (MLA)
"Easily Create All Types of UML Diagrams." UML Diagrams Online | Online UML Tool | UML Diagram Creator | Creately. N.p., n.d. Web. 07 Feb. 2017.

Halverson, Dr. Ranette, Ph.D. , Department of Computer Science, College of Science and Mathematics, Midwestern State University, Wichita Falls, Texas. 

