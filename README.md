# Fullstack Chat App

This is a real-time chat application built using a fullstack approach, featuring a modern frontend and a robust backend. The app allows users to create accounts, log in, and participate in real-time conversations with others.

## Features

- **Real-Time Messaging**: Instant message delivery with live updates.
- **User Authentication**: Secure login and signup functionality.
- **Responsive UI**: Optimized for both desktop and mobile devices.
- **Scalable Backend**: Handles multiple concurrent users efficiently.
- **User Management**: Ability to create, update, and manage user profiles.

## SCREENSHOT-:
![Screenshot 2024-12-12 221937](https://github.com/user-attachments/assets/29c0f345-f71c-4895-abe5-563af9282dc1)


## Tech Stack

### Frontend

- **React**: For building a dynamic and interactive user interface.
- **Tailwind CSS**: For styling and responsive design.

### Backend

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Backend framework for handling API requests.
- **Socket.io**: For real-time, bi-directional communication between the client and server.

### Database

- **MongoDB**: For storing user data and chat messages.

### Others

- **JWT**: For secure authentication.
- **dotenv**: For managing environment variables.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/ShashwatSingh321/fullstack-chat-app.git
   cd fullstack-chat-app
   ```

2. Install dependencies for the frontend:

   ```bash
   cd frontend
   npm install
   ```

3. Install dependencies for the backend:

   ```bash
   cd ../backend
   npm install
   ```

4. Create a `.env` file in the backend folder and configure the following environment variables:

   ```env
   MONGO_URI=<Your MongoDB Connection String>
   JWT_SECRET=<Your Secret Key>
   PORT=5000
   ```

5. Start the backend server:

   ```bash
   npm start
   ```

6. Start the frontend development server:

   ```bash
   cd ../frontend
   npm start
   ```

7. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Create an account or log in with existing credentials.
- Start a conversation with any user in the app.
- Enjoy real-time chat with seamless UI updates.

## Folder Structure

```
fullstack-chat-app
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── server.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── App.js
│   │   └── index.js
├── .gitignore
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any queries or suggestions, feel free to reach out:

- GitHub: [ShashwatSingh321](https://github.com/ShashwatSingh321)
- Email: [shashwat73557@gmail.com](mailto:shashwat73557@gmail.com)

