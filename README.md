# Travel Snap

Travel Snap is a web application that allows users to upload pictures of their vacation and view photos shared by other users. This app is built using the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User Authentication: Sign up and log in to your account.
- Upload Photos: Share your vacation photos with other users.
- View Photos: Browse photos uploaded by other users.
- User Profiles: View your uploaded photos and manage your account.

## Technologies Used

- **MongoDB**: Database to store user data and photos.
- **Express**: Backend framework to handle API requests.
- **React**: Frontend framework for building user interfaces.
- **Node.js**: Server environment to run Express.

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Backend (Express)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/travel-snap.git
    cd travel-snap
    ```

2. Navigate to the backend directory:
    ```bash
    cd backend
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file and add your environment variables:
    ```plaintext
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. Start the Express server:
    ```bash
    npm start
    ```

### Frontend (React)

1. Open a new terminal and navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the React development server:
    ```bash
    npm start
    ```

## Usage

1. Open your browser and go to `http://localhost:3000` to access the application.
2. Sign up for a new account or log in with your existing account.
3. Upload your vacation photos and browse photos shared by others.
