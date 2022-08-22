
Software Requirements
Specification

for

BUP LEAVE REGISTER

Version 1.0 approved

Prepared by 
Tashfia Sikder - 2054901007
Tamanna Rahman - 2054901009
Farhat Binte Shahid - 2054901013
Saeed Hossain Moheb - 2054901050

Bangladesh University of Professionals 

22.08.2022
Table of Contents
Table of Contents                                                                                                                                                         ii
Revision History                                                                                                                                                            ii
1. Introduction	4
1.1 Purpose	4
1.2 Document Convention	4
1.3 Intended Audience and Reading Suggestions	4
1.4 Reference	5
2. Overall Description	5
2.1 Product Perspective	5
2.2 Product Functions	5
2.2.1. Administrators	5
2.2.2. Users (Employees)	6
2.3 User Classes and Characteristics	6
2.4 Operating Environment	7
2.5 Design and Implementation Constraints	7
2.6 User Documentation	7
2.7 Assumptions and Dependencies	7
3. External Interface Requirements	8
3.1 User Interfaces	8
3.1.1. Users	9
3.1.2. Admin Panel	10
3.2 Hardware Interfaces	10
3.3 Software Interfaces	10
3.4 Communication Interfaces	10
4. System Features	11
4.1 Login	11
4.1.1 Description and Priority	11
4.1.2 Stimulus/Response Sequences	11
4.1.3 Functional Requirements	11
4.2 Search	12
4.2.1 Description and Priority	12
4.2.2 Stimulus/Response Sequences	12
4.2.3 Functional Requirements	12
4.3 Dashboard	12
4.3.1 Description and Priority	12
4.3.2 Stimulus/Response Sequences	13
4.3.3 Functional Requirements	13
4.4 Category	13
4.4.1 Description and Priority	13
4.4.2 Stimulus/Response Sequences	14
4.4.3 Functional Requirements	14
5. Other Nonfunctional Requirements	14
5.1 Performance Requirements	14
5.2 Safety Requirements	14
5.3 Security Requirements	15
5.4 Software Quality Attributes	15
5.5 Business Rules	15
6. Other requirements:	15
Appendix A: Glossary	15
Appendix B: Analysis Model	16
Appendix C: To Be Determined List	16








1. Introduction
1.1 Purpose
SRS document provides the audience with overviews of the software products, goals, and parameters is the primary aim for every SRS documents. This Software Requirements Specification provides a complete description of all the functions and specifications of the leave register system. It creates a framework for development teams and help them clearly define what they need to develop. Writing an SRS is necessary for creating startups and launching new software products. Defining software requirements in an SRS also lays the groundwork for other teams such as quality assurance, operations, and maintenance. Since writing as SRS delineates everything that needs to be done and leaves no ambiguity, it mitigates project deviations, time and cost overruns.
1.2 Document Convention
	Entire document should be justified
	Convention for chapter title
•	Font face: Times New Roman
•	Font style: Bold
•	Font Size: 24

	Convention for sub-title 
•	Font face: Times New Roman 
•	Font style: Bold 
•	Font size: 18

	Convention for running text
•	Font face: Times New Roman 
•	Font size: 12
1.3 Intended Audience and Reading Suggestions
The expected audience of this document is the project manager, developers, all employees, admin panel, all faculties, dean & chairman including members of the organization who will use this system. The rest of the part this SRS will contain overall description of project, External interface requirements, System features, Other nonfunctional requirements etc. a table of contents is given from that audience can read the SRS document sequentially with the beginning of overview section.
1.4	Reference
•	Eisner, M. (2021, January 15). 10 business rules examples in process automation. ProcessMaker. Retrieved August 22, 2022, from https://www.processmaker.com/blog/10-examples-of-business-rules-and-logic/
•	830-1993 - IEEE Recommended Practice for Software Requirements Specifications. IEEE Xplore. (n.d.). Retrieved August 22, 2022, from https://ieeexplore.ieee.org/document/392555/definitions#definitions 
•	Barristerhafizkhan@gmail.com. (2020, October 11). Leave and holiday under labour law. counselslaw.com (CLP). Retrieved August 22, 2022, from https://www.counselslaw.com/leave-and-holiday-under-labour-law/ 

