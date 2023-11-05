## ShodanDorks

## ShodanDorks



Shodan is a search engine that scans and indexes internet-connected devices. Here's a comprehensive list of tips and tricks (commonly referred to as "Shodan dorks") to help you search effectively on Shodan.io:

1. **Basic Keyword Search**: Start with a basic keyword search related to what you're looking for. For example, if you're interested in webcams, you can search for "webcam."

2. **Exact Match**: To find an exact match for a term or phrase, enclose it in double quotes, e.g., "Apache/2.4.7."

3. **Search by Port**: Specify a specific port using the `port:` operator, e.g., "port:80" to search for devices running web servers on port 80.

4. **Search by Hostname**: You can search for a specific hostname using the `hostname:` operator, e.g., "hostname:example.com."

5. **Search by IP Address**: To search for devices with a specific IP address, use the `ip:` operator, e.g., "ip:192.168.1.1."

6. **Country or Location**: Use the `country:` operator to search for devices in a specific country, e.g., "country:US."

7. **City**: Narrow your search to a specific city using the `city:` operator, e.g., "city:New York."

8. **Search by Organization**: You can search for devices belonging to a specific organization using the `org:` operator, e.g., "org:Google."

9. **Operating System**: Specify the operating system using the `os:` operator, e.g., "os:Windows."

10. **Service Banner**: To search for specific service banners, use the `http.title:` or `ssl:"TLS Certificate"` operators followed by the banner text, e.g., "http.title:"Welcome to our website"."

11. **Vulnerabilities**: Use the `product:` operator to search for specific software products and versions that may have vulnerabilities, e.g., "product:Apache 2.4.7."

12. **Devices with Default Credentials**: Search for devices that may have default login credentials by using "default password" in your query.

13. **Webcams and Cameras**: To find webcams and security cameras, try searches like "webcam has_screenshot:true" to only show those with available screenshots.

14. **IoT Devices**: You can search for Internet of Things (IoT) devices by using terms like "iot" or "smart."

15. **Specific Protocols**: Use operators like `ftp`, `ssh`, `telnet`, or `http` to search for devices using those protocols, e.g., "ftp has_screenshot:true."

16. **Filter by Port Status**: To search for devices with open or closed ports, use the `port:21 status:open` or `port:22 status:closed` operators.

17. **Product Specific Searches**: For specific products, use operators like `product:MySQL` to find servers running MySQL.

18. **Export Data**: Shodan offers a paid API that allows you to export search results programmatically. You can also export data in different formats using the website interface.

19. **Combine Operators**: You can combine multiple operators in one query to narrow down your search, e.g., "country:US port:80 Apache."

20. **Monitor Alerts**: Consider setting up alerts for specific searches so that you can be notified when new devices matching your criteria are discovered.

Please note that while Shodan can be a valuable tool for research and cybersecurity, always ensure you are using it responsibly and within the bounds of the law and ethical guidelines. Unauthorized access or misuse of information obtained through Shodan is illegal and unethical.
