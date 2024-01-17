# SpiderChat

SpiderChat is a comprehensive social networking platform that facilitates seamless communication and media sharing among users. This project is built using the MERN stack (MongoDB, Express.js, React, Node.js) and utilizes Web Sockets for real-time communication.


## Features

- Real-time messaging
- Image sharing
- Video sharing
- User account creation and authentication

For example purposes, the user credentials are hardcoded and only the following are accepted by the application:

| Username | Password | 
| -------- | -------- |
| test1    | test     | 
| test2    | test     |
| spider   | spy      |




## Getting Started

Follow these steps to get SpiderChat up and running on your local machine.


### Prerequisites

- Node.js and npm installed
- MongoDB installed and running 

### Installation

1. Clone the repository: `git clone https://github.com/yourusername/spiderchat.git`
2. Navigate to the project folder: `cd spiderchat` and run the following commands to install required dependencies for frontend and backend.
3.	cd client
4.	npm install or yarn add.
5.	cd ..
6.	cd api
7.	npm install or yarn add.
   

### Usage

Start the backend server and frontend development server by running the following commands:
   1. cd api
   2. yarn run nodemon
   3. cd..
   4. cd client
   5. yarn dev
      
Visit `http://localhost:5173` in your browser to use SpiderChat locally by logging in through the valid credentials.


![Screenshot (131)](https://github.com/Nitya063/Mern-chat/assets/66220305/d018a7fd-1397-4d3f-a810-bc4b42d1fc8c)



Once authenticated, the chat will be displayed and the online contacts will be seen on the left. Open multiple tabs/windows and authenticate with different users. Write a message and hit Enter or click the Send button to chat:


![Screenshot (130)](https://github.com/Nitya063/Mern-chat/assets/66220305/af427f65-502d-4eeb-b85f-3226adc47103)


## Configuration

Adjust the backend/frontend URLs and other configurations in the respective configuration files.


## Technologies Used

- MongoDB
- Express.js
- React
- Node.js
- Web Sockets
- Axios


## Contributing

Contributions are welcome! If you find a bug or have a feature request, please open an issue.



