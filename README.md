# Creating-Functions-to-Register-App-Users

Create a validate_user() function, using some helper validation functions to validate user input.

The function should take in the parameters: name, email and password.
The function should call each of the helper validation functions and raise a ValueError with a descriptive error message if any of the inputs fail validation.
If all of the checks pass, the function should return a Boolean value of True.
Now that you've validated that all the user details are correct, you want to allow users to register to the app. Create a register_user() function that registers the user if all checks pass.

The function should take in the parameters: name, email and password.
The function should call validate_user() to ensure that the user input is valid.
If all checks pass, the function should create a dictionary with the keys: name, email, password.
The function should return the new user dictionary, or the boolean value of False.