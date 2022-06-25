# TTMS
This project is aimed at developing a paper free application “Timetable Management System” that is important to a college. It is a web-based application which is used to generate a timetable based on the staff choice. Our application will take various inputs like number of courses, staff details, batch, year, semester, labs, departments, student details. Based on these inputs, it will generate a possible timetable schema for working days. The generated timetable schema is managed by the administrator. Staff members will be able to select their specified slots with respect to the schema. The constraints include avoiding clashes of time slots, number of slots and number of   courses etc. Students will be able to view the generated timetable.
The Timetable Management System in Education is designed on the base of considering a motto called “Go Paper Free”. In manual process it requires more paper work and man power to design a optimal timetable. But we cannot say the designed timetable as optimal because it is designed only on the management constraint’s it does not satisfy the lecturer’s. Sometimes lecturer can be dual allocated in different department at the same timings in the manual process. if we want to modify the timetable we need to reconstruct the entire timetable to avoid the prone of error’s. It may consume more time to redesign entire time table to satisfy the management constraints. To avoid this we designed a web-based application used by the college to generate optimal timetable. This application consists of three set of modules   Administrator, Lecturer and   Student. Lecturer’s and Student’s need to register with their details. 
In our application administrator has more privileges, users need to register with their details. Registered lecturer details is reverified by the administrator to provide Double Authentication and authorization to access the data of application. The Approved lecturer will access the data of  application with their credentials. Approved lecturer details can be view by the administrator. Registered student details can be view by the administrator. Administrator has a dashboard which show’s the count of lecturer’s, course’s and student’s. Administrator will add the details of departments and courses. Administrator will assign the courses to the lecturer’s. Assigned courses details can be accessible by the lecturer’s with their credentials. Administrator will generate a timetable schema based on the working days and academic details. Administrator can select the slots before the timetable schema is accessed by the lecturer’s. Administrator book the slots for the labs in the management. After that lecturer can access the generated timetable schema and book the slots based on their assigned course and academic details.            
          Timetable Management System project is intended for site administrator who can generate time table schema according to the management constraints. After generating the time table schema. Lecturer can register and login to the application and select their specific slots and can view their assigned courses. Registered lecturer can also provide grievance to the administrator. Those grievance can be view and managed by the administrator. It avoids paperwork and manpower its completely error free. After creating the time table student can register and login to application and view their time table according to their semesters and branches and download it. 
1.2   Objectives: 
•	To provide user free Environment and flexibility.
•	To avoid paperwork and manpower and saves lot of time. 
•	To provide selection of slots to the lecturers.  
•	To provide visibility of timetable with respect to their login id and password.
•	To provide authentic and authorized features to the current system where Admin and lecturer can allocate the specific slots based on their choice.
•	To provide the reverification to the registered lecturer that is managed by the admin.
•	To Provide grievance option to the Lecturer’s.
•	To provide administrator to manage the timetable based on the grievance.
•	To provide the environment to view the timetable by the student’s.
•	To provide the download option to download the generated timetable for the users.
2.	SYSTEM ANALYSIS 
2.1   Existing system: 
Generally timetable is prepared manually by the management with respect to their constraints. Creating time table manually is very time consuming process.  Manual process takes more time, more paper work and not sure about usefulness of effort.  Separate timetable copy has to be created for teachers. Dual allocation of same teacher at same time in different classes will takes places. If we want to modify the timetable we need to reconstruct the entire timetable to satisfy the management constraints. 
2.1.1   Disadvantages of Existing System: 
1.	Creating timetable manually is very time consuming process. 
2.	Timetables made manually are prone to errors such as redundancy in scheduling of classes at a certain time.
3.	  Manual timetable requires more manpower and paperwork. 
4.	 Detecting dual allocation of same teacher at same time in different classes is not possible.
5.	If we want to modify the timetable we need to reconstruct the entire timetable to satisfy the management constraints.
6.	The designed timetable cannot say as optimal because it satisfy the management constraints but it may not satisfy the lecturer’s.
7.	 Manual process is not user free and flexible.
2.2   Motivation to the Problem:
The project “TIMETABLE MANAGEMENT SYSTEM” is a web based application which is helpful for the education managements to get the optimal timetables based on the management Constraints. It provides the Staff choice for user free environment. It avoids the Paper work for the management. This web application has more Flexibility we can modify based on the management constraints
2.3   Proposed system: 
       The proposed system automates the existing system. It decreases the paper work and also solve the timetable generation being faced by college every academic year. This application avoids the allocation of teacher in dual classes at the same time alerts the user. We can reduce high cost and slow turnaround involved in the generation of near-optimal timetables. The system has capabilities for input of the various courses, departments, labs, lecturers, grievance and the specification of a few constraints from which the timetable is constructed. The proposed timetable system for this project seeks to generate maximum error free timetable using the Staff Choice (selection and crossover). 
