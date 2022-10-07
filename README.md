# SEIR-808 Project 3

It's 1999, and blogging is the coolest new trend on the world wide web! You've been hired to create a blogging platform for the 21st century.

## User Stories

* As an unregistered user, I would like to sign up with email and password.
* As a registered user, I would like to sign in with email and password.
* As a signed in user, I would like to change password.
* As a signed in user, I would like to sign out.
* As an unregistered user, I would like to see all users blog posts.
* As an unregistered user, I would like to see comments on those blog posts.
* As a signed in user, I would to create blog posts.
* As a signed in user, I would to comment on other users' blog posts.
* As a signed in user, I would to update my blog posts and comments.
* As a signed in user, I would to delete my blog posts and comments.

## Wireframes

<!-- Wireframes here -->

## ERDs

<!-- ERDs here -->

## RESTful Routes

| HTTP METHOD | URL              | CRUD    | Response                              |
| ----------- | ---------------- | ------- | ------------------------------------- |
| GET | `/users/:id` | READ | return a specific user as json (status 200) |
| POST | `/users` | CREATE | create a user in the database and send back as json (status 201) |
| PUT | `/users/:id` | UPDATE | update a user in the database and send back as json (status 200) |
| DELETE | `/users/:id` | DESTROY | delete a user from the database (status 204) |
| GET | `/courses` | READ | return all courses as json (status 200) |
| GET | `/courses/:id` | READ | return a specific course as json (status 200) |
| POST | `/courses` | CREATE | create a course in the database and send back as json (status 201) |
| PUT | `/courses/:id` | UPDATE | update a course in the database and send back as json (status 200) |
| DELETE | `/courses/:id` | DESTROY | delete a course from the database (status 204) |

## MVP goals

<!-- MVP goals here -->

## Stretch goals

[ ] Let users leave ratings on courses
[ ] Let users follow other users
