**Activity 0: Tools Installation and Initial Applications**

**Author:** ADEWALE OLAOMO  
**Date:** 18 Feb 2026

# **Introduction & Tools Installation**

**Introduction**

I installed Node.js, npm besides Visual Studio Code to prepare the
development environment. I checked that each tool worked - typing
version commands in the terminal. I built simple “Hello World” programs
with Node.js, Express or TypeScript.

The exercise showed how Node.js starts and runs backend code plus how
utilities like nodemon next to TypeScript speed up work.

**Node.js Installation Verification**

Once Node.js was on the system, I launched the terminal and confirmed
the installation.

**Command: node –v**

![node version](nodeversion.png)

**The screenshot displays the Node.js version that is installed on the
system and my setup completed without problems.**

## **NPM Installation Verification**

Next, I verified npm installation.

**Command: npm -v**

![NPM version](npmversion.png)

**Node.js Hello World (Console Application)**

I started - making a directory called hello - in that directory I placed
a file named app.js.

**Code:**

**Execute with below command**

**Command : node app.js**

**Output:**

![Hello world](hellowolrdconsole.png)

The screenshot displays a Node.js console application that runs without
errors and prints “Hello World!” in the terminal.

This small program showed me how Node.js runs JavaScript files on the
computer instead of inside a browser window.\*\*\*\*

**Express Hello World Application**

Express “Hello World” Application

I built a console application then added a basic web server with
Express.

Sequence

1.  **I created a folder called helloex.**

2.  **I ran the initialization command: npm init**

3.  **I installed Express: npm install express**

> **App.js Code :**

**Then I started the server:**

**Command : node app.js**

\*\*\*\*

**Output:**

![Hello World on browser](Helloworldonbrowser.png)

The screenshot captures the Express server as it runs and prints “Hello
World!” in the browser.

Node.js served as the tool that started the web server plus sent an
answer to the HTTP request.

**Nodemon Utility:**

To improve development workflow, I have installed nodemon globally:

**Command : npm install –g nodemon**

Now I will start the server using nodemon

**Command : nodemon app.js**

![Nodemon Start](nodemonconsole.png)

I edited the response string in the file then refreshed the browser. The
server restarted on its own - no manual step was required.

**Output:**

![nodemon start](nodemonstart.png)

The screenshot displays the Express server running under nodemon.
Nodemon restarts the server automatically each time the source file
changes.

Developers find this tool helpful because it removes the need for manual
restarts and shortens the development cycle.

**Node.js with TypeScript**

For the second part of the exercise I created a project folder called
MusicAPI.

### Commands Used:

**TypeScript Application Code**

**Execute Below Command**

**Command: ts-node app.ts**

**Output :**

![Typescript code](usingtypescript.png)

The screenshot shows the TypeScript Node.js application working in the
browser.

**Commented app.ts**

![Commented Code](commentedcode.png)

**Conclusion**

**During the exercise**

1.  **Installed Node.js and npm and checked both work**

2.  **Wrote a Node.js program that runs in the terminal**

3.  **Wrote an Express server that answers web requests**

4.  **Used nodemon so the server restarts after each change**

5.  **Wrote the same server again in TypeScript**

6.  **Learned why a project needs proper setup plus dependency records**
