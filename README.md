# Eiancoder_Tasks

## The flow of Task1:

    index.html:
      Has the form with the upload file option.
    display.php:
      Has a table which shows the data in the databse with two option
      Update and Delete
    update.php:
      On the basis of the id the data will be pulled from the database
      and we are able to change the values of the email id
    update_back.php:
      This is for the updation of the email id and makes the changes in the databse.
    delete.php:
      This will run the query on the basis of the id and then delete the data in the databse.

## The flow of Task2:
        
    The files are sel-explanatory.
    The structure is like:
        1. signup.php
            Form with the password validator on its backend
            Conditons are:
                a.Min len 8
                b.One lowercase char
                c.One uppercase char
                d.One number
        2. login.php
            Has a form for email and pass
        3. signup_back.php
            inserts the data in the php with the backend validator 
        4. login_back.php
            creates a session
        5. logout.php
            destroys the session
            
## The flow of Task3:
    
    The url in which we can see the table of the images.
    http://localhost/Task3/
    As we have already changed the name of the default_controller to the home page
    so we are directly gonna go on that page.
   
## The flow of Task4:
    
    The goal of this task was to make a CRUD application and to display
    all the data from the database on the same page, with the updatate and delete buttons.
  
    We are using User.php as the model and the Usermodel.php as the one which deasl with
    the data base.
    This is the url http://localhost/Task4/user/create

## The flow of Task5:

    I've made the SB Admin from bootstrap into a template which is available in CI.

## The flow of Task6:
    
    I've made a login and signup connection with the database and will also give out
    the results in flashdata and will be displayed in h5 of both of them
    lorem@ipsum.com:test [INSERTED USER]
    If needed you can insert the values after importing the database

## The flow of Task7:

    Default landing page is the own_form page and we are getting the form with email,pass
    and info as the params and we are inserting the data in the table. In the side bar there
    are both the form as own_form and the table as own_table in which we are displaying the whole
    database entries.

## The flow of Task8:
    The login is test@test.com:test or lorem@ipsum.com:1234 and then and then only we are able to
    to access the admin page and else we are redirected to the login page. We have the logout option
    in the navbar and we will be deleting the session on the click of that button.

## The flow of Task9:
    The config file base url must be changed first of all and then the own_table must be visited then we
    can edit the form or the data which has already been inserted.

## The flow of Task10:
    The config file must be updated to the correct path!
    We have put js function for the confirmation of the delete part and only if we click on confirm the 
    the data is deleted else nothing else happens.

## The flow of Task11:
    The tasks user/maps has the map of india and the default page of this will have the form for the
    number and then will be redirected and the otp_confirm and then we will get the otp value from the 
    user.