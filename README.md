# Login-Page-for-Websites
You can sign up by creating new username and password. Later on, you can login using the correct login credentials.

Registration:
Username:

When the user chooses to Register,
---> email/username should have "@" and followed by "."
      eg:- sherlock@gmail.com
---> it should not be like this 
       eg:- @gmail.com
---> there should not be any "." immediate next to "@"
       eg:- my@.in
---> it should not start with special characters and numbers
       eg:- 123#@gmail.com

Password: 

---> password (5 < password length > 16)
     Must have minimum one special character,
     one digit,
     one uppercase, 
     one lowercase character. 

Saving the Data:

Once the username and password are validated, the data will ne stored in a file.

Login:

When the user chooses to Login, it will be checked whether his/her credentials exist in the file or not, based on the user input. 
If it doesn’t exist then they will be asked to go for Registration. (or) 
If they chose forget password, their original password will be retrieved based on their username provided in the user input. (or)
A new password can be provided. 
(only if their username matches with the data that exists in the file)
If nothing matches in the file you will be guidednto Registration.
(Since they don't have an account)
