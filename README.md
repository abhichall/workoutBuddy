# WorkoutBuddy

WorkoutBuddy is a full-stack workout tracker application designed to help users manage their fitness routines. Built with React, Node, and Express on the backend, and MongoDB for data storage, this app provides secure authentication using JWT tokens to keep your workout data safe and personalized.

## Project Overview

WorkoutBuddy is designed to allow users to log workouts, track progress, and manage fitness goals. It features user authentication, a powerful backend for handling workout data, and a responsive React-based frontend. MongoDB is used for storing user and workout data, while JWT tokens ensure secure login sessions.
<img width="1659" alt="Screenshot 2024-09-22 at 12 17 04 PM" src="https://github.com/user-attachments/assets/5455506e-77e3-4c18-ab7b-e17ee9afaf51">

<img width="1449" alt="Screenshot 2024-09-22 at 12 12 05 PM" src="https://github.com/user-attachments/assets/2c21fc04-dd9f-4635-bb28-bd40b10cfcff">

## Features

- **User Authentication:** Secure sign-up and login system using JWT tokens to authenticate users.
- **Workout Management:** Log workouts, track progress, and set fitness goals.
- **Real-time Updates:** Workouts and stats update in real-time with smooth UI interactions.
- **Database Integration:** MongoDB stores all user data, workouts, and logs for easy retrieval and management.
- **Modular Design:** Easy to scale and add features.

## Tech Stack

- **Frontend:** React (with Vite for fast development and HMR).
- **Backend:** Node.js, Express.js.
- **Database:** MongoDB.
- **Authentication:** JWT for secure token-based user sessions.
- Utilized proxy for connection between front-end and back-end
  
## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/) and npm/yarn installed.
- MongoDB installed and running locally or accessible through MongoDB Atlas.

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/workoutbuddy.git
    ```

2. Navigate to the project directory:

    ```bash
    cd workoutbuddy
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up environment variables:

    Create a `.env` file in the root directory and add the following values:

    ```bash
    MONGO_URI=your_mongodb_connection_string_here
    JWT_SECRET=your_jwt_secret_here
    ```

5. Start the backend server:

    ```bash
    npm run server
    ```

6. Run the frontend:

    ```bash
    npm run dev
    ```

   This will start the development server on `localhost:3000`.

## Usage

- Register or log in to create an account.
- Add workouts, set fitness goals, and track your progress.
- Manage your workout history and view statistics.

## License

This project is licensed under the MIT License.
