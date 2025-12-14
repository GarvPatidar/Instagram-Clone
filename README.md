
## Task 01

# Mini Instagram Clone

## Project Overview

This project is a Mini Instagram-style full stack application developed using the MERN stack.
The main objective of this project is to understand user authentication, database relationships, RESTful API design, and frontend state management by implementing core Instagram-like features.

Users can create accounts, upload posts with captions, follow other users, like and comment on posts, and view a personalized feed based on their following list.


## Features Implemented

### Authentication

* User signup and login
* Secure password hashing using bcrypt
* JWT-based authentication
* Protected routes for authenticated users

---

### Follow System

* Follow other users
* Unfollow users
* Maintain followers and following relationships

---

### Post Management

* Create posts with:

  * Image upload using Cloudinary
  * Caption support
* View posts created by followed users
* Delete own posts

---

### Likes

* Like posts
* Unlike posts
* Dynamic like count updates without page refresh

---

### Comments

* Add comments on posts
* View comments with username and comment text

---

### Personalized Feed

* Feed displays posts only from followed users
* Latest posts appear first

---

### Profile Management

* View user profile
* Update profile information
* Upload profile image
* View followers and following count

---

## Tech Stack

### Backend

* Node.js
* Express.js
* MongoDB
* JWT (JSON Web Tokens)
* bcryptjs
* Cloudinary
* cors
* dotenv

---

### Frontend

* React.js
* React Router DOM
* Redux Toolkit
* Axios
* Tailwind CSS
* react-icons
* react-hot-toast

---

## Project Structure

```
FullStack-Instagram-Clone/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   └── App.jsx
```

---

## How to Run the Project

### Backend Setup

```bash
cd backend
npm install
npm start
```

Create a `.env` file inside the backend directory:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## Learning Outcomes

* Implemented secure authentication using JWT
* Understood MongoDB schema relationships
* Built RESTful APIs using Express.js
* Managed frontend state efficiently using Redux Toolkit
* Gained hands-on experience with full-stack application development

