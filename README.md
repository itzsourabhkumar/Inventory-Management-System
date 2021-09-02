# Inventory-Management-System
Project Based On Management System Of COVID-19 Vaccine

Medicine -> COVID-19 Vaccine 🧑
<br/>
Objective of MMS->Medicine Management System::
<br/>
In this Inventory our main objective are booking slotes for vaccination by selection your state code which are given to you and after booking update our Medicine-data.txt file.
<br/>
Explanation Step by step::
<br/>

Step-1: In step 1 we are reading a file by using file handling read mode.
<br/>


Step-2: In step two we are making a list by using split function and print all the state name with their code's
<br/>

Step-3: In step 3 we are doing our main logic ::  
<br/>

1. of all we are taking State_id and age_of_person by user
<br/>

2. Loop through entire list and checking each and every state_id with state code
<br/>

3. If state found then check two condition 
<br/>

A. if(state_code == state_id and age_person >=18 and age_person < 45)
<br/>

B. if(state_code == state_id and age_person >=45 and age_person < 90)
<br/>

4. If condition match than Book NO.of condidates for vaccination and select One of the vaccine
<br/>
A.Covaxin
B.Covisheld
<br/>
     
5.If the vaccine are in stock than your booking is successful otherwise Vaxin out of stock.
<br/>

Step-4: This is the second last step of this project in which we are updating the value of vaccine and store it in a new List (Name of the list -> new_record = [])
<br/>


Step-5: IN last step we are writing the updated list in medicine-data.txt file
<br/>

Hope you like it!


