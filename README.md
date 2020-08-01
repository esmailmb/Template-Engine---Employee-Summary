# Employee Summary Template Engine

This app helps user to generate and display Employee summary sheet in HTML

# Installation
---
Run `npm install` to install all required dependencies 


# Folder Structure
lib = classes and helper code
output = rendered output
templates = HTML template(s)
test = jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js = Runs the application

# Usage
---
1. Run `node apps.js` for app to start
2. Enter the number of users within your team
3. Enter the employees name > `ENTER`
4. Enter the employee's ID > `ENTER`
5. Enter the employee's email > `ENTER`
6. Select the employee's title > `ENTER`
7. If you selected Engineer, input their GitHub. If you selected Manager, input their office number. If you selected Intern, input their school
8. Repeat for all employees until you see the "Success!" notification. 

    ![](images/Run.gif)

9. you can see `team.html` in output folder 

    ![](images/output.png)

## Tool & Resources
---
* [Bootstrap](https://getbootstrap.com/) - CSS framework used
* [Node.js](https://nodejs.org/en/) - JavaScript runtime environment

    ### Dependencies
    ---
    * [Inquirer](https://www.npmjs.com/package/inquirer) - for the CLI user interface. This will prompt user within the CLI for employee information.

## Running the Test
---
run `npm run test` in the root

#  Challenges

It is difficult to figure out how to run app.js and collect all data from other files and generate final html.



