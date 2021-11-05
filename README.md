# Week9

IDOR
Here the id field in the salesperson tab can be used to access objects that are not meant to be accessed
The example shown here is the id 11 where the person is fired and is not meant to be public

SQLI
This attack uses the ID field in the salesperson tab to inject SQL commands into the database.
Here the command added is to sleep for 5 seconds, it is encoded in URL as well as it is sent via the URL
Command used: %27%20OR%20SLEEP(5)=0--%27

XSS
This attack uses the Feedback tab and the comment field to inject javascript code.
The field is not cleaned before accepting resulting in the javascript code being allowed and being executed along with the existing HTML

User Enumeration
Here the error seen when the username is present in the database and when the user is not present is different.
In the former the error message "Log in was unsuccessful" is in BOLD
while in the later, it is not in bold.
