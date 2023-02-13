User authentication service

file description

0. In this task you will create a SQLAlchemy model named User for a database table named users (by using the mapping declaration of SQLAlchemy).
1. In this task, you will complete the DB class provided below to implement the add_user method.
2. In this task you will implement the DB.find_user_by method. This method takes in arbitrary keyword arguments and returns the first row found in the users table
3. In this task, you will implement the DB.update_user method that takes as argument a required user_id integer and arbitrary keyword arguments, and returns None
4. In this task you will define a _hash_password method that takes in a password string arguments and returns bytes.
5. In this task, you will implement the Auth.register_user in the Auth class provided below:
6. Create a Flask app that has a single GET route ("/") and use flask.jsonify to return a JSON payload of the form:
7. Create a Flask app that has a single GET route ("/") and use flask.jsonify to return a JSON payload of the form:
8. In this task, you will implement the Auth.valid_login method. It should expect email and password required arguments and return a boolean.
9. In this task you will implement a _generate_uuid function in the auth module. The function should return a string representation of a new UUID. Use the uuid module.
10. In this task, you will implement the Auth.create_session method. It takes an email string argument and returns the session ID as a string.
11. In this task, you will implement a login function to respond to the POST /sessions route.
12. n this task, you will implement the Auth.get_user_from_session_id method. It takes a single session_id string argument and returns the corresponding User or None
13. In this task, you will implement Auth.destroy_session. The method takes a single user_id integer argument and returns None.
14. In this task, you will implement a logout function to respond to the DELETE /sessions route
15. In this task, you will implement a profile function to respond to the GET /profile route.
16. In this task, you will implement the Auth.get_reset_password_token method. It take an email string argument and returns a string
17. In this task, you will implement a get_reset_password_token function to respond to the POST /reset_password route.
18. In this task, you will implement the Auth.update_password method. It takes reset_token string argument and a password string argument and returns None.
19. In this task you will implement the update_password function in the app module to respond to the PUT /reset_password route.
20. Create a new module called main.py. Create one function for each of the following tasks. Use the requests module to query your web server for the corresponding end-point. Use assert to validate the response’s expected status code and payload (if any) for each task.
