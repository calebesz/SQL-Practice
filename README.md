# SQL-Practice
Portfolio usando a plataforma www.sql-practice.com/ com a base de dados hospital, variando desafios fáceis, médios e dificeis

Escolhi 5 perguntas de cada nível para demonstrar meu conhecimento de forma uniforme.

<strong>Schema do Banco de Dados</strong>


![image](https://github.com/user-attachments/assets/32fe4f08-b85f-40f8-b9ae-e506c09db432)


<h2>Questions - Easy</h2>

1 - Write a query to find list of patients first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'

![image](https://github.com/user-attachments/assets/989e2817-e3fb-4b0e-9326-eaa36f9e4214)


2 - Write a query to find the first_name, last name and birth date of patients who has height greater than 160 and weight greater than 70

![image](https://github.com/user-attachments/assets/96b187fc-2582-4b23-8909-7bfe26a695f5)


3 - Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)

![image](https://github.com/user-attachments/assets/6518a7c8-fdf7-4176-90e6-33ceec277e3a)


4 - Based on the cities that our patients live in, show unique cities that are in province_id 'NS'?

![image](https://github.com/user-attachments/assets/e51afe59-5b27-4eee-8434-aad4792d4350)


5 - Show first name and last name of patients who does not have allergies. (null)

![image](https://github.com/user-attachments/assets/af25f530-e234-44e8-8942-d0c6de51b89a)



<h2>Questions - Medium</h2>

1 - Show patient_id, first_name, last_name from patients whose does not have any records in the admissions table. (Their patient_id does not exist in any admissions.patient_id rows.)

![image](https://github.com/user-attachments/assets/9a548c47-8a58-46a2-84a9-399e4584832a)


2 - Show patient_id, first_name, last_name from patients whos diagnosis is 'Dementia'.

![image](https://github.com/user-attachments/assets/5a4b6b48-3cfa-4aa9-a7c1-b209dc0f1628)


3 - Show all patient's first_name, last_name, and birth_date who were born in the 1970s decade. Sort the list starting from the earliest birth_date.

![image](https://github.com/user-attachments/assets/b5e154ca-7083-46e0-b8de-7ecd50449dcc)


4 - Show first and last name, allergies from patients which have allergies to either 'Penicillin' or 'Morphine'. Show results ordered ascending by allergies then by first_name then by last_name.

![image](https://github.com/user-attachments/assets/577e6227-2e57-4140-8f75-91282ccf0c64)


5 - For every admission, display the patient's full name, their admission diagnosis, and their doctor's full name who diagnosed their problem.

![image](https://github.com/user-attachments/assets/82ec4855-9946-416a-b622-6731586ba984)



<h2>Questions - Hard</h2>

1 - Show all of the patients grouped into weight groups.
Show the total amount of patients in each weight group.
Order the list by the weight group decending.

![image](https://github.com/user-attachments/assets/f65108cd-8728-46d0-9593-643ac258b8ae)


2 - All patients who have gone through admissions, can see their medical documents on our site. Those patients are given a temporary password after their first admission. Show the patient_id and temp_password.

The password must be the following, in order:
1. patient_id
2. the numerical length of patient's last_name
3. year of patient's birth_date

![image](https://github.com/user-attachments/assets/0352bd6b-feca-4718-8d9a-c0a56a2468d2)


3 - Sort the province names in ascending order in such a way that the province 'Ontario' is always on top.

![image](https://github.com/user-attachments/assets/86b29c39-ccc8-4b16-92c5-ac753b07b87f)


4 - Show the percent of patients that have 'M' as their gender. Round the answer to the nearest hundreth number and in percent form.

![image](https://github.com/user-attachments/assets/fcb53058-ea3a-48da-a1b3-b122cc474208)


5 - 
Show all of the patients grouped into weight groups.
Show the total amount of patients in each weight group.
Order the list by the weight group decending.

For example, if they weight 100 to 109 they are placed in the 100 weight group, 110-119 = 110 weight group, etc.

![image](https://github.com/user-attachments/assets/6c2853eb-56a5-432f-9910-a490b7797105)





