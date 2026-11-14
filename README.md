# Guftguu – Social Media Platform

**Guftguu** is a full-stack social media application designed to connect people through conversations, posts, and community interactions. It provides users with a platform to share content, interact with posts, and engage with other users through likes and comments.

## Overview

Guftguu aims to provide a simple and interactive social networking experience with a responsive frontend and a backend responsible for authentication, API handling, and database operations.

The application follows a full-stack architecture using React.js, Node.js, Express.js, and MongoDB.

## Features

- **User Authentication:** Secure user authentication using JWT.
- **Social Feed:** View and interact with posts shared by users.
- **Create Posts:** Share content with the community.
- **Likes & Comments:** Engage with posts through likes and comments.
- **User Management:** Support user-related functionality.
- **Responsive Interface:** Interactive frontend built with React and Material UI.
- **REST API:** Backend API powered by Express.js.
- **Database Integration:** Persistent data storage using MongoDB and Mongoose.

## Tech Stack

| Category | Technology |
|---|---|
| Frontend | React.js |
| UI Framework | Material UI |
| Backend | Node.js |
| Backend Framework | Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Authentication | JWT |
| API | REST |
| Bundler | Webpack |
| Development Tool | Nodemon |

## Project Architecture

```text
Guftguu/
│
├── client/
│   └── Frontend application
│
├── server/
│   └── Backend application
│
├── config/
│   └── Application configuration
│
├── package.json
├── nodemon.json
├── template.js
├── webpack.config.client.js
├── webpack.config.client.production.js
├── webpack.config.server.js
│
└── README.md
```

## Installation & Setup

### Prerequisites

Make sure you have the following installed:

- Node.js (>= 13.12.0)
- npm or Yarn
- MongoDB (local installation or MongoDB Atlas)
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/krrish3424beai24-spec/Guftguu.git

cd Guftguu
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Configure the application using the configuration file or environment variables.

Typical configuration:

```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/guftguu
JWT_SECRET=your_secret_key
```

For MongoDB Atlas, replace the local MongoDB URI with your Atlas connection string.

**Important:** Never commit your actual secrets or database credentials to GitHub.

### 4. Run in Development Mode

```bash
npm run development
```

This starts the application using Nodemon for development.

### 5. Production Build

Build the frontend and backend:

```bash
npm run build
```

Start the production server:

```bash
npm start
```

Note: The production start script currently uses Unix-style environment variable syntax. On Windows, you may need to use `cross-env` or adjust the script.

## Application Workflow

```text
           User
             |
             v
       React Frontend
             |
             v
       Express Server
             |
       +-----+------+
       |            |
       v            v
 Authentication   REST APIs
       |            |
       +-----+------+
             |
             v
          MongoDB
             |
             v
       Response to User
```

## Security

- JWT-based authentication.
- Password hashing as described by the project.
- HTTP security headers using Helmet.
- CORS configuration.
- Cookie parsing support.

## Future Enhancements

- Real-time messaging and notifications.
- Follow/unfollow functionality.
- User profile customization.
- Image and video sharing.
- Advanced search and discovery.
- Content moderation.
- Personalized social feed.
- Improved security and session management.

## License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE) file for details.

## Repository

GitHub: https://github.com/krrish3424beai24-spec/Guftguu

---

**Guftguu – Connect, Share, and Converse.**
