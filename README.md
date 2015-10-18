# build an angular js front end web page in visual studio code editor

visual studio code editor is the new coding tool Microsoft invented to allow .net developer to develop non .net web application for mobile strategy. visual studio editor is Node js based. when we say .net applicaiton, we say it is run under .net 2.0... framework, now visual studio editor use node js framework to develop js server back end for modern mobile application, .net has no space here. what .net can do here is to provide restful APIs for those front end.

however, node js has its own backend, that is JSON server with MongoDB, therefore, using visual studio editor

Steps to get started here is listed below

1, install Node js

download node.exe from internet and install it to window 10

2, create a directory in c:// such as C:\00000vs2016\AngularinVScode

3, go to github to create a new directory and clone this to this local directory C:\00000vs2016\AngularinVScode

4, open cmd and point to this folder C:\00000vs2016\AngularinVScode

5, run npm install -g express-generator to install expess js

6, run express mobileangularinvscode to create a new web application called mobileangularinvscode

7, go to mobileangularinvscode folder to run npm install

8, now we have created a node js based web template that we can use Visual Studio COde editor to develop the application

9, open Visual Studio Code Editor (download from microsoft web site)

10, click file to open a folder, find out folder mobileangularinvscode and open it

11, click package.json file, you can see the start is /bin/www

12, click bug icon or F5 to run program, you can see launch .bin/www appear next to run icon, tis is the starting point we get web page run

13, I like html view engine, so i need to change default view engine from jade to html, open app.js, disable

// app.set('views', path.join(__dirname, 'views')); // app.set('view engine', 'jade');

14, you need to install ejs to run npm install ejs

15, now you are ready to run html in visual studio code editor

16, before to run this, you need to create an index.html page in views folder and change th eport to 3001

17, press F5 , you can see cmd is running , it means web server is running

18, open internet explorer in window 10 (edge), input link http://localhost:3001 and return, you can see index page is displayed properly.

19, add angular js code into html page. 

20, run visual studio code, you now can see angular js enabled SPA html page .

21, click git icon in visual studio code edittor, you can comment all changes to your github
