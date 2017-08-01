# raspberry-pi-webserver
We are using a raspberry-pi to create a web-server and this repository will include the steps we took to make it.

What is a Webserver?

A webserver can refer to either software, hardware or a combination of the two working in unison. A web server is a computer that stores a websites in the form of documents and data, including HTML files, images, videos, etc and renders them to users when they are requested. 

First, a user, through their browser, and sends a request to the server to access a particular website. This is done by typing "mozilla.org" into the search bar, and pressing enter. 

There are 2 basic components to the client/server model that a webserver employs:

On the hardware side, a web server is a computer that stores a website's component files (e.g. HTML documents, images, CSS stylesheets, and JavaScript files) and delivers them to the end-user's device. It is connected to the Internet and can be accessed through a domain name like mozilla.org.

On the software side, a web server includes several parts that control how web users access hosted files, at minimum an HTTP server. An HTTP server is a piece of software that understands URLs (web addresses) and HTTP (the protocol your browser uses to view webpages).
At the most basic level, whenever a browser needs a file hosted on a web server, the browser requests the file via HTTP. When the request reaches the correct web server (hardware), the HTTP server (software) sends the requested document back, also through HTTP.

When a browser wants to load or retrieve a particular file hosted on a web server, the browser requests the file via HTTP (software aspect). The request will then reach the physical server, and the software server, HTTP, will send the document back and it will get rendered on the page.

Benefits of having your own web-server:
You can control your own data.
You don't have to pay for hosting.
You'll get street credit.
Educational resource.

STEPS:

1) First, make sure the Pi is set up (read separate setup instructions in "PI-SETUP" repo)
2) Connect to the internet using an ethernet cable, or just using a wifi network.
3) Open the terminal, and type in *sude apt-get update* to update your Pi
4) Install Apache MySQL, MyPHP admin, using: *sudo apt-get install apache2 php5 mysql-server mysql-client*
5) Go to your browser, and type in the IP address of the Pi in the search bar.
6)

