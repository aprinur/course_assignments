## **Instructions**  
**Objective:** The goal of this exercise is to help you develop a foundational understanding of web navigation and its components, which are crucial for effective web scraping.

By the end of this exercise, you will have a strong foundational knowledge of how URLs, DNS, hyperlinks, and web servers work, and how this knowledge is applied in web scraping. 🚀  

---

## **Questions**  
1. **What are the main components of a URL, and what is the function of each component?**  

    1. Scheme (```http://```)
    
    Indicate the set of rules that will decide the transmission and exchange of data

    2. Subdomain (```www.```)
    
    To separate different section of a website as if specifies the type of resource to be delivered to the client

    3. Domain name (```.example.```)

    Specify the organization or entity that the URL belongs to.

    4. Top Level Domain (```.co.id```)

    Indicate the type of organization the website is registered to.

2. **What is the Domain Name System (DNS), and why is it essential for internet functionality?**  

    DNS is a system that translate domain names into IP address. It is essentials because with existance of DNS, human doesn't need to memorize IP address of the website to be addressed

3. **How does DNS translate a domain name into an IP address?**  

    It is involves converting a hostname into a computer-friendly IP address (such as www.google.com into 8.8.8.8).

4. **What is a hyperlink, and how does it assist in web navigation?**  

    Hyperlink or known as link is a clickable HTML element on a web page that opens another web page, a document or moves to a different section/location of the same page when clicked. It's all depends on URL behind the HTML element. It's very helpful for user to click the HTML element and the page will redirect to the embeded URL automatically rather than copy and paste URL or search the reference by ourself

5. **Why are hyperlinks significant in web scraping tasks?**  

    It is useful for web scraping because the programmer can follow the link to the next page of the scraped page 

6. **What is a web server, and how does it support website hosting?**  

    Web server is a computer that stores web server software and a website's components files ( HTML documents, image, CSS stylesheets, and JavaScript files). Web server will connect to the internet making it accessible by user through the website

7. **How does a web server process incoming requests from users or web scrapers?**  

    1. Parsing the request
    - Reading the HTTP headers (like contect type, Authorization)
    - Parsing the request method ( GET, PROST, PUT)
    - Extracting request parameters ( query strings, body data)
    - In a typical web server, this involves decoding HTTP messages, which might include reading JSON payloads or multipart form data.
    2. Routing the  Request
    - Route the request to the appropriate handler based on the request's URL and HTTP method
    - The routing logic detemines which function or controller to invoke tohandle the specific request. E.g: in a RESTful API, a GET/ user request might me routed to a function that retrieves a user's data from the database
    3. Businnes Logic Exceution
    - Accessing databases
    - Performing complex calculations.
    - Communication with external service(APIs, microservice)

8. **How do DNS, URLs, and hyperlinks work together to enable web navigation?**  

    When opening a URL, DNS will convert hostname into IP address of a webpage, and in a webpage there is an HTML element that embeded a URL to another page

9. **Why is understanding web servers crucial for effective web scraping?**  

    Understanding web server is crucial for effective web scraping because with understanding how a web server works a web scraper can get the data properly to avoid any damages on web server.

10. **How can analyzing the structure of URLs and hyperlinks improve the efficiency of web scraping?**  

    With analyzing the structure of URL, a web scraper can modify the URL that will be sent to the web server and get the required data