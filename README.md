# How a Web Request Works

![Web Request Flow](request-flow.png)

When I open a website like google.com, many steps happen in the background.

First, I type google.com in my browser and press Enter. The browser is the Client.

Then, the browser asks the DNS for the IP address of google.com. DNS changes the website name into an IP address.

After that, the request goes through the Internet and my ISP until it reaches the Web Server.

The Web Server receives the request and processes it. Then, it sends a Response back to the browser.

The response can contain HTML, CSS, JavaScript, and images.

Finally, the browser receives the response and displays the website.

In simple words:

Browser → DNS → Internet → Web Server → Response → Browser → Web Page
