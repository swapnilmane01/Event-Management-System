# Event Management System

![CI Status](https://img.shields.io/github/actions/workflow/status/Gaurav241/Event-Management-System/ci.yaml?branch=master)
![Production](https://img.shields.io/github/deployments/Gaurav241/Event-Management-System/production)

## Table of Contents

1. [Introduction](#introduction)
2. [Screenshots](#screenshots)
    1. [User](#user)
    2. [Admin](#admin)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Contributing](#contributing)
6. [Contact](#contact)
7. [License](#license)

## Inroduction

The Virtual Event Management System is a web application built with React (or Next.js) that allows users to organize, manage, and participate in virtual events. The application includes features such as user authentication, event creation, event management, and participation tracking.

## Screenshots

### User
#### Dashboard
![Dashboard](visuals/ss/UserDashboard.png)
#### SignUp
![SignUp](visuals/ss/SignUp.png)
#### User Dashboard MyEvent
![User Dashboard MyEvent](visuals/ss/UserDashboardMyEvent.png)

### Admin
#### Dashboard
![Page](visuals/ss/AdminDashboard.png)
#### Add Event
![Add Event](visuals/ss/AdminAddEvent.png)

## Technologies Used

- **Next.js**: A React framework that enables server-side rendering and static site generation for building modern web applications.
- **React**: A JavaScript library for building user interfaces, particularly single-page applications with a component-based architecture.
- **MongoDB**: A NoSQL database used for storing event and user information with flexible and scalable document-oriented storage.
- **Redux**: A state management library for JavaScript applications, allowing predictable state management with a single store.
- **Passport**: Middleware for Node.js that provides a comprehensive suite of authentication strategies for secure user authentication.
- **SWR**: A React Hooks library for data fetching, caching, and synchronization, improving the efficiency and user experience of data handling.
- **Material Icons**: A library of icons from Google that provides a consistent and modern look for user interfaces.
- **Bootstrap**: A popular CSS framework for responsive design and modern UI components, facilitating the creation of mobile-first and accessible web applications.

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Clone the Repository

Run the following command to clone the repository:
```
git clone https://github.com/Gaurav241/Event-Management-System.git
cd Event-Management-System
```
### Install Dependencies

Install the necessary dependencies with:
```
npm install
```
### Configure Environment Variables

1. Copy `.env.example` to `.env`:
```
cp .env.example .env
```
2. Edit the `.env` file to include your MongoDB connection string and JWT secret. Update the following variables:
```
TOKEN_SECRET=your_token
MONGO_URL=mongodb_database_address
```
3. Generate a secure token secret using the following command and set it in the `.env` file:
```
node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"
```
4. Replace `your_token` with the generated token and `mongodb_database_address` with your MongoDB connection string.

### Start the Development Server

Start the server with:
```
npm run dev
```
The application will be running on `http://localhost:3000`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements. Your feedback and contributions help improve the project!

## Contact

For any questions or inquiries, please contact [gaurav.govinda2420@gmail.com](mailto:gaurav.govinda2420@gmail.com).

## License

Distributed under the MIT License. See [LICENSE](LICENSE.txt) for more information.
