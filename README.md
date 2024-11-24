# CODTECH-Task-2

My Task is to create the Student based Calculator, which calculates their Total Marks, Average Percentage & their corresponding Grade also.Calculate the grade of a student based on their marks. This task meets all of the requirements and has been thoroughly tested.

1. Project Setup
Ensure Java is installed on your system.
Use an IDE (like Eclipse, IntelliJ IDEA, or NetBeans) to create a new Java project.
Create a new Java class for the Student-based Calculator (e.g., StudentGrade p).

3. Import Swing Packages
Import necessary Swing and AWT packages for building the GUI components:
java
Copy code
import javax.swing.*;
import java.awt.*;
import java.awt.event.*;

5. Define the Purpose of the Calculator
Determine the types of calculations the Student-based Calculator should perform. For example:
Grade Calculation
Marks to Grade Conversion
Average Score Calculation

6. Create GUI Components
JFrame: Main window for the application.
JTextField: For displaying results or user input (marks, grades).
JButtons: For user actions like calculating GPA, average, or converting marks to grades.
JComboBox: For selecting options like different subjects or grade scale types.
JLabels: For showing labels and instructions to guide the user.
JPanel: To organize components like text fields and buttons.

8. Layout the Components
Organize the layout using layout managers like GridLayout, FlowLayout, or BorderLayout.
Place input fields for student marks, a button to calculate the GPA, and areas to display the results (e.g., GPA, grade).
9. Add Action Listeners
Implement ActionListener to handle events triggered by button clicks. For example:
When the user clicks "Calculate GPA," the program should compute the GPA based on the entered marks.
When the user clicks "Convert," the program should convert marks to corresponding grades (A, B, C, etc.).

11. Implement Student Grade Calculator Logic

 if (percentage >= 75) {
            return "Distnction";
        } else if (percentage >= 65) {
            return "First Class";
        } else if (percentage >= 50) {
            return "Second Class";
        } else if (percentage >= 35) {
            return "Third Class";
        } else if (percentage <35) {
            return "Fail";
        } else {
            return "No record Found";
        }
    }
You can also calculate the average score, total marks, or any other related computation.
Snapshot 

![StudentGrade Output2](https://github.com/user-attachments/assets/aa6123fc-5c5d-4246-ab38-8602fbb1c59c)
![StudentGrade output1](https://github.com/user-attachments/assets/d19c6fc3-820c-4bdd-a28a-9b2edf747a09)
