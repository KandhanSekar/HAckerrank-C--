

This problem is to get you familiar with virtual functions. Create three classes Person, Professor and Student. The class Person should have data members name and age. The classes Professor and Student should inherit from the class Person.

The class Professor should have two data members: publications and cur_{id}. There will be two member functions: getdata and putdata. The function getdata should get the input from the user: the name, age and publications of the professor. The function putdata should print the name, age, publications and the cur_{id} of the professor.

The class Student should have two data members: marks, which is an array of size  and cur_{id}. It has two member functions: getdata and putdata. The function getdata should get the input from the user: the name, age, and the marks of the student in  subjects. The function putdata should print the name, age, sum of the marks and the cur_{id} of the student.

For each object being created of the Professor or the Student class, sequential id's should be assigned to them starting from .

Solve this problem using virtual functions, constructors and static variables. You can create more data members if you want.



Input Format



There are two types of input. If the object being created is of the Professor class, you will have to input the name, age and publications of the professor.

If the object is of the Student class, you will have to input the name, age and the marks of the student in  subjects.

Constraints 

, where  is the length of the name. 
 
 
, where marks is the marks of the student in each subject.



Output Format



There are two types of output depending on the object. 

If the object is of type Professor, print the space separated name, age, publications and id on a new line.

If the object is of the Student class, print the space separated name, age, the sum of the marks in  subjects and id on a new line.
