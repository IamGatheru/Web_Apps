HTTP - Hypertext Transfer Protocol

- It is the dominant Application Layer Protocol on the Internet
- Invented for the Web - to retrieve HTML, images and documents etc
- Extended to be data in addition to documents - RSS. Web Services, etc
- Basic Concept-
1. Make a connection
2. Request a document
3. Retrieve the Document
4. Close the connection

URL(uniform Resource Locator)
http://www.dr-chuck.com/page.htm(protocol, host, document/file)
protocol - how
host - where
file - what

GETTING DATA FROM THE SERVER
Request--> Server--> Browser(Parse/Render)--> Response

Internet Standards:
Internet Engineering Task Force(IETF)
www.ietf.org
RFC(Request For Comments)
2616(HTTP)

$telnet www.dr-chuck.com 80(default web port)
GET http://dr-chuck.com/page1.htm HTTP/1.0
(get a new line), hit one line

DEBUGGING CAPABILITY OF BROWSERS 

Browser - HTML, CSS, "Document Object Model"(The DOM) and JavaScript
Server - Apache websever with a PHP installed
Database Server - MySQL, Postgress, Oracle, SQL Server  or similar
