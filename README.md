Front end representation of Aggregated test cases and its time /Value graph.
#Creating SimpleHTTPServer 
Python 2
If you have Python installed...

Change directory into the folder where your file some.html or file(s) exist using the command cd /path/to/your/folder

Start up a Python web server using the command: python -m SimpleHTTPServer

This will start a web server to host your entire directory listing at http://localhost:8000

You can use a custom port python -m SimpleHTTPServer 9000 giving you link: http://localhost:9000
This approach is built in to any Python installation.

Python 3
Do the same steps, but use the following command instead python3 -m http.server
