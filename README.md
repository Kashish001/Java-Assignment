Question : Write a program to create following scenario:
A class Person having :
private field : name  to store name of person
abstract method : void display()  which will be used to display details of person Use parameterized constructor to initialize these attributes. Make setter & getter methods for the attribute.
Make a class Employee which inherits Person class and having : private field: id  to store id of employee
date_of_join to store joining date of employee
Use a parameterized constructor to initialize these attributes. Make setter & getter methods
for the attributes also.
Now make a class Test having main() method in which you have to create at least 6 Employee objects and store them in ArrayList. Make another method named serializeObjects() in the same class which will read all the employee-objects from the ArrayList and serialize all those employee-records (in file “records.txt”) whose date of joining is before the year 2015.
Now make another method named deserializeObjects() in the same class which will read and display all the records from the file.
Note: Don’t make any separate instance variable other than the ones specified in above scenario. Also date_of_join variable is to be taken as LocalDate object rather than String object. Also, make use proper exception handling by using inbuilt exception-classes and also make your own custom exception class to deal with the exceptions such as users entering a negative no.
