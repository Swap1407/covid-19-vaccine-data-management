# covid-19-vaccine-data-management
A basic Data management system created using Data Structure (Singly Linked List) in c++.
INTRODUCTION

The project “Covid-19 Vaccination Management” is developed in C++. The system includes registration of patients depending upon the available number of vaccines in the center. Also, the system has facility to search a particular patient by their Names, Mobile Number, Aadhar Number and Age. Also, we have given a provision to display all patients list with their details who have been vaccinated.  All these operations are performed using a Singly linked list.

Nowadays, there is too much load on hospitals and covid-19 centers for vaccination and it has become difficult to keep track of patient’s records. So, covid-19 vaccination management system enables us to develop our organization and improves its effectiveness and quality of work.  This system is flexible and easy to use and is designed and developed to deliver real conceivable benefits. 


 

IMPLEMENTATION
Software Used: Dev C++ 5.1
Language Used: C++
Compiler: TDM GCC 4.9.2 64-bit Release
Data Structure Used: Linked List(Singly)
Operations Performed: Add, Delete, Display

ALGORITHM:
1.	Start
2.	Add vaccines
3.	Display the options:
i.	Add Patient Data.
ii.	Display Patient Data.
iii.	Search Data
4.	For adding patient’s data:
A.	Add New Entry:
I.	Declare a pointer temp of type node and add the data to it and set next field as NULL as it would be last node of list
II.	Check if list is empty if (head == NULL), then set head and tail as temp
III.	If list is not empty, link newly created node with tail node tail->next = temp (it will pass address of new node to next pointer of tail node)
IV.	Set tail pointer to new node as tail pointer should always point to last node tail = tail -> next. 
iv.  Delete last Entry:
I.	Check whether list is Empty (head == NULL) 
II.	If it is Not Empty then, define two Node pointers 'temp1' and 'temp2' and initialize 'temp1' with head
III.	Check whether list has only one Node (temp1 → next == NULL) and set head = NULL and delete temp1
IV.	If not then, set 'temp2 = temp1 ' and move temp1 to its next node. Repeat the same until it reaches to the last node in the list. (until temp1 → next ==NULL)
V.	Set temp2 → next = NULL and delete temp1
5.	To view data:
A.	Add new Vaccine:
I.	Take input and store as the number of vaccine stocks from the user
II.	Display the vaccine stock by printing the integer
B.	View available number of vaccines.
C.	View all data:
I.	Define node pointer temp and pass address of head node to it.
II.	Check whether list is empty If (temp == NULL) 
III.	If not print data in current temp
IV.	Set temp = temp -> next to traverse in list
V.	Repeat step 3,4 until (temp == NULL) 
6.	To search data: -
I.	Define node pointer temp and pass address of head node to it.
II.	Check whether list is empty If (temp == NULL). 
III.	If list is not empty check condition for matching (name, Aadhar no, mob no, gender, age), if matched print data.
IV.	Set temp = temp -> next to traverse in list.
V.	Repeat step 4,5 until (temp == NULL) .
7.	Exit.
















FLOWCHART:
 



















Testing and Results:
Testing a program consists of providing the program with a set of test inputs (or test cases) and observing if the program behaves as expected. If the program fails to behave as expected, then the conditions under which failure occurs are noted for later debugging and correction.
 
This is result after compiling our program with no errors and warnings.
 
This is Home Screen (Run Window) of our program.
Time Complexity of Singly Linked List:

Operation	Best Case	Worst Case
Get ()	O (1)	O(N)
Insert ()	O (1)	O(N)
Search ()	O (1)	O(N)
Delete ()	O (1)	O(N)





CONCLUSION AND FUTURE ENHANCEMENTS

In conclusion, we would like to thank our faculty for giving us this opportunity out of which we tried to comprehend as much as possible and learnt about various data structures. Not only that, but we were successfully able to implement this project of Covid-19 Vaccination Management using Linked List which is one of the many data structures.
We developed a covid-19 record management system for hospitals and covid centers using data structure Linked List. This system makes user simpler way to keep information of vaccines and patients.  This system deals with menu driven program showing patient data, vaccine data, search data and exit making it comfortable to operate.  So, it will definitely help in current scenario of pandemic situation where vaccination process has been started. 
There is always room for improvement, and this fairly applies to our project too. With more time, the system can be improved by adding options like saving previous data using file handling.
