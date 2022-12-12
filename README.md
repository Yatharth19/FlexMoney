This is a simple web application which registers members in the monthly organized Yoga Classes.

Only people within the age limit of 18-65 can enroll for the monthly classes and they will be paying the fees on a month on month basis. 
They can enroll any day but they will have to pay for the entire month. The monthly fee is 500/- Rs INR.
There are a total of 4 batches a day namely 6-7AM, 7-8AM, 8-9AM and 5-6PM. The participants can choose any batch in a month and can move to any other batch next month.

While preparing this project, a few assumptions were made which are as follows.


1. A single member can register only once using their phone number.
2. A user can change the slot alloted to them for the next month, multiple times.
3. A new member must register into the system for the first time only.
4. In subsequent visits, they can use the login functionality to see and modify their details.
5. Currently, the pay fees button is disabled.


Functionality Related:
1. The user first registers themselves using phone number as a primary key.
2. This stage also checks for the user's age and displays an appropriate message if age is not as expected.
3. After registering, the user is directed to their dashboard.
4. At the dashboard, all the information regarding the user is shown.
5. Also, their is an option present to change the batch for the next month of the current user.
6. Returning users can login into the system using their phone number and password.
7. After login, the users are directed to their dashboard.
8. SQL database was used.
9. Two tuples were created for the member information and the next month's batch information for every member.


Node js was used in the backend along with ejs templates in the frontend.
The project was deployed on render.com

The full deployed project can be found here: https://yogaregisteration.onrender.com/

**E-R Diagram**
![image](https://user-images.githubusercontent.com/59289916/207110187-29a55ab0-b482-4705-9368-cbd1cfd87787.png)
