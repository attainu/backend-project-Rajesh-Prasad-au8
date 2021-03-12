This Project focuses on admin and employee's signup and login operations with proper authentication.
For session management JWT token is used.


Code editor: Visual studio code
Language used: HTML, CSS, javascript
DataBase: mongodb
DBMS: mongodb atlas
code manager: github
Deployed on: heroku


Description:
/homepage => this is the homepage of our project. You can login here if you are already an admin or employee.
Or an admin can signup here as well.
admin will be redirected to /allusers page
whereas employee will be redirected to his page where he/she can view all the details.

/signup => this route will let you signup as admin

/alladmin => this route will let the admin see all the admins at one page.

/allusers => this route will let the admin see all the users at one page.

/employee => this route will let the admin add details of a employee

/alladmin/:email => this router will let the admin see all details of any single admin

/allusers/:email => this router will let the admin see all details of any single employee

/logout => this route will clear the session and make you logout of the session

How to run:
1. clone it in your local harddrive
2. navigate to the folder
3. use the command npm install 
4. use npm run dev
