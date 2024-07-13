# collaborative-study-platform
## Project Overview
The Collaborative Study Platform is a web application designed to enable students to create, edit, and share notes in real-time. It facilitates collaborative learning by allowing multiple users to work on the same notes simultaneously. The project showcases full-stack development skills, including frontend and backend technologies, secure user authentication, and real-time data handling.

## Features
- User registration and login
- Real-time collaborative note editing
- Note management (create, edit, delete)
- Secure user authentication using JWT
- Backend API with Node.js and Express
- Frontend developed with React and TypeScript
- Database management with PostgreSQL

## Technologies Used
### Frontend
- React
- TypeScript
- Axios
- React Router

### Backend
- Node.js
- Express
- PostgreSQL
- Sequelize
- JWT for authentication

## Installation Instructions

### Prerequisites
- Node.js
- PostgreSQL
- Git

### Backend Setup
1. **Clone the Repository**
 ```bash
    git clone https://github.com/Ayushigitgithub/collaborative-study-platform-backend.git
    cd collaborative-study-platform-backend
   ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Create `.env` File**
    Create a `.env` file in the root directory and add the following environment variables:
    ```env
    PORT=5000
    DATABASE_URL=Ayushigitgithub_postgresql_database_url
    JWT_SECRET=Ayushigitgithub_jwt_secret
    ```

4. **Run the Server**
    ```bash
    npm start
    ```

### Frontend Setup
1. **Clone the Repository**
    ```bash
    git clone https://github.com/Ayushigitgithub/collaborative-study-platform-frontend.git
    cd collaborative-study-platform-frontend
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Create `.env` File**
    Create a `.env` file in the root directory and add the following environment variable:
    ```env
    REACT_APP_API_URL=http://localhost:5000/api
    ```

4. **Run the Frontend**
    ```bash
    npm start
    ```

## Usage
1. **Register a New User**
   Navigate to `http://localhost:3000/register` and create a new account.

2. **Log In**
   Log in with your new credentials at `http://localhost:3000/login`.

3. **Collaborate on Notes**
   Access the study session at `http://localhost:3000/study` to start creating and editing notes in real-time.

## Project Structure

### Backend
- `src/app.ts`: Sets up the Express app.
- `src/server.ts`: Starts the server.
- `src/controllers`: Contains the logic for user authentication and note management.
- `src/models`: Defines the database models for users and notes.
- `src/routes`: Defines the API routes for authentication and notes.

### Frontend
- `src/components`: Contains reusable UI components like `NoteEditor` and `NoteList`.
- `src/pages`: Defines the main pages such as `Login`, `Register`, and `StudySession`.
- `src/App.tsx`: Sets up the main application and routing.

## Code Explanation
### Backend
- **Controllers**: Handle the logic for user authentication and note management.
- **Models**: Define the data structure for users and notes.
- **Routes**: Define the API endpoints for authentication and note operations.
- **App and Server**: Setup and run the Express server.

### Frontend
- **Components**: Implement the UI for the note editor and note list.
- **Pages**: Define the login, registration, and study session pages.
- **App**: Setup the routing for the application.

## Challenges and Solutions
Describe any challenges you faced while developing the project and how you solved them. This section can include technical difficulties, design decisions, and any trade-offs you made.

## Future Improvements
- Real-time collaboration using WebSockets
- User profiles with customization options
- Enhanced note management features (tagging, searching)
- Mobile responsiveness

## License
Include any licensing information if applicable.

## Contact
For any inquiries or feedback, please contact:
- Your Name
- Email: your-email@example.com
- GitHub: [Ayushigitgithub](https://github.com/Ayushigitgithub)
