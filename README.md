# Real-Time Collaborative Text Editor

A **real-time collaborative text editor** where multiple users can edit the same document simultaneously. Built with **React**, **Express.js**, and **WebSocket**, this project allows instant updates across all connected clients, providing a seamless editing experience.


## Features
- **Real-time collaboration**: Changes made by any user are instantly reflected across all other users.
- **WebSocket communication**: Persistent WebSocket connections enable efficient, low-latency communication.
- **Simple, intuitive UI**: Built with React to ensure a responsive and user-friendly experience.
- **Live document updates**: Clients receive document updates in real-time as changes occur.

## Technologies Used
- **React**: Frontend framework to create the interactive text editor interface.
- **Express.js**: Server-side framework to handle WebSocket connections and serve the app.
- **WebSocket**: For real-time communication between the client and server.
- **Cors**: Used for handling cross-origin resource sharing (CORS) to allow requests from different domains.

## Installation & Setup

To run this project locally, follow these steps:

### 1. Clone the repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Haddajii/Real-time-collaborative-text-editor.git
cd Real-time-collaborative-text-editor
```
### 2. Install client dependencies
Navigate to the client folder and install the required dependencies:

```bash
cd client
npm install
```
### 3. Install server dependencies
Next, navigate to the server folder and install the required dependencies:

```bash
cd ../server
npm install
```

### 4. Start the WebSocket server
Start the server with the following command:

```bash
npm start
```
The server will run on http://localhost:5001.

### 5. Start the React client
Go back to the client folder and start the React app:

```bash
cd ../client
npm start
```
The frontend will be served on http://localhost:3000.

### 6. Open in Multiple Tabs or Devices
To test the collaborative editing, open the application in multiple browser tabs or different devices. As you make edits in one tab, the changes will instantly appear in all other open tabs or devices connected to the same server.

### Usage
Open the app in two or more browser tabs or devices.
Start typing in one tab and see the updates reflected live on the other tab.
Each user can make their own changes, and they will instantly be visible to all connected users in real-time.

### License
This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.


### Contributing
Feel free to fork this repository and submit pull requests for bug fixes, features, or improvements. Contributions are always welcome!

Made with ❤️ by Haddajii