2. Overall Description
2.1 Product Perspective
BUP leave register is a replacement for the existing manual leave register which is controlled with a software called PIMS. This particular software is used to maintain more than just leaves.  The proposed leave register will be solely built for maintaining the leave requests of employees and everything will be digitalized and updated. The complete digitalization will make the whole process a lot easier for the authorities to maintain and coordinate the leaves. Moreover, the timing and effort will be reduced as well. 
2.2 Product Functions
2.2.1. Administrators 
●	Admin should be able to see all the leave requests of employees.
●	Admin can see all the past leave requests of the employees and how many days they have taken leaves and how many are remaining.
●	Admin should be able to approve or reject any leave request. 
●	An academic calendar would be provided for better understanding. 
 
FIG 1: Mind Map of Product Functions 

2.2.2. Users (Employees) 
●	Employee will have a dedicated company ID and password.
●	 There will be a dashboard where employees can view the following data: joining date, yearly leaves, total leaves taken, leaves remaining. 
●	They can apply for leave through a form.
●	An academic calendar would be provided for better understanding. 
●	Employees can check their leave status. 
●	There will be a specific rules and regulations section, where the employees can look up all the rules and regulations regarding employee leaves. 
2.3 User Classes and Characteristics
●	BUP Leave Register will be used only by the employees of BUP. Both the administrators and users will be employees of BUP. Each admin and employee will have a unique company ID. 
●	The rules of leave requests vary according to the rank and position of the employees. We will set the conditions of leaves according to those rules. 
●	Leave will be approved for different people according to their higher authority. Such as, chairman will approve faculty leaves and Dean will be aware of it, Dean will approve chairman’s leave and VC will be aware of it, VC will approve Dean’s leaves etc. 
●	Officers according to their categories and staff will get approval from Additional Registrar.

2.4 Operating Environment
BUP leave register will be able to operate in all popular browsers such as Google Chrome, Safari, Mozilla Firefox etc. and Android and iOS mobile apps as well. Users can access our software through their preferred devices such as laptop, tabs, mobile etc. This software will be developed by JaveScript and React. js.
2.5 Design and Implementation Constraints
●	All the conditions should be set properly according to the rules and regulations of leaves of the employees for the software to work properly.
●	These rules vary according to the ranks and positions of the employees, which should be included as well. 
●	There is a hierarchy in the admin panel which should be strictly maintained.
●	MySQL will be used for SQL engine and database.
●	BUP leave register will operate 24 hours a day. 
●	Users should be able to access the software from any device containing internet network and internet browsing capabilities.
●	Only employees with valid company ID should be able to access BUP leave register. 
2.6 User Documentation
●	A quick start guide will be provided which will consist of a few pages of the most important information on a product and short-listed instructions on how to use it. It will be created to help users quickly set up and start using the product straight away.
●	An installation guide or manual focusing mainly on how to setup configuration procedures to make the system ready for use will also be provided.
●	Lastly, a user manual or user guide will be provided. It will contain the fullest information on the product and will be composed of the sections described separately.
2.7 Assumptions and Dependencies
The Following Third-Party products are needed for developing BUP leave register:
Backend:
●	MySQL will be used for SQL engine and database
●	Laravel is needed for API (Application Programming Interface software)
●	XAMPP phpMyAdmin for MySQL. 
Frontend:
●	React.js for building web applications.
●	Third party package which are needed for React.js are:
i.	Node.js
ii.	npm
iii.	Material-UI
iv.	Tailwind CSS

3. External Interface Requirements
3.1 User Interfaces
●	Sign In Interface 
All the employees will have to give company ID and password in order to Sign in . If the user doesn’t have an account yet, they can sign up and create their account. 
 
FIG 2: Sign in Interface 
 
FIG 3: Sign up Interface 
●	Academic Calendar
An academic calendar will be provided so that the users can plan their leaves accordingly. 

3.1.1. Users 
●	Leave Apply Form 
In order to apply for a leave request, user’s will have to fill up a form regarding necessary information such as their raking and position, what kind of leaves they are taking, and for how many days etc. 
●	Leave Status 
As there is a hierarchy of admin panel for approving an employee’s leave request, the employees will be able to see in which step their request is and they will be notify if their request is accepted or rejected.
 
FIG 4: Home Interface 

●	All Leave Details
This section will have all the necessary details about individual employee’s leave such as how many leaves they have taken, how many are remaining etc. 
●	Rules and Regulations 
There will be a specific rules and regulations section, where the employees can look up all the rules and regulations regarding employee leaves. 
●	Leave
Users can use this section to see what kind of leaves they have and how many days they can take for a particular leave. This section will be added so that users can have a better understanding. 

