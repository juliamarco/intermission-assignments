## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?

 First the browser checks its cache, as it  maintains a repository of DNS records for a fixed duration for websites you have previously visited. It also checks the Operating system, the router and the ISP cache. 
 If the requested URL is not in the cache, ISP’s DNS server initiates a DNS query to find the IP address. Once the browser receives the correct IP address it will build a connection with the server that matches IP address to transfer information.
 Then the browser sends an HTTP request to the web server and the server handles the request and sends back a response. The server response contains a representation of the web page you requested (HTML content), that the browser will display.

1.  What does HTTP stand for?

HyperText Transfer Protocol

1. 	What protocol does the World Wide Web use?

HTTP

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

Internet Protocol

1. 	What does DNS stand for?

  * A. Domain Name System

1. 	How are text domain names matched to their respective numeric IP addresses.
 By the Domain Name System

1. 	What is the client?

  * E. The computer which the IP address belongs to
  
1. 	What does URL stand for?
 Uniform Resource Locator

1. 	What are protocols

 * D.	The standardised method for transferring data or documents over a network

1. what is the `www` portion of a url?
It stands for "World Wide Web" and refers to all of the publicly accessible websites in the world. The Internet has different services and the web is one of them. 

1. What is The markup language used for all web documents?
HTML

1. What is the organization that monitors web technologies?
W3C (World Wide Web Consortium)


1. What is the Protocol for transferring web documents on the Internet?
HTTP 

1. What matches the domain names with numeric IP addresses?
DNS




