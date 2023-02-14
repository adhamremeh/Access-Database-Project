Project description: 
This project is a hospital database, we made tables in this database about (doctors, managers, branches, …Etc) to illustrate the information about everything in the hospital and the relations between them.









The Entity Relationship Diagram (ERD)

![Capture](https://user-images.githubusercontent.com/125047290/218610760-a669d71b-14a7-4115-81db-0c657281ba97.PNG)









Entities and it’s attributes description

Suppliers Table:
•	Medical supplier name: 
The name of the supplier company which provided the tool

•	Tools provided:
The tools which the supplier provided

•	Expenses Per Year:
The expenses spent on the tool annually		

Sections Table:
•	Section_name: 
name of the medical section

•	Section_address:
the address of that section in hospital






SEC_manager Table:
•	ID: 
Section manger Id

•	Sec_manger_fname:
Section manager first name

•	Sec_manger_lname:
Section manager last name	

•	mobile: 
Section manager mobile Number

•	mail:
Section manager mail

•	section:
Section that managed with each manager		

Rooms Table:
•	DR_room: 
Doctors’ id

•	Room_number:
Doctors Rooms’ number




Patients  Table:
•	ID: 
Patients ID

•	P_fname:
Patients first name

•	P_lname:
Patients last name	

•	DR_PA: 
doctor who is responsible for Patients

•	Age:
Patients Age

PA_ROOMS Table:
•	PA_room: 
room occupied by patient

•	Room_number:
Room number for every patient

•	cl:
Cleaner ID




Nurses Table:
•	ID: 
Nurse ID

•	Nurse:
Nurse name

•	Patient:
Patient ID

Medical tools Table:
•	Tool_name: 
The name of the medical instrument

•	use:
The use of this instrument

•	manufacturer:
the country that manufactured the tool	

•	Tool_Supplier: 
The tool supplier that provided the tool

Janitors Table:
•	ID: 
Janitor ID

•	Janitor:
Janitor Name
J_CL_ROOM Table:
   (Bridge table for many to many relation between janitors and rooms) 
•	R_ID: 
Room ID

•	J_ID:
Janitor ID

Doctors Table:
•	Doctor_ID: 
write each doctor's ID to be the primary key for this table

•	Doctor_Name:
write the name of each Doctor

•	section: 
write the section that the doctor is worrking in.

•	Doctor_Salary:
write the salary of each doctor

•	Branch: 
write in which branch does the doctor work





Branches Table:
•	B_ID: 
Branch ID

•	Address:
Branch Address

•	B_Manager_ID:
Every branch manager ID

Branch_Manager Table:
•	M_ID: 
Manager ID

•	Name:
Manager Name

•	Address:
Manager Home Address	

•	Salary: 
Manager Salary

