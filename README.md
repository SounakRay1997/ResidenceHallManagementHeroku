# Residence Hall Management System

Project for the Introduction to Databases Course at Columbia University. 

The residents (or potential residents) can perform the following operations through the User Interface :

1. Applicants can raise an application for admission to the residence hall and they become Residents when approved by the Admissions Department.
2. Residents can raise various Financial Requests with the Finance Department.
3. Residents can raise various Task Requests with the Facilities Department.
4. Residents can look at their current pending bill amount and pay it.
5. Residents can order food from the Dining Hall Services and also request a recharge of their dining hall credits through the Finance Office.

The employees can perform the following tasks through the User Interface :
1. The Admission Department can look at pending admission applications and approve them or reject them. If they approve the requests, they will also allocate room numbers.
2. Employees of the Finance Department will look at Financial Requests and approve them.
3. Employees of the Facilities Department will look at various service requests like Carpentry, Electricity etc. and update the status of these Task Requests.

Additional Features:
1. Auto approval for rent payment and recharge of dining hall credits by residents.
2. When the resident pays the rent the outstanding rent is set to 0 and if a resident has no outstanding rent amount, his rent payment request will be automatically rejected.
3. The resident won’t be able to order food from dining hall service if his dining credit is less than the bill amount.
4. When admissions approve an applicant to be a resident they will be able to see the list of rooms and also from what dates the room would be available.
5. When a vacant room is assigned the room’s vacant from date view is updated to the end date of resident’s stay.
6. All finance requests and task requests are managed by employees of specific departments and the employee’s view screen will be customized according to the tasks
assigned to them.
7. Residents will be able to view the task requests raised and the status of the task requests.

Interesting web-pages:
1. Resident page : The resident home page enables residents to raise new task requests as well as has navigation to the billing summary page where residents can view the payment history, outstanding rent and current dining hall credits, the page also navigates to task requests page to view the task requests and finance requests raised and their current status. The page also navigates to the order food page where residents can order food of their choice.
2. Employees Home page : Every employee will see a view depending on their department. Employees of the admission department can approve applicants and assign room
numbers as well as reject applicants. Employees of the finance department can approve finance requests and add updated amounts or reject pending requests. The employees of the Facilities department can update task priority and status of task completion.
