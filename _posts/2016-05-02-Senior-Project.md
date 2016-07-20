---
layout: post
title: Senior Project
description: "A little information on the start of my Senior Project"
modified: 2016-05-02
tags: [Java, Senior Project]
---

I'm currently working with the Computer Science Department Chair on creating an intuitive learning module system for one of the introduction course, CS 202.  This would be a test case for them to connect outside/integrated application directly to the learning module Desire 2 Learn (D2L) at Regis University.  

The application itself will be a very rudimentary program using a seven segment display that can generate all 128 states that a student would have to mark specific switches as on (1) or off (0). There are two sides to the program, the first side is to give a student the ability to practice on a set number of problems that they can complete and get instant feedback to see if they need more practice, go back to the course material or if they are ready to complete the homework problem.  The second section is the homework problem that would generate from all 128 states and grade the problem set at the completion.  

The value added from this application would it gives the student an instant grade to know how well they are fairing in the course.  It free's up time for the professor for more interaction with the students and it gives the student the ability to practice with course objectives as they are learning them.  One of the biggest complaints from the course is they learn a wide variety of information but do not get to interact with the learning objectives other than the homework problems.   

This is a short course with only 8 weeks to complete everything from start to finish so the end goal is a little ambiguous at this point.  The goal would be to have a working application running independent of D2L and then try to plug in the application at the end.  

The program will be based on Java using Net Beans, and AWT/Swing for the GUI.  I'm not a very artistic person so the GUI will probably be the hardest part of this application.  

### Items to accomplish:

1. Layout
   1. Overall theme
   2. Main Page
   3. Homework Page
   4. Practice Page
2. Practice Page
   1. Allow student to generate # of problems from 1-10
   2. Only generate from a specific problem set
3. Button Controls
   1. Submit
   2. Hint
   3. Reset
4. Homework Page
   1. Generate 10 problems from the 128 problem set
   2. Show grade after Submit
5. Database
   1. Store student information
   2. Store homework problems with student_id, grade and date_time
   3. Store practice problem attempts with student_id, grade, # of problems, date_time
6. Connect application to D2L
   1. Valence API
   2. Tomcat Server
