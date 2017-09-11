---
title:  "New Login System"
image: new_login.png
tag: [Android, CodeCar]
---

Lately I’ve been working on new login system secured and connected to my database to register user and update their information

The new login system uses:

*   Use PHP PDO for working with MySQL database which is more secure and prevents SQL injection.
*   Hash password using default PHP BCRYPT algorithm instead of SHA.
*   JSON input instead of form urlencoded data input.
And much more...

The login screen where user can login, sign up or request for forgotten  password.

![CodeCar New Login](/images/new_login/1.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

If user is registered and logs in go to Profile Screen he will see his information.

![CodeCar New Login](/images/new_login/2.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

If user wants to change password

![CodeCar New Login](/images/new_login/3.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

Or First time user complete the fields to register in CodeCar

![CodeCar New Login](/images/new_login/4.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

It gave me error because im already registred to CodeCar

![CodeCar New Login](/images/new_login/5.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

Inside look in the CodeCar database 

![CodeCar New Login](/images/new_login/6.jpg "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

If user forgot his password it'll send an email contain a verification  code and user have to use it within an hour to change his/her password

![CodeCar New Login](/images/new_login/7.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

Then an email is sent to that account if found in our DB with the code to change the password

![CodeCar New Login](/images/new_login/8.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

Email contain the password reset code

![CodeCar New Login](/images/new_login/9.png "CodeCar New Login"){: .img-responsive .thumbnail  .max-image-height}

That's all for now, if you have any comment please tell us below.