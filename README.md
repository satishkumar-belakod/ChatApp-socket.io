# Chat-App
A real time chat application built using Node.js, Express, Socket.io

## Features<a name="features"></a>
+ Uses Express as the application Framework.
+ Real-time communication between a client and a server using [Socket.io](https://github.com/socketio/socket.io).
+ Unit test cases/assertions written using [Mocha](https://www.npmjs.com/package/mocha) and Expect v1.20.2(https://github.com/mjackson/expect)

## Installation<a name="installation"></a>
### Running Locally
Make sure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

1. Clone or Download the repository

	```
	$ git clone https://github.com/satishkumar-belakod/chat.io
	$ cd chat.io
	```
2. Install Dependencies

	```
	$ npm install
	```
3. Run Test cases
    ```
    npm test
    ```  
    If all test cases pass, you are good to go.
    
4. Start the application
	```
	$ npm start
	```

Your app should now be running on [localhost:3000](http://localhost:3000/).

## How It Works<a name="how-it-works"></a>
After installation, visit url [localhost:3000](http://localhost:3000/).

Login to the chat app, by specifying your name and chat room you want to join.

If no chat room exists, you can create one by just specifying new room name.

Let all others know the chat room name, so that they can join the room you created.
## Contribute <a name="contribute"></a>

Contribute by creating new issues, sending pull requests on Github or you can send an email at: satishkumar.me@outlook.com
