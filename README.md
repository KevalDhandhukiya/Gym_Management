# Gym Management System

A full-stack web application for managing gym memberships. This system allowing administrators to perform CRUD (Create, Read, Update, Delete) operations on member records efficiently.

## Features

-   **Add New Members**: Register new gym members with personal details (Name, Email, Phone, Gender, DOB) and membership type (Basic, Premium, VIP).
-   **View All Members**: Display a list of all registered members with their key details.
-   **Member Details**: View detailed information for a specific member.
-   **Edit Member**: Update existing member information.
-   **Delete Member**: Remove members from the system.
-   **Responsive Design**: Built with Bootstrap for a responsive user interface.

## Tech Stack

**Frontend:**
-   React.js
-   React Router DOM
-   Bootstrap & Bootstrap Icons

**Backend:**
-   Node.js
-   Express.js

**Database:**
-   MongoDB (with Mongoose)

## Getting Started

### Prerequisites
-   Node.js installed
-   MongoDB installed and running locally (or a cloud Atlas URI)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/keval2310/Gym-Management.git
    cd Gym-Management
    ```

2.  **Setup Backend**
    ```bash
    cd "Back End"
    npm install
    # Ensure MongoDB is running on localhost:27017 or update connection string in index.js
    npm start
    ```
    The server will run on `http://localhost:4000`.

3.  **Setup Frontend**
    ```bash
    cd "Front End"
    npm install
    npm start
    ```
    The application will run on `http://localhost:3000` (or 3001 if port 3000 is busy).
