# To build this project, need to follow the steps below:

1.  go to your github repositories page

2.  click the "NEW" button

3.  give a name for your project

4.  upload the project that you already did

5.  add a file and name it "Procfile"

6.  add the following code to "Procfile" file

      web: vendor/bin/heroku-php-apache2 ./
    
7.  add a file and name it "composer"

8.  add the following code to "composer" file
  
      {}
  
9.  go to your project settings page on your github

10. change the "Source" to master branch, and save it

11. go to Heroku website and login

12. click "Create new app" button

13. give your app a name and choose a region

14. choose GitHub as your deployment method

15. find your project in your github and press "Connect"

16. press the "Deploy Branch" button

17. press "View" button down the page to check if it is successfully deployed 
