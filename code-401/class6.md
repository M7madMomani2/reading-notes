# Node.js
## What Is Node and When Should I Use It?
![Image](https://www.bleepstatic.com/content/hl-images/2020/08/04/nodejs-header.jpg)

> - Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine. 
> - The V8 engine : is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute Use a version manager. 


![Image](https://2.bp.blogspot.com/-S7ZyL0LsBzc/WayM6X0UeoI/AAAAAAAAnig/NoaBd72wa3sRhmgf6ROhohFDWRDjB_dLgCLcBGAs/w1200-h630-p-k-no-nu/NODEJS%2BASYNC%2B%25281%2529.png)
> - ### version manager is a program that allows you to install multiple versions of Node and switch between them at will. 

> - There are various advantages to using a version manager.

> - You can check that Node is installed on your system by opening a terminal and typing node -v. If all has gone well, you should see something like v12.14.1 displayed. This is the current LTS version at the time of writing.
npm, the JavaScript Package Manager
> - To check which version you have installed on your system, type npm -v.
> - npm is also the world’s largest software registry. There are over 1,000,000 packages of JavaScript code available to download, with billions of downloads per week. Let’s take a quick look at how we would use npm to install a package.


![Image](https://www.mundojs.com.br/wp-content/uploads/2019/01/javaScriptv8engine.jpg)

## server101
### we can use node Name.js to run js code and see what's happened

### npm init -y
> - This will create and auto-populate a package.json file in the same folder

### npm install lodash --save
> - install the lodash package and save it as a project dependency.
> - you can check dependencyes from package.json file 

### require('http'); :- 
> - We use this to create a new web server object,
### http.createServer((request, response):-  
> -  The anonymous function is called with two arguments (request and response). 
### response.writeHead(200); response.end('Hello, World!');
> - These contain the request from the user and the response, which we use to send back a 200 HTTP status code, along with our “Hello World!” message. 
### .listen(3000):- 
> - we tell the server to listen for incoming requests on port 3000, and output a message to the terminal to let us know it’s running.

