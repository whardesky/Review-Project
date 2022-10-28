# Review-Project

## CSC-212 Data Structures and Algorithms

### Group Members
 - Alex Estrada
 - Wes Hardesky

### Premise

Build an algorithm to interpret course grades into a semester final grade.

### Purpose

Knowing your grade throughout the term is one of the most critical tools you have at your disposal as a student. Without this knowledge, it becomes incredibly difficult to assess your knowledge of the subject matter relative to a course. It also means not knowing where you stand in a course and more importantly whether you may truly need help or not.

This project, when successfully compiled, will aleviate that concern for this course. An effective output will provide merely a course grade calculated based on all possible points that can be earned within the course.

### Part 1: Planning

Step 1: Determine how our code will function in an overarching 
Divide the tasks to complete the review project in its entirety.
- Alex Estrada is tasked with providing the initial algorithm and psuedo code for the project.

### Pseudo Code



```
// Input 
/*How to calculate weighted grades
	find the average of all assignments of the same type and multiply by its weight (percent)
		Ex. total quiz avg is 85 and quiz weight is 30%
		So, quiz weight = 85*.3 which is 25.5 points
	Next, calculate the remaining weight of the other types of assignments (WEIGHT should add to 100)
	Lastly, add all the points together and the result is the final grade

	Final Gade Calculation Example
		Quiz Weight (QW) = 30%
		Quiz Avg (QA) = 95
		Test Weight (TW) = 40%
		Test Avg (TA) = 85
		Final Exam Weight  (FW) = 30%
		Final Exam Grade (Avg)  (FG) = 80
	Final Grade = (QW*QA)+(TW*TA)+(FW+FG) = (0.3 * 95) + (0.4 * 85) + (0.3 * 80) = 86.5
*/

// Use the function below for each type of assignment the course requires
/* double homeworkWeight function
	ask the user for number of homeworks and the weight of homeworks
	create a vector with each homework grade input
	add each element and divide by total number of elements to find Avg of homeworks
	multiply the average by the weight (i.e 30% should be converted to 0.3)
	return homeworkAvg which should be of type double
*/
```

# Large Title
## subtitle
### subsub title

- [space] is bullet point
