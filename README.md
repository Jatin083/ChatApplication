# Chat_Application 

Welcome to ChatApplication, a simple web-based chat application where users can communicate in real-time.

## Features

- **Real-time Chat**: Users can send and receive messages instantly.
- **User Authentication**: Users can create accounts and log in securely.
- **User Profiles**: Users can customize their profiles with avatars and status messages.
- **Multiple Chat Rooms**: Users can join different chat rooms based on interests or topics.
- **Message History**: Chat messages are saved, allowing users to view past conversations.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Real-time Communication**: WebSocket (Socket.io)

## Installation

1. Clone the repository:

   git clone https://github.com/yourusername/chatapplication.git

2. Navigate to the project directory:

   cd chatapplication and cd to both frontend and backend in different terminal

3. Install dependencies for both :

   npm install


4. Set up environment variables:

- Create a `.env` file in the root directory.
- Add the following variables:

  PORT=3000
  MONGODB_URI=mongodb://localhost/chatapp
  JWT_SECRET=yoursecretkey

5. Start the server:

npm start


6. Open your browser and visit `http://localhost:3000` to access the application.

## Usage

1. Sign up for an account or log in if you already have one.
2. Explore available chat rooms or create your own.
3. Start chatting with other users in real-time.
4. Customize your profile settings as needed.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

