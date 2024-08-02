# MERN-User-Registration

 This repository contains backend server and frontend application for a MERN Stack user management application.  
 
 Back-end is built with Node.js and Express and MongoDB for Database.

 Front-end is built with Reactjs


### Backend Server
- Base URL: [http://localhost:5000](http://localhost:5000)

### Frontend Server
- Base URL: [http://localhost:3000](http://localhost:3000)

## Prerequisites

- Node.js
- Express
- React.js
- JSON Web Token (JWT)
- MongoDB

## Environment Variables

```bash
APPLICATION_NAME = MERN-User-Manager  
PORT = 5000  
NODE_ENV = development  
(Use development for dev environment and production for prod environment)  
JWT_KEY = your_jwt_key_here  
JWT_TOKEN_DURATION = 30d  
MONGO_DB_URI = your_mongodburi_here  
ADMIN_REGISTRATION_KEY = your_adminSecret  
```

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <repository>
   ```

2. **Install dependencies:**

   ```bash
   cd MERN-User-Manager
   ```
   ```bash
   npm install
   ```

   Install Front-end dependencies.
   ```bash
   cd frontend
   ```

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root of the project and add the environment variables listed above.

4. **Run the server:**

    Execute following command in the root directory of the project.  

   ```bash
   npm run app
   ```

   The back-end server will be running at [http://localhost:5000](http://localhost:5000) or the specified port in your `.env` file.

   The front-end server will be running at [http://localhost:3000](http://localhost:3000).