3.1.2. Admin Panel  
●	Approve or Reject
Based on the application of the employees, admins can approve or reject any leave request. 
●	All Leave Request 
Admins will have all the information regarding an employee’s leave for example pas records of leaves, how many leaves are pending etc. 


3.2 Hardware Interfaces
As our software is compatible, it will only require the recommended configuration (basic requirements of hardware), there is no need for any particular hardware in order to use this software. 
3.3 Software Interfaces
●	Any preferred operating system of the user.
●	A browser to load and view the software. Apart from that, no specific software is needed.
3.4 Communication Interfaces
This project supports all types of web browsers. We are using simple electronic forms for leave request. 


4. System Features
The functional requirements for BUP Leave Register, system features and the major services provided by our system are described here.
4.1 Login
4.1.1 Description and Priority
Users must need to login to their accounts to get access to the system. Without login they won't be able to enter our system. 
Priority: High 
Priority Component Ratings (Scale from a low of 1 to a high of 9):
●	Benefit: 9
●	Penalty: 2
●	Cost: 5
●	Risk: 3
4.1.2 Stimulus/Response Sequences
●	BUP Leave Register > User > Login > Sign up / Sign in
●	BUP Leave Register > Admin > Login > sign up / Sign in
4.1.3 Functional Requirements
The detailed functional requirements, software capabilities that must be present in order for the user to carry out the services provided by the login system, or to execute the use case associated with Login, are described here:
●	Sign Up: If the users do not have any account, then they must need to create an account first by using their unique ID given by BUP. This procedure will be completed by providing First name, Last name, ID and Password. 
●	Sign In: To access the features, Users have to sign in and enter the system by using their ID and password. 
●	Unique ID: BUP always provides an unique ID to every single Faculty, Employee and other members. This ID will be associated with the Admin. 
●	Password: Setting up a password is a must for everyone to secure their account and enter the system. 
●	Name: Real name that is recorded in the academic Admin system is required to verify the identity. 
4.2 Search
4.2.1 Description and Priority
Both user and admin can search for different things, such as:
●	Admin: Admin can search for a particular user, any date, leave types, calendar etc. 
●	User: Users can search for any particular date, holidays, leave types etc. 
Priority: Higher Medium 
Priority Component Ratings (Scale from a low of 1 to a high of 9):
●	Benefit: 8
●	Penalty: 1
●	Cost: 4
●	Risk: 0
4.2.2 Stimulus/Response Sequences
Search Bar > keyboard input / history selects > Select / open 
4.2.3 Functional Requirements
The detailed functional requirements, software capabilities that must be present in the search system, or to execute the use case associated with Search, are described here:
●	Search Bar: It will take the keyboard input and match our database to find out the searches. Also Search Engine Optimization (SEO) feature will help to find. 
●	History: Search bar database will store the history of searches in the memory to make it faster for future use. 
●	Select / Open: After searching the desired field, users can enter or open or select the field and it will be directly integrated to that field. 

