## 1. Objective

Build a full-stack web app named “EtharaChats” that includes a real-time group chat where users can join by entering their details like name and gender before entering the chat room.

The main goal is to build a smooth UI with responsive, and attractive chatting web app where users can join the chat room by entering their identity details like name and gender, without requiring complex authentication.

The application should be interactive, smooth, scalable and proper error handling.


## 2. Context & Role

You are a professional experienced full-stack web developer with proiciency in building ull-stack web apps using HTML, CSS, JavaScript, Node.js HTTP server, and Socket.IO.

Your responsibility is to design and develop the complete web application from scratch, including:

* Responsive Frontend
* Backend server
* Real-time socket communication
* User session handling
* Online user tracking
* Input validation
* Error handling

The final application should be fully functional and deployable.


## 3. Input Requirements

Users should be able to:

* Open the landing page
* Click a “Join Chat” button
* See a popup/modal before entering the chat room
* Enter:
  * Name
  * Gender
* Join the public group chat instantly

### User Identity Fields

Required inputs:
* Name
* Gender

Genders options:
* Male
* Female
* Other


## 4. Expected Output

Give me the fully working source code for both frontend and backend.

The output must include:

### Frontend

* Responsive UI
* Landing page
* Join-chat popup
* Chat interface
* Online users sidebar
* Real-time message updates
* Typing-friendly input box
* Timestamp for messages
* Sender details (name + gender)

### Backend

* Basic HTTP server
* Socket.IO integration
* Real-time event handling
* User connection/disconnection logic
* Online users management
* Broadcasting messages
* Proper validation
* Error handling

### Additional Deliverables

* Well-structured project folders
* Clean commented code
* package.json
* Setup guide from scratch
* Commands for installation and running
* Deployment-ready configuration


## 5. UI & Design Requirements

### Theme Colors

The UI theme should primarily use:

* Orange
* Pink
* Black

### Design Expectations

* Modern chat-style interface
* Smooth scrolling
* Attractive buttons and cards
* Responsive on all screens
* Professional animations and hover effects

### Chat Features

Each message should display:

* Sender name
* Gender
* Timestamp
* Message content

### Online Users Section

Show:

* Active users list
* Gender indicator/icon
* Real-time online/offline updates


## 6. Data Processing & Real-Time Communication Techniques

Implement proper real-time data flow using Socket.IO.

### Required Data Processing Techniques

#### Real-Time Event Processing

Use socket events such as:

* user-joined
* user-left
* send-message
* receive-message
* update-users

#### Data Synchronization

Ensure:

* All users receive messages instantly
* Online user list updates in real time
* No duplicate messages appear

#### State Management

Maintain:

* Active socket sessions
* Connected users map/object
* Real-time chat updates

#### Timestamp Processing

Automatically generate and format timestamps for each message.

#### Client-Server Communication

Use:

* WebSockets by Socket.IO
* Time-based architecture
* Broadcast messaging techniques


## 7. Input Validation Requirements

Implement validation on both frontend and backend.

### Validate:

* Empty name field
* Invalid gender selection
* Empty messages
* Very long messages
* Special character abuse/spam
* Duplicate blank spaces

### Validation Rules

* Name must contain at least 2 characters
* Message cannot be empty
* Trim unnecessary spaces
* Limit message length appropriately



## 8. Error Handling Requirements

Implement error handling in the whole application.

### Frontend Error Handling

Handle:

* Empty form submission
* Connection issues
* Socket disconnection
* Invalid inputs

### Backend Error Handling

Handle:

* Socket connection failures
* Missing user data
* Unexpected disconnects
* Server crashes

### User-Friendly Error Messages

Display toast and messages like:

* “Please enter your name”
* “Connection lost. Reconnecting…”
* “Message cannot be empty”


## 9. Technical Stack Requirements

Use only the following technologies:

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Basic HTTP Server
* Socket.IO

### Restrictions

Do NOT use:

* React
* Angular
* Vue
* Express.js
* MongoDB
* Firebase

Keep the project lightweight and framework-free.


## 10. Folder Structure Expectations

Use a clean production-style structure such as:

```plaintext
EtharaChats/
│
├── client/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── server/
│   └── server.js
│
├── package.json
├── README.md
```


## 11. Setup Guide Requirement

Provide a complete setup guide including:

* All enviroment and dependencies installation
* How to run the server
* Localhost URL
* Production deployment guidance

Include all terminal commands.


## 12. Final Development Expectations

The final web app should be:

* Fully functional
* Real-time
* Responsive
* Production-ready
* Smooth

Do not provide partial codes.
Provide complete working code for all files with proper explanations.
