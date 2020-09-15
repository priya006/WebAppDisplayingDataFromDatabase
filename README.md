# WebAppDisplayingDataFromDatabase
Display Data from MySQL database table in Node.js.

# How to get the Project Folder Straucture
------
Run the command `npx express --view=ejs myapp`to get Basic Project Structure

# Steps
--------
1. Make sure the local MySQL Server is up and running 
2. Make sure there is data in the database `DataTool` and there are data added to the table `people`
3. CD to `myapp` folder. `Start the node js server `node app.js`
4. Add more data to the table `userstable`. Using **Mysql Work Bench** SQL client. 
5. From browser `http://localhost:5000/user/user-list`
6. From Postman type `http://localhost:5000/user/user-list` to see the data embeddedd in html


