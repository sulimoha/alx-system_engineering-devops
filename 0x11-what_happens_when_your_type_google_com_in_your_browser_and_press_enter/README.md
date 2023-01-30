<h1>What happens when you type google.com in your browser and press Enter</h1>

When you type https://www.google.com in your browser and press Enter, a series of events is triggered that ultimately leads to the display of the Google homepage on your screen. Here's what happens in detail:
- DNS Request: The first step is to translate the human-readable domain name (google.com) into an IP address that computers understand. This is done by sending a DNS (Domain Name System) request to a DNS resolver. The resolver then returns the IP address of the server associated with the domain name.
- TCP/IP: Once the IP address is obtained, the browser initiates a TCP (Transmission Control Protocol) connection with the server. This protocol is responsible for establishing and maintaining a reliable connection between the client and the server. The IP (Internet Protocol) is used to transmit the data packets between the two devices.

- Firewall: If the server is behind a firewall, the firewall will check the incoming request to ensure it meets its security policies. If the request is not deemed harmful, it will be allowed to pass through to the server.

- HTTPS/SSL: The browser uses HTTPS (Hypertext Transfer Protocol Secure) to establish a secure connection with the server. This protocol encrypts all the data transmitted between the browser and the server, making it unreadable to anyone who may intercept it. The SSL (Secure Socket Layer) or TLS (Transport Layer Security) protocol is used to provide the encryption.

- Load-balancer: If the server is part of a group of servers, the incoming request is directed to the appropriate server by a load-balancer. The load-balancer distributes the incoming traffic evenly across all available servers, ensuring that no single server is overwhelmed with requests.

- Web server: The request finally reaches the web server, which is responsible for delivering the HTML code that makes up the web page to the browser. The web server may be Apache, Nginx, or any other web server software.

- Application server: If the web page being requested requires dynamic content, the web server may forward the request to an application server. The application server runs the necessary code to generate the dynamic content and returns it to the web server, which then delivers it to the browser.

- Database: If the dynamic content requires data from a database, the application server will communicate with the database to retrieve the necessary information. The database may be MySQL, PostgreSQL, or any other database management system.

And that's it! This is what happens behind the scenes every time you type a URL into your browser and press Enter. Understanding these processes helps us appreciate the complexity and efficiency of the modern-day web.

