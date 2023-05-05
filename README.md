Download Link: https://assignmentchef.com/product/solved-csi121-assignment1
<br>
This assignment requires you to write a program in Java that help a student to enrol into the Bachelor of Computer Science course, including the core subjects enrolment, the selecting of a major and the elective subjects.

Background

The Bachelor of Compute Science course contains three parts, i.e., the core subjects, the majors and the elective subjects. In order to complete the course, students shall complete at least 144 credit points.

<ol>

 <li>All students shall complete 15 core subjects, i.e., 96 cp in total.</li>

 <li>All students shall complete a major with four or five subjects, i.e., 24/30 cp in total. The course contains five majors and each student can only select one major. The five majors are Big Data, Cyber Security, Digital Systems Security, Game and Mobile Development, and Software Engineering. The core subjects of each major are displayed in the following snapshots.</li>

</ol>




(It is assumed that all five subjects are compulsory for the Game and Mobile Development Major)

<ol start="3">

 <li>All students shall enrol 4~5 elective subjects to make up 144 credit points. (Students are allowed to enrol more than 144 credit points). The elective subjects are the collection of subjects from all five majors.</li>

</ol>

You are required to design, implement and test a course enrolment system to enrol one student into the Bachelor of Computer Science course by using Java. The system shall contain five classes, i.e., the Student class, the Subject class, the Major class, the Course class, and the Enrolment class (the primary class). The basic requirements of each class are as follows:

<ol>

 <li>Student class</li>

</ol>

The purpose of Student class is to maintain the personal information of a student, i.e., the student name, the student number, the gender, and the date of birth.

<ol start="2">

 <li>Subject class</li>

</ol>

The purpose of Subject class is to maintain a subject’s information, i.e., the subject name, the subject code, the credit point of the subject.

<ol start="3">

 <li>Major class</li>

</ol>

The purpose of Major class is to maintain the information of a major, i.e., the major name, and all major subjects.

<ol start="4">

 <li>Course class</li>

</ol>

The purpose of Course class is to maintain the information of a course (Bachelor of Computer Science), i.e., the course name, the core subjects of the course, the majors of the course, the elective subjects of the course, and the minimal credit points requirement of the course.

<ol start="5">

 <li>Enrolment class (primary class)</li>

</ol>

The purpose of Enrolment class is to help a student to enrol into the Bachelor of Computer Science course with the following steps in the main() method. i) to display the entire course structure to the student; ii) to ask the student to input the personal information (by using the Scanner); iii) to automatically enrol the student to all core subjects;

<ol>

 <li>to ask the student to select a major and automatically enrol the student to all subjects of the major;</li>

 <li>to ask the student to select sufficient elective subjects for reaching the minimal credit points requirement of the course, i.e., 144 credit points; vi) once the student enrols sufficient subjects to make up at least 144 credit points, the enrolment is completed. vii) to display the student’s final enrolment record.</li>

</ol>

Note: You can use the hardcode to create the course structure for the Bachelor of Computer Science. You can also assume the user’s inputs are always correct. See an example to create the course structure with the hardcode in the main() method.

See the snapshots of an example for the program testing. Your program must have the exact same outputs for the same inputs. The user’s inputs are highlighted by blue colour, my explanations (not the inputs or outputs) are highlighted by green colour. The watermark is used to prevent the snapshots are used in your solution. You must capture the snapshots of your own program’s outputs.

<strong>Big Data Major  Cores:  </strong>




<h2>Tasks</h2>

Task 1 Complete the program design by using the UML class diagrams. The class diagrams shall

<ul>

 <li>contains at least the five classes mentioned above;</li>

 <li>contains class name, fields and methods definitions for each class;</li>

 <li>use correct and sufficient UML notations;</li>

 <li>clearly specify the associations between classes;</li>

 <li>clearly specify the multiplicities for both sides of the associations.</li>

</ul>

Task 2 ( Implement the system according to the UML class diagrams. The program shall

<ul>

 <li>be consistent with the UML class diagrams;</li>

 <li>follow the conventions for naming all classes, variables, and methods;</li>

 <li>provide sufficient comments;</li>

 <li>use proper blank spaces, indentation and braces to make your code easy to read and understand;</li>

 <li>follow the specified steps in Enrolment class to enrol the student into the Bachelor of Computer Science course;</li>

 <li>be able to automatically calculate the remaining elective subject number for the minimal credit points requirement.</li>

</ul>

Task 3: Compilation and test. You should compile and test your program by using two different cases. The first testing case must use the exact same inputs in the example. The second testing case must choose different majors and elective subjects. Please carefully compile and test your program and make sure your program can pass the compile by using “javac” command. Please do not define the package in your program (a special alert for students who use IDE to complete the assignment).


