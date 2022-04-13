# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

### PaSS Project

Step 1: Sign-Up in Heroku with student id enter deatail as first name ,last name , select as a student verify   email id and set password.

Step 2 : Create new App in Heroku with new give the app name Passsign and app created successfully.

Step 3: Create new repository in github with name PassAssign and upload the all files provided in zipped folder in repository.

Step 4:  Open Heroku and connect to github account using password and id of github search for the repository created for project.

Step 5: Select the folder passAssign and select the option Enable automatic deploy then start deploy shows error as deploy failed disconnect from github to make changes.

Step 6 : Change a ruby version in gem filefrom 2.7.0 to 2.6.6 save the changes and upload to github.
	Again connect to github and start again the deployment and finally deployment successful.

Step 7 : Next, Run the command in console heroku run rake db:migrate and run suceesfully.
Step 8: Run another command in console heroku run rake db:seed to seed data in database created recently.

