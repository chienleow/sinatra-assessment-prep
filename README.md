# Sinatra Assessment Prep 

## By ChiEn Leow, Alicia Reeves 

Project requirements checklist: 

Build an MVC Sinatra application. 

MVC: Model, View, Controller, provides a separation of concerns 

Use ActiveRecord with Sinatra. 

Use multiple models. 

Use at least one has_many relationship on a User model and one belongs_to relationship on another model. 

Must have user accounts - users must be able to sign up, sign in, and sign out. 

Validate uniqueness of user login attribute (username or email). 

Once logged in, a user must have the ability to create, read, update and destroy the resource that belongs_to user. 

Ensure that users can edit and delete only their own resources - not resources created by other users. 

Validate user input so bad data cannot be persisted to the database. 

BONUS: Display validation failures to user with error messages. (This is an optional feature, challenge yourself and give it a shot!) 

Review possible questions: 

Write a migration to modify an existing table (creating migration, creating new model, adding to schema, understanding the convention, relationships) 

Tux 

How to authenticate users, bycrpt, has_secure_password 

How objects are created, sending request (form), http verbs (post, patch) 

Routes are protected (users cannot edit/delete others) 

Difference between authentication (email, password) and authorization (what a user can do) 

What is ActiveRecord:Base? It builds all your macro methods for you. 

Write a helper method 

My Review (ChiEn): 

Sign up a user, show in browser then explain in code 

Try signing in as user, first try without entering a password, show error message, explain in code, can we use @user.password to check instead of @user.authenticate Why and why not? 

Successfully signed in, show CRUD in browser, then explain in code 

Dustin helped refactor code to use method .build 

Try editing and deleting other users' projects 

Create a new model, add table, make sure to include "foreign id" in another table that relates to this table. 

My Review (Alicia): 

1. Request/response flow 

What does that mean to you? 

How does a get request work, how does a post request work? What are the differences? 

2. Rendering vs Redirecting 

What does this mean to you? 

3. When logging in, I saw that you set a session[user_id] = @user.id 

What does this mean to you? What is the session in a Sintra app? 

4. has_secure_password 

What is it really? Read up on the lessons about bcrypt. (or, google bcyrpt and see if an article elsewhere explains it better than flatiron does) 

5. And of course, ActiveRecord 

What is it? What does it afford you? (its a little more than just writing SQL for you). See if you can watch some videos on the topic.  

6. Had me create a new object in Tux and associate it with a user. Then walked me 

through the .build method(as stated above) 

 

 