4.3 Dashboard
4.3.1 Description and Priority
Dashboard is integrated with the sign up system. That means, every single user who will sign up to the system, will get an automatic generated Dashboard of the person where every detail of the person will be recorded. 
Priority: High 
Priority Component Ratings (Scale from a low of 1 to a high of 9):
●	Benefit: 9
●	Penalty: 5
●	Cost: 6
●	Risk: 4
4.3.2 Stimulus/Response Sequences
BUP Leave Register > Login > Dashboard > My Profile > Settings > Records > Calendar > Leave 
4.3.3 Functional Requirements
The detailed functional requirements, software capabilities that must be present in the Dashboard system, or to execute the use case associated with Dashboard, are described here:
●	Sign Up: After signing up or creating an account, the Dashboard for that particular user will be created. 
●	My Profile: Dashboard will contain the user's profile, where the basic information is recorded like Name, ID, Photo, Rank, Designation, Address, Contact Details, Leaves
●	Settings: This function holds the power of editing or modifying the recorded data like Photo, Password etc. 
●	Calendar: It shows the Annual calendar of BUP since the system was started to be used, with all the holidays, working days, leave days, exam days and other necessary information. 
●	Leave: It has the records of the leave type, remaining leaves, and leave details of a user. Also, users can apply for leaves by using a Form, which will be sent to the admin server. Admins can also use this function to take leaves for themselves. 
4.4 Category
4.4.1 Description and Priority
It is the criteria for different types of leaves. Based on the criteria, leaves are divided into different categories. 
Priority: High 
Priority Component Ratings (Scale from a low of 1 to a high of 9):
●	Benefit: 8
●	Penalty: 4
●	Cost: 5
●	Risk: 6
4.4.2 Stimulus/Response Sequences
Login > Dashboard > Apply for Leave > Type > Sick / Casual / Yearly > Days (With Dates) > Reasons > Additional Documents > Submit
4.4.3 Functional Requirements
The detailed functional requirements, software capabilities that must be present in the Category system, are described here:
●	Casual leaves: For BUP employees this leave in a year is 20 days
●	Entertainment leave: This leave is 15 days in 3 years. Employees will get a bonus for spending this type of leave. But they have to stay in contact and can not go out of the country.
●	Earned leave: It is 1 day when an employee works for 11 consecutive days. This type of leave is stored from the day the employee had joined. It’s not yearly. This leave would be calculated based on the number of an employee’s work days. Employees may choose to take it, or save it and get benefits after they retire. An employee can take up to 4 months of earned leave together, 6 months if sick. Also, employees can take all of their earned leaves together if they are unable to join for work. The Chairman and Dean can only help with referring for this leave for an employee to the Administration.

5. Other Nonfunctional Requirements
5.1 Performance Requirements
●	Performance needs to be super-fast, as slow systems can cause data inconsistencies. 
●	It requires using facilities for unlimited time
●	It should be as user friendly as possible
●	The system should be accessible by different types of devices
5.2 Safety Requirements
●	Login attempts should be secured 
●	Passwords need to be end-to-end encrypted 
●	Notify if the system gets any unusual login attempts 
●	Necessary information needs to be confidential 
●	Must satisfy Security or Privacy Certifications given by ICT law

5.3 Security Requirements
●	Leave days, Reasons for leave and other necessary Documents should be confidential 
●	Admins should have the two factor verification system to enter into the user account. 
5.4 Software Quality Attributes
●	Adaptability: Excellent 
●	Availability: Rare
●	Correctness: Good
●	Flexibility: Good
●	Interoperability: Average 
●	Maintainability: Excellent 
●	Portability: Good
●	Reliability: Good
●	Reusability: Bad
●	Robustness: Good
●	Testability: Excellent 
●	Usability: Excellent 
5.5 Business Rules
Author can cancel service for any customer that fails to make a payment before or after purchasing the software. Also, any violation of terms and conditions for the software can result in a service cancellation. 

6. Other requirements
Appendix A: Glossary
●	PhpMyAdmin: phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web. phpMyAdmin supports a wide range of operations on MySQL and MariaDB.
●	TailwindCSS: Tailwind CSS is the only framework that is easy to customize, adapts to only design & the built size is easy.
●	Material UI: MUI provides a simple, customizable, and accessible library of React components. Following own design system, or start with Material Design. One can develop React applications faster.
●	Notify: Notify is an all-in-one platform for automating modern web projects.
●	React Framer Motion: Framer Motion provides a simple animation and gesture API that makes it simple to animate HTML and SVG elements while maintaining semantics. 
●	React Icons: React Icons Include popular icons in our React projects easily with react-icons, which utilizes ES6 imports that allows you to include only the icons that our project is using.
●	Styled Components: Styled Components is a variant on “CSS-in-JS”—which solves many of the problems with traditional CSS. 
●	Axios: Axios is a simple promise-based HTTP client for the browser and node.js. Axios provides a simple to use library in a small package with a very extensible interface.
●	Twin Macro: Twin blends the magic of Tailwind with the flexibility of css-in-js. Twin macro also helps to attach custom animation to classes through the CSS-in-JS declaration.
Appendix B: Analysis Model
 
FIG 5: BUP Leave Register Mind Map
Appendix C: To Be Determined List
•	Abhilasha Lahigude Follow Learner. (n.d.). Leave management system: Software requirements specification document... Leave Management System: Software Requirements Specification Document... Retrieved August 22, 2022, from https://www.slideshare.net/abhilashalahigude/srsforleavemgmtfinalprint 
