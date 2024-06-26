## EduGo

EduGo is a MERN (MongoDB, Express.js, React.js, Node.js) based web application for college students to share and read interview experiences. This platform aims to help students prepare better for interviews by learning from the experiences of their peers.

## Features

### User Authentication
- Secure user registration and login using JSON Web Tokens (JWT).
- Passwords are hashed using bcrypt to ensure security.
- Sessions are managed to keep users logged in across pages.

### Post Interview Experiences
- Users can share their interview experiences.
- Posts can include the company name, role, questions asked, and overall experience.
- Experiences can be edited or deleted by the original author.

### View Experiences
- Browse through a list of shared interview experiences.
- Search functionality to find specific posts by keywords.
- Filter experiences by company, role, and other criteria.

### Comments
- Users can comment on shared experiences.
- Comments can be used to ask questions or provide additional insights.
- Authors can respond to comments on their posts.

### User Profiles
- Each user has a profile page.
- Profile displays user's shared experiences and comments.
- Users can update their profile information and view their activity history.

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download it as a zip file and unzip it on your machine.

### Step-by-Step Guide

1. **Open the project in your preferred code editor.**
2. **Open the terminal:**
   - In VS Code, go to `Terminal` -> `New Terminal`.
3. **Split your terminal into two:**
   - Run the Frontend on one terminal and the Backend on the other terminal.

### Frontend Setup

In the first terminal, run the following commands:

```bash
$ cd frontend
$ npm install  # To install frontend-side dependencies
$ npm start  # To start the frontend
```
### Backend Setup

In the second terminal, follow these steps:

1. **cd Backend and Set environment variables in .env**
2. **Create your mongoDB connection url, which you'll use as your MONGO_URI**
3. **Supply the following credentials**

```bash

URI=http://localhost:3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET_KEY=your_jwt_secret_key
```
```bash

$ npm install  # To install backend-side dependencies
$ npm start  # To start
```
## Technologies Used

This project was created using the following technologies.

### Frontend

- **React.js:** JavaScript library for building user interfaces, specifically for single-page applications.
- **React Hooks:** For managing and centralizing application state.
- **react-router-dom:** To handle routing.
- **axios:** For making API calls.
- **CSS:** For styling the user interface.
- **uuid:** For generating random IDs.
- **React Icons:** Small library that helps you add icons to your React apps.

### Backend

- **Node.js:** Runtime environment to build fast server applications using JavaScript.
- **Express.js:** Server for handling and routing HTTP requests.
- **Mongoose:** For modeling and mapping MongoDB data to JavaScript.
- **jsonwebtoken:** For authentication.
- **bcryptjs:** For data encryption.
- **dotenv:** Zero dependency module that loads environment variables.
- **cors:** Provides Connect/Express middleware for enabling CORS.

### Database

- **MongoDB:** NoSQL database that provides a free cloud service to store MongoDB collections.


## Contribution

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. **Fork the repository.**

2. **Create your feature branch (git checkout -b feature/AmazingFeature).**
3. **Commit your changes (git commit -m 'Add some AmazingFeature').**
4. **Push to the branch (git push origin feature/AmazingFeature).**
5. **Open a pull request.**



