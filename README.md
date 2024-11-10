---

# ChatApp - Real-time Chat Application

A modern, real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with Socket.io for real-time communication and JWT for secure authentication.

### Live Demo:
You can check out the live demo of the application [here](https://chatting-app-lbiw.onrender.com/login).

## Features

- **User Authentication**: Secure login and registration using JWT (JSON Web Token).
- **Real-time Messaging**: Instant, bidirectional communication using Socket.io.
- **Online/Offline Status**: Users can see who is online and who is offline.
- **User Search**: Easily find and start chatting with other users by searching for their names.
- **Responsive UI**: Beautiful and clean UI designed using **Tailwind CSS**.
- **NoSQL Database**: Store and retrieve messages using **MongoDB**, a NoSQL database.

## Technologies Used

- **MongoDB**: NoSQL database for storing user data and chat messages.
- **Express.js**: Web framework for Node.js to handle HTTP requests and routes.
- **React.js**: JavaScript library for building the user interface.
- **Node.js**: JavaScript runtime for server-side execution.
- **Socket.io**: For enabling real-time, bidirectional communication between clients and the server.
- **JWT (JSON Web Token)**: Used for user authentication and authorization.
- **Tailwind CSS**: A utility-first CSS framework for fast UI development.

## Installation

### Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/Yusuf-Hussain25/Chatting-App
   ```

2. Navigate to the `backend` directory:
   ```bash
   cd chattingapp/backend
   ```

3. Install the backend dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root of the backend directory (not shared publicly) and add the following environment variables:
   ```bash
   MONGO_URI=<Your MongoDB URI>
   JWT_SECRET=<Your JWT Secret Key>
   ```

5. Run the backend server:
   ```bash
   npm run dev
   ```

### Frontend

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Install the frontend dependencies:
   ```bash
   npm install
   ```

3. Run the frontend development server:
   ```bash
   npm run dev
   ```

4. Your app should now be running on `http://localhost:4002` (or the port provided in the terminal).

## Running Both Backend and Frontend

To run both the backend and frontend simultaneously, you can use the `build` script:

1. In the root of your project (the main directory), run the following command to install both backend and frontend dependencies:
   ```bash
   npm run build
   ```

2. This will install all dependencies for both the backend and frontend and build the frontend for production.

## Usage

- **Login**: Enter your credentials or sign up if you're a new user.
- **Search Users**: Use the search bar to find other users by name.
- **Chat**: Start real-time conversations with users.
- **Online Status**: See who’s online with a green status icon and offline users with a grey status icon.

## License

This project is licensed under the MIT License.

---