2.3.1   Advantages of Introduced System: 
1.	Unlike the manual timetable process, this system offers flexibility.
2.	It utilizes minimal processing/computing power.
3.	It greatly reduces the time needed to generate maximum error free timetables.
4.	It almost eliminates paperwork.
5.	It simplifies the timetable process.
6.	The generated timetable is secure, ensures that there is transparency of activities that take place and does not allow individuals to tamper with the timetable if they are not authorized.
7.	It provides the environment to manage the application by the administrator.
8.	It Provides the environment to select the specific slots in the timetable schema by the  lecturer’s. 
9.	It provides the grievance option to the lecturer’s.
10.	It provides administrator to manage the timetable based on the grievance.
11.	It provides the Download option to users to download the generated timetable.
12.	It provides more privileges to the administrator to modify the generated timetable.

		3 Modules:
 	A module is defined as the unique and addressable components of the software which can be solved and modified independently without disturbing (or affecting in very small amount) other modules of the software. Thus, very software design should follow modularity. The process of breaking down a software into multiple independent modules where each module is developed separately is called Modularization. In the “Timetable management System” application there three modules those are admin module, lecturer module and student module.
		3.1 Admin Module: 
	The functions of the Administrator module are to handle the entire administrator task. Admin can create the time table according to the constraints (slots, courses, semesters, departments, labs). This module can see the registrations of students and lecturers. It reverify the registered lecturer’s details and the approve the lecturer’s. Admin can see and manage the departments and courses. Admin can assign the courses to the lecturers. Admin can also view the registered details. It will also handle the responsibility of adding entries in the generated time table. Admin can manage the time slots. Admin can select the slots based on the priority of the courses. Admin can view and download the timetables.  Admin can view the grievance provided by the lecturer.
  	3.2   Lecturer Module: 
 	The functions of the Lecture module are view their assigned courses and schedule the courses. Firstly lecturer need to register and approved by the admin to get their credentials. Lecturer can select their specific slots in the created time table by the admin. Once slots are booked to the one lecturer. Other lecturers cannot book  the same slots. Only admin can edit the booked slots. lecturer’s can send their grievance to  admin. 

      3.3 Student Module: 
The function of the student module is to view the generated timetable and can download it. Firstly student need to register based on registered credentials student can signin. All the students can signin and view their timetable and download their timetable according to their departments.

4 CONCLUSION 
     
The current system using in the College is manual system. with the manual system, there are sometimes problems in managing the timetable with respect to the lecturer’s. The Manual time table is not satisfies the all lecturers and it prone to errors because of dual allocation of classes same teacher at same time. Timetable Management System, is a paperless time table. It is completely web-based application. It is managed by administrator. administrator can generate timetable schema according to the management constraints. After generating the timetable schema lecturer can register and login to the web application and select their specific slots in the timetable according to the constraints. Main advantage of these application is to avoid paperwork, manpower and also consume less time. These application is completely error free. These application is very helpful for present collages for generating the time table according to the constraints. These application can generate optimal time table in less time. It is very friendly and easy to use. This system is used for the colleges or any other institutes that requires timetable management system. 



