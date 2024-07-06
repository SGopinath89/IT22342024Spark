This guide will walk you through installing Node.js, MongoDB, and running a sample application that utilizes both.

**Node.js:

Visit the official Node.js website: https://nodejs.org/en
Download the installer for your operating system.
Run the installer and follow the on-screen instructions.

**MongoDB:
Visit the official MongoDB website: https://www.mongodb.com/docs/manual/installation/
Download the Community Server version for your operating system.
Run the installer and follow the on-screen instructions.
During installation, make sure to note the directory where MongoDB is installed (usually C:\Program Files\MongoDB\Community Server on Windows or /usr/local/mongodb on macOS/Linux).

**Start MongoDB Server
Open a command prompt or terminal window.
Navigate to the bin directory within your MongoDB installation path (e.g., cd C:\Program Files\MongoDB\Community Server\bin on Windows).
Start the MongoDB server by running one of the following commands:
Windows: ./mongod
macOS/Linux: mongod

**Run the Sample Application

Assuming the sample application has separate folders for "api" and "web":
Open two separate command prompts or terminal windows.
In the first window, navigate to the "api" folder of the sample application.

**Run the following commands sequentially:
>>npm update (Updates any existing dependencies)
>>npm install -g nodemon (Installs the nodemon package globally for development purposes)
>>nodemon server.js (Starts the server using nodemon for automatic restarts on code changes)
In the second window, navigate to the "web" folder of the sample application.

**Run the following commands sequentially:
>>npm update (Updates any existing dependencies)
>>npm start (Starts the web application)

**Access the Application
>>Open your web browser.
>>In the address bar, enter http://localhost:3000/.
This should launch the sample application in your browser.
