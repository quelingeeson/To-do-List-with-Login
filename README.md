# To-do-List-with-Login
In this project ,I have created a website called "to do list".  This website is made using python, flask, and sqlite database and sqlalchemy.IDE used:Visual Studio Code  It is a simple website designed to make your personalised to-do list for your daily routine. The site  also removes the schedule items from list once the work has been completed.

Firstly, a user has to create his or her account to access his personal to do list.

This can be done by registering the user.
On clicking the register button, a form page opens up where the user has to provide his or her unique username and email,
along with the password and confirm password.

A user gets registered succefully if they provide valid credentials.

All the user data is stored in a database.

The user can now login using his or her email and paasword.

On successful Login, the user is redirected to their homepage.

In the homepagewe , we have a form in which the user can type in the items which he/she wants to add to their schedule.
At first , since this is a new user,  the list will be empty.

The work to be completed can be added to the list using the form and by pressing the add button.

It also provides the date and time at which the task was added so that the user can keep track of the schedule.

The list also has the option to strike off the task once it's completed by pressing the complete button.

Also, the user can delete the completed tasks from the list by clicking the delete button.
The list gets reordered as per the number of tasks left on the list.

In this way, every user can maintain his/her personal to-do-list and keep a check of their schedule for the day.

The account button on the page displays the username and email details of the user.

The about button displays the features of the website and the home button redirects to the homepage of the to-do-list.

Once the user is done using the website, he or she can logout using the log out button.

All the entries in the to-do list of the user will be saved in the users database so that the user can access the list whenever they log in
