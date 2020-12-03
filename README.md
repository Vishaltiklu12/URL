# URL
What happens when you type in an URL ?
1.Browser checks cache for DNS entry to find the corresponding IP address of website.
2.It looks for following cache. If not found in one, then continues checking to the next until found.
3.If not found in cache, ISP’s (Internet Service Provider) DNS server initiates a DNS query to find IP address of server that hosts the domain name.
4.The requests are sent using small data packets that contain information content of request and IP address it is destined for.
5.Browser initiates a TCP (Transfer Control Protocol) connection with the server using synchronize(SYN) and acknowledge(ACK) messages.
6.Browser sends an HTTP request to the web server. GET or POST request.
7.Server on the host computer handles that request and sends back a response. It assembles a response in some format like JSON, XML and HTML.
8.Server sends out an HTTP response along with the status of response.
9.Browser displays HTML contentBrowser checks cache for DNS entry to find the corresponding IP address of website.
