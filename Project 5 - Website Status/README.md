URL Status Checker
This Python script checks the status of a given URL by making an HTTP GET request and displaying relevant details such as the status code, content type, server information, and response time. It helps quickly assess the availability and performance of a website or web service.

Features
URL Status: Displays the HTTP status code (e.g., 200 OK, 404 Not Found).
Content-Type: Displays the content type (e.g., text/html, application/json).
Server Information: Displays the server information (e.g., Apache, Nginx).
Response Time: Measures and shows the response time in seconds.
Error Handling: Catches request exceptions (e.g., network issues, invalid URL) and displays appropriate error messages.

How to Use
Run the Script: Execute the script in a Python environment.
Set URL: In the main() function, change the value of url_to_check to the URL you want to check.
Check the Output: The script will display the following details for the URL:
HTTP status code
Content type
Server information
Response time

Example
For the URL https://www.indently.io, the output might look like:
URL: https://www.indently.io
Status Code: 200
Content Type: text/html; charset=utf-8
Server: nginx/1.18.0
Response Time: 0.56 seconds
If the URL is unreachable or if there is an error, the script will print the corresponding error message, such as:

Error: HTTPConnectionPool(host='www.indently.io', port=80): Max retries exceeded with url: / (Caused by NewConnectionError('<urllib3.connection.HTTPConnection object at 0x7f50d1f91100>: Failed to establish a new connection: [Errno -2] Name or service not known'))

Requirements
Python 3.x
requests library (You can install it with pip install requests)
