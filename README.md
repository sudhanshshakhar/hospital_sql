Queries-

* Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)

* **Update the patients table for the allergies column. If the patient's allergies is null then replace it with 'NKA' 
update patients
	Set allergies='NKA'
        where allergies is null; 

* Show first name and last name concatinated into one column to show their full name.

* Show first name, last name, and the full province name of each patient.

* Show how many patients have a birth_date with 2010 as the birth year. 

* Show the first_name, last_name, and height of the patient with the greatest height.

* Show all columns for patients who have one of the following patient_ids: 1,45,534,879,1000

* Show the total number of admissions

* Show all the columns from admissions where the patient was admitted and discharged on the same day.

* Show the patient id and the total number of admissions for patient_id 579. 

* Based on the cities that our patients live in, show unique cities that are in province_id 'NS'?

* Write a query to find the first_name, last name and birth date of patients who has height greater than 160 and weight greater than 70

* Write a query to find list of patients first_name, last_name, and allergies where allergies are not null and are from the city of 'Hamilton'

* Show unique birth years from patients and order them by ascending.

*  Show unique first names from the patients table which only occurs once in the list.
 For example, if two or more people are named 'John' in the first_name column then don't include their name in the output list. If only 1 person is named 'Leo' then include them in the output.


* Show patient_id and first_name from patients where their first_name start and ends with 's' and is at least 6 characters long. 

* Show patient_id, first_name, last_name from patients whos diagnosis is 'Dementia'.

* Display every patient's first_name. Order the list by the length of each name and then by alphabetically.

* *** Show the total amount of male patients and the total amount of female patients in the patients table. Display the two results in the same row.

* Show first and last name, allergies from patients which have allergies to either 'Penicillin' or 'Morphine'. Show results ordered ascending by allergies then by first_name then by last_name. 

* non-aggregate query??

* Show patient_id, diagnosis from admissions. Find patients admitted multiple times for the same diagnosis.

* Show the city and the total number of patients in the city. Order from most to least patients and then by city name ascending.

* Show first name, last name and role of every person that is either patient or doctor.
The roles are either "Patient" or "Doctor"

* Show all allergies ordered by popularity. Remove NULL values from query. 

* Show all patient's first_name, last_name, and birth_date who were born in the 1970s decade. Sort the list starting from the earliest birth_date.

*  We want to display each patient's full name in a single column. Their last_name in all upper letters must appear first, then first_name in all lower case letters. Separate the last_name and first_name with a comma. Order the list by the first_name in decending order EX: SMITH,jane */

* Show the province_id(s), sum of height; where the total sum of its patient's height is greater than or equal to 7,000.

*  Show the difference between the largest weight and smallest weight for patients with the last name 'Maroni' */

*  Show all of the days of the month (1-31) and how many admission_dates occurred on that day. Sort by the day with most admissions to least admissions. */

*  Show all columns for patient_id 542's most recent admission_date.*/

*  for only from admission table*/

*  Show patient_id, attending_doctor_id, and diagnosis for admissions that match one of the two criteria:
1. patient_id is an odd number and attending_doctor_id is either 1, 5, or 19.
2. attending_doctor_id contains a 2 and the length of patient_id is 3 characters. */

*  Show first_name, last_name, and the total number of admissions attended for each doctor.
Every admission has been attended by a doctor.*/

* For each doctor, display their id, full name, and the first and last admission date they attended.*/

*  Display the total amount of patients for each province. Order by descending.*/ 

* For every admission, display the patient's full name, their admission diagnosis, and their doctor's full name who diagnosed their problem.*/

* display the first name, last name and number of duplicate patients based on their first name and last name.*/
Ex: A patient with an identical name can be considered a duplicate.*/

* Display patient's full name,
height in the units feet rounded to 1 decimal,
weight in the unit pounds rounded to 0 decimals,
birth_date,
gender non abbreviated.

Convert CM to feet by dividing by 30.48.
Convert KG to pounds by multiplying by 2.205.*/ 

* Show patient_id, first_name, last_name from patients whose does not have any records in the admissions table. (Their patient_id does not exist in any admissions.patient_id rows.)*/ 













