# Project-2-Extending-the-JWKS-server
Running main.py will create a funtional JWKS server with RESTful API that can serv punlic keys with expiry and unique kid to verify JWTs backed by a SQLite database. The repo also contains a TestSuite.py file that tests the authentication of the server. It tests valid credentials, valid credentials with expired key and invalid credentials.
I used the project1 files given on the assignment as a base for the server and converted my Testsuite to use HTTP instead of Flask app.
