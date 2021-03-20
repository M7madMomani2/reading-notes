# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

![image](https://i.ytimg.com/vi/rVyTjFofok0/maxresdefault.jpg)

# persistent local storage 
> - ## it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually) it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

## they have three potentially dealbreaking downsides:

> - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
> - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
> - Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

![image](https://i.pinimg.com/originals/ca/66/0a/ca660ac9b7985487984ce17e9acd8f73.jpg)

## HTML5 storage:

> -  HTML5 Storage specification
> - Introduction to DOM Storage on MSDN
> - Web Storage: easier, more powerful client-side data storage on Opera Developer Community
> - DOM Storage on Mozilla Developer Center. (Note: most of this page is devoted to Firefox’s prototype implementation of a globalStorage object, a non-standard precursor to localStorage. Mozilla added support for the standard localStorage interface in Firefox 3.5.)
> - Unlock local storage for mobile Web applications with HTML5, a tutorial on IBM DeveloperWorks

## Early work by Brad Neuberg et. al. (pre-HTML5):

> - Internet Explorer Has Native Support for Persistence?!?! (about the userData object in IE)
> - Dojo Storage, part of a larger tutorial about the (now-defunct) Dojo Offline library
> - dojox.storage.manager API reference
> - dojox.storage Subversion repository



## Web SQL Database:

> - Web SQL Database specification
> - Introducing Web SQL Databases
> - Web Database demonstration
> - persistence.js, an “asynchronous JavaScript ORM” built on top of Web SQL Database and Gears


## IndexedDB:

> - Indexed Database API specification
> - Beyond HTML5: Database APIs and the Road to IndexedDB
> - Firefox 4: An early walk-through of IndexedDB