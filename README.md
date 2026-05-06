# CSC-125-201 Final Project

## Project Description
This program helps a professor store, organize, and track students' grades throughout the semester. It allows the professor to record each student's information, enter grades for assignments, quizzes, exams, and final projects, and monitor class performance. 
The program can show how many students are enrolled in the class, how many are passing, and how many are failing. It can also identify the student with the highest grade and the student with the lowest grade. In addition, it calculates the grade average and generates a final report that summarizes the students’ performance for the semester. 

## Features
- The function add_student(students) receives students as an empty dictionary, asks the user for a student's ID, name, and grades, then adds that information to the empty dictionary. As a result, return the students dictionary containing students' information.  

- The fucntion called clean_input(user_input) receives the user input and returns the clean version. 

- The function called total_grade(students) that calculates the total grade for each student receives students' dictionary as a parameter, verifies whether the student passed or faille the class and returns the updated students' dictionary with the total_grade and the status of the student which either passed or failed. 

- The function named calculate_average(students) receives the updated students’dictionary, calculates the average, then returns average.  

- The function named count_attended(students) receives students’dictionary as parameter and returns the length of students’ dictionary as number of students attended the class.  

- The function called count_status(students) receives students’ dictionary as parameter and returns the number of passed and failed. 
- The function max_min_grade(students) receives students’ dictionary as parameter and returns the highest grade and the minimum grade. 

- The function display_report(students) receives the full student dictionary and average as parameters, and displays each student’s name, grades, total_grade, students attended the class, average, and passed or failed status.
   
- The main function in which add_student(students), total_grade(students), calculate_average(students), count_attended(students), count_status(students) and display_report are being called is used as a container.  
