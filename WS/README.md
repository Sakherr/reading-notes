# Q: What are the main differences between scraping static and dynamic websites?
### A: Static websites don't change often, while dynamic websites change frequently. Static websites are easier to scrape because they mostly use HTML, CSS, and JavaScript, while dynamic websites use different technologies like JavaScript, AJAX, and PHP.

# Q: What are three techniques to avoid being blocked while scraping websites?


### Use a proxy server: It acts as a middleman between your computer and the website, hiding your IP address.
### Use a rotating proxy server: It constantly changes the IP address, making it harder for websites to block you.
### Use a VPN: It encrypts your internet traffic and routes it through a different server, protecting your IP address.
# Q: What is Playwright, and how does it help in web scraping?
### A: Playwright is a tool used for automating web browsing and testing. It's useful for web scraping because it can simulate user interaction with the website. Playwright is particularly beneficial for scraping websites that rely on JavaScript to show their content.

# Q: Can you provide an example of using Playwright for web scraping?
### A: Hmmm let's say you want to scrape a website that uses JavaScript to display its product listings. With Playwright, you can mimic a user browsing the site and clicking the "Add to Cart" button for each product. This way, you can extract product information like name, price, and quantity in stock.

# Q: What is the purpose of using XPath in web scraping, and can you give an example?
### A: XPath is a language used to select specific elements from XML or HTML documents, including web pages. It's commonly used in web scraping to pinpoint specific elements.

### For instance, if you want to extract the product name from a webpage, you can use XPath to select the element that contains the product name.