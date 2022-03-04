# Password Generater V4

Intro
-----
Secure passwords are long, complex and hard to guess. This tool will generate passwords for you based on your personal key and the domain name for the website you want to access. 

By using a different password for each web page you visit, you will be protected from attackers who guess or discover your password on any one website.  

You must remember and keep safe only your personal key.

This tool will reliably generate the same password again and again for the same pair of personal key and domain name.

About
-----
As is, this is a pure Javascript implementation, relying on some ES5 features. The basic premise is that the user provides their own memorable passkey, and the url for a given website. The code then takes these two strings and interleaves them into one mixed string.  It then performs a SHA-256 hash using the built in crypto library.  This string is finally trimmed to the number of characters requested by the user, default value is 40.

Using 
-----
Simply enter your passkey and url.  Click on the password generated to copy it to the clipboard.

Using This As A Learning Tool
-----------------------------
Aside from the meager content provided, the all-in-one html file provides a simple set of use cases in a portable format.  With this you could:

* wrap it with a web framework to provide a quick-start website to explore packaging and deployment
* refactor the existing code
* abstract the code into remote functions, backend logic or microservices
* improve the user experience or look and feel

Granted, you could do this with any other content but feel free to use this as a starting point to have a "my first app" with a bit more utility than a simple "hello world" implementation.