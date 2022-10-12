Part One: Solidify Terminology
In your own terms, define the following terms:

What is HTTP?:
It is a defined as Hypertext Transfer protocol. Although there is HTTPS which is the secured version of the protocol. Protocol is how document are obtained from the web.

What is a URL?
Is defined as the Universal Resource Locator, in other words it is the address of the web page. It reference web pages such as HTTP, HTTPS, ftp etc. A URL for insance: http://somesite.com/some/page.html indicates a protocol (http), a host name (www.somesite.com) and a file name (page.html)

What is DNS?
Is the Domain Name System. It translate the domain name www.amazon.com to a machine readable IP addresses: 192.0.2.44.As a result the protocol(http) will be able to send the data packet to the right addresses.

What is a query string?
is the extra portion of the URL where data is passed to the web applciation. For instance it is indicated after the (?). They are like a Key=Value pairs and perhaps very vital to facilitae data searched.

What are two HTTP verbs and how are they different?
They are the GET and POST verbs. The GET information packet will send what you requested to you from the server without modifying anything. While the POST information has the propensity to fill a form and change the information. For instance change password in a FORM

What is an HTTP request?
It access information from a server requested by a client(GET) and provided by the host

What is an HTTP response?
It is the resposne from the server due to information rquested.

What is an HTTP header?
Give a couple examples of request and response headers you have seen.
A header is the inclusion of hostname, date requested by the client , cookies, content-length, content-type etc.

Example of request header
host: wxyzsomesite.com
User-Agent: mozilla/5.0
acept text/html*/*

Example of response header:
Access-controll-allow-origin
Connection:Keep-Alive
Content-type: tetx/html
Date: web,12 october 2022 16:06:00GMT
Server: Appache

What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

. client request information from browser
. The protocol is http, host or site is somesite.com, and the resources is some/page.html
. DNS convert the host information such as somesite.com to an IP address and connect to it to a default port such as port 80.
