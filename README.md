# pywebapp
Python3 Web App using Webkit2

Allows you to create quick web apps by simply specifying the url for the webapp, size of the window and even additional CSS to use for the website so you can customize the website/app without having to have access to the website itself.

Uses GTK3 for the window and has a quick loader/revelaer so you can customize the look of the window while the webpage loads.

All links on the website are checked, any link that is set to open in new windows will use the default browser to open while all links that are within the same domain the webapp is using will be loaded in the same window. If link is not within the same url the default browser will also be used.

Cookies are also stored so the session is kept and you don't need to login every time the app starts.
