# FunTime

FunTime is a full-stack social media web application built with the MERN stack (MongoDB, Express, React, Node.js) and REST API. The platform allows users to share posts, react to posts, comment on posts, follow other users, and more.

## Features

- **User Authentication:** Secure sign-up and login functionality.
- **Create and Share Posts:** Users can create, edit, and delete posts.
- **React to Posts:** Like or react to posts shared by others.
- **Comment on Posts:** Engage in discussions by commenting on posts.
- **Follow Users:** Follow other users to see their posts on your feed.
- **User Profiles:** View and edit your own profile or view others' profiles.
- **Responsive Design:** Accessible on desktop and mobile devices.

## Tech Stack

- **Frontend:**
  - React.js
  - Redux (for state management)
  - CSS/SCSS or styled-components

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (Database)
  - REST API

- **Authentication:**
  - JWT (JSON Web Token) for authentication

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- Node.js
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/funtime.git
   ```

2. **Install dependencies for both the client and server:**

   ```bash
   # Install server dependencies
   cd funtime/server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `server` directory and add the following:

   ```env
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```

4. **Run the application:**

   ```bash
   # Run the server
   cd ../server
   npm start

   # Run the client
   cd ../client
   npm start
   ```

   The application will be running on `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend.

## Usage

Once the application is running, you can:

- Register a new account or log in with an existing one.
- Create and share posts.
- Interact with other users by liking or commenting on their posts.
- Follow users to see their posts in your feed.
- View and edit your profile.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, feel free to reach out to Vaibhav Kashyap at vaibhavkashyap1012@gmail.com.

---

Feel free to adjust the details as needed!


