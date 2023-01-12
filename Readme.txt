This is the 5 factor authentication project which I did for my Supervisor to assist with his thesis.
Since this is published work, I cannot provide the code without his prior permission.


Explanation
All fields are verified against a database
1. The registration page which registers user credentials into the database
2. Login Page which receives and verifies the Username and password
3. The OTP pages sends a random number request to the server to the phone number for the specific profile
4. The fingerprint form receives and verifies the User's fingerprint.
5. The Device Page checks the MAC address of the device and verifies it against the database.
6. The location page verifies that the user is at the registered location.
	If the user is not at the location the page checks how far the user is from the location
	If the user is within a specified radius to the location the final registration step success
	if not the final registration step fails