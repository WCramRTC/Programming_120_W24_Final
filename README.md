
# Prog_1_W24_Final_YourName - C# Programming Assignment

## Description:
This assignment aims to reinforce concepts of arrays, loops, and basic user interaction in C#. You will create a small application that manages student names and grades using parallel arrays. The application will display all names, corresponding grades, and their letter grades, calculate the average grade, allow the user to change individual grades, and provide an option to exit the application.

## Requirements:

1. **Create a C# console application named Prog_1_W24_Final_YourName.**
2. **Implement parallel arrays:**
   - One array to store student names (strings).
   - Another array to store corresponding grades (ints).
3. **Display all student names, grades, and letter grades.**
4. **Calculate the average grade.**
5. **Determine the letter grade based on the average.**
6. **Provide a menu for the user with the following options:**
   - Display all names, grades, and letter grades
   - Display average grade and letter grade
   - Change a grade
   - Exit
7. **Ensure appropriate comments are included throughout the code to explain functionality.**
8. **Submit the assignment via a GitHub repository link on Canvas.**

## Step-by-Step Explanation:

1. **Create a C# console application named Prog_1_W24_Final_YourName:**

   - Explanation: Begin by creating a new C# console application project in your development environment. Name the project `Prog_1_W24_Final_YourName`. This will serve as the foundation for your assignment.

   - Console Output Example:
   ```
   Welcome to Prog_1_W24_Final_YourName
   ```

2. **Implement parallel arrays:**

   - Explanation: Declare two arrays:
     - One array to store student names (strings).
     - Another array to store corresponding grades (ints). 
     - Make sure there are at least 5 names and 5 grades.

     These arrays should be parallel, meaning that each element in the student names array corresponds to the grade of the same index in the grades array.

   - Example:
     ```csharp
     string[] studentNames = { "Alice", "Bob", "Charlie", "David" };
     int[] studentGrades = { 85, 92, 78, 88 };
     ```

   - Console Output Example:
   ```
   Student Names:
   Alice
   Bob
   Charlie
   David

   Student Grades:
   85
   92
   78
   88
   ```

3. **Provide a menu for user interaction:**

   - Explanation: Implement a menu with the following options:
     - Display all names, grades, and letter grades
     - Display average grade and letter grade
     - Change a grade
     - Exit

   - Console Output Example (Menu):
   ```
   Menu:
   1. Display all names, grades, and letter grades
   2. Display average grade and letter grade
   3. Change a grade
   4. Exit
   ```

4. **Display all student names, grades, and letter grades:**

   - Explanation: Write code to display all the student names, their corresponding grades, and their letter grades.

   - Console Output Example:
   ```
   Student Names, Grades, and Letter Grades:
   Alice - 85 (B)
   Bob - 92 (A)
   Charlie - 78 (C)
   David - 88 (B)
   ```

5. **Calculate the average grade:**

   - Explanation: Calculate the average grade from the grades array.

   - Console Output Example:
   ```
   Average Grade: 85.75
   ```

7. **Determine the letter grade based on the average:**

Create a method that takes a numerical value between 0 and 100. Following the table below, have it return a string with the appropriate letter grade.

   - Explanation: Determine the letter grade based on the calculated average grade. You can use a simple grading scale, such as:
     - A: 90-100
     - B: 80-89
     - C: 70-79
     - D: 60-69
     - F: Below 60

   - Console Output Example:
   ```
   Letter Grade: B
   ```

8. ## Change a Grade:

- Explanation: Allow the user to change a student's grade by displaying the student's name and their index in the array, then prompting the user to enter the index of the student whose grade they want to change and the new grade.

- Console Output Example:
  ```
  Change a Grade:
  0: Alice
  1: Bob
  2: Charlie
  3: David

  Enter the index of the student whose grade you want to change: 2
  Enter the new grade for Charlie: 85

  Grade for Charlie updated successfully.
  ```


9. **Ensure appropriate comments are included throughout the code:**

   - Explanation: Add comments to the code to explain its functionality. Comments should describe what each section of code does, making it easier for others (and yourself) to understand the logic behind the implementation.

10. **Submit the assignment via a GitHub repository link on Canvas:**

   - Explanation: Upload your completed assignment to a GitHub repository and submit the repository link on Canvas for grading.

   - Console Output Example:
   ```
   Assignment submitted successfully via GitHub repository link.
   ```


---
## Rubric:

| Category                       | Description                                                          | Points  |     |
| ------------------------------ | -------------------------------------------------------------------- | ------- | --- |
| Code Structure and Readability | Proper naming conventions, indentation, and formatting               | 5       |     |
|                                | Clear and concise code comments explaining functionality             | 25      |     |
|                                | Appropriate code structure                                           | 25      |     |
| Functionality                  | Display all names and grades                                         | 15      |     |
|                                | Calculate and display average grade                                  | 15      |     |
|                                | Determine and display letter grade                                   | 15      |     |
|                                | Allow user to change a grade                                         | 15      |     |
|                                | Provide an option to exit the application                            | 15      |     |
| Parallel Arrays Implementation | Proper creation and initialization of parallel arrays                | 20      |     |
|                                | Correct usage of parallel arrays throughout the application          | 20      |     |
| GitHub Submission              | Proper submission of assignment via GitHub repository link on Canvas | 20      |     |
| **Total**                      |                                                                      | **200** |     |

---

## Expected Output

```console
Welcome to Prog_1_W24_Final_YourName

Menu:
1. Display all names, grades, and letter grades
2. Display average grade and letter grade
3. Change a grade
4. Exit

Enter your choice: 1

Student Names, Grades, and Letter Grades:
Alice - 85 (B)
Bob - 92 (A)
Charlie - 78 (C)
David - 88 (B)

Menu:
1. Display all names, grades, and letter grades
2. Display average grade and letter grade
3. Change a grade
4. Exit

Enter your choice: 2

Average Grade: 85.75
Letter Grade: B

Menu:
1. Display all names, grades, and letter grades
2. Display average grade and letter grade
3. Change a grade
4. Exit

Enter your choice: 3

Change a Grade:
0: Alice
1: Bob
2: Charlie
3: David

Enter the index of the student whose grade you want to change: 2
Enter the new grade for Charlie: 85

Grade for Charlie updated successfully.

Menu:
1. Display all names, grades, and letter grades
2. Display average grade and letter grade
3. Change a grade
4. Exit

Enter your choice: 1

Student Names, Grades, and Letter Grades:
Alice - 85 (B)
Bob - 92 (A)
Charlie - 85 (B)
David - 88 (B)

Menu:
1. Display all names, grades, and letter grades
2. Display average grade and letter grade
3. Change a grade
4. Exit

Enter your choice: 4

Thank you for using Prog_1_W24_Final_YourName. Exiting...

```
