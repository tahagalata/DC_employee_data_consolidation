# DataCamp Project: Consolidating Employee Data
## Project Instructions
The Head of People Operations wants a general view of all available employee information.
Your job is to gather all employee data and store in a pandas DataFrame called employees_final, which will serve as the reference moving forward.

In order to complete the project you will need to:

* Read in and merge the four datasets.
* Change any NaN values in column names starting with office to the word "Remote".
* Set the index of the DataFrame to employee_id.
* Produce a final DataFrame called employees_final containing:
* Index: employee_id,
* Columns: first_name, last_name, employee_country, employee_city, employee_street, employee_street_number, emergency_contact, emergency_contact_number, relationship, monthly_salary, team, title, office, office_country, office_city, office_street, office_street_number.

## Project & Data Details:
You just got hired as the first and only data practitioner at a small business experiencing exponential growth. The company needs more structured processes, guidelines, and standards. Your first mission is to structure the human resources data. The data is currently scattered across teams and files and comes in various formats: Excel files, CSVs, JSON files...

You'll work with the following data in the datasets folder:

Office addresses are currently saved in office_addresses.csv. If the value for office is NaN, then the employee is remote.
Employee addresses are saved on the first tab of employee_information.xlsx.
Employee emergency contacts are saved on the second tab of employee_information.xlsx; this tab is called emergency_contacts. However, this sheet was edited at some point, and the headers were removed! The HR manager let you know that they should be: employee_id, last_name, first_name, emergency_contact, emergency_contact_number, and relationship.
Employee roles, teams, and salaries have been exported from the company's human resources management system into a JSON file titled employee_roles.json. Here are the first few lines of that file:
