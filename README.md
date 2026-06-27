# Job Portal

## Overview

The Job Portal is a full-stack web application developed to simplify the recruitment process for both job seekers and employers. It provides a single platform where users can search for jobs, apply for suitable positions, and track their applications, while administrators can manage job postings, categories, and user activities.

The application is built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) and follows the MVC (Model-View-Controller) architecture to keep the codebase organized and maintainable. Material UI is used to build a responsive interface that supports both dark and light themes.

---

## Purpose

The main objective of this project is to provide a simple and secure recruitment platform that helps:

* Job seekers search and apply for jobs easily.
* Employers manage job listings efficiently.
* Administrators monitor the overall activity of the platform.

---

## Features

### User Features

* User registration and login
* Secure JWT-based authentication
* Search jobs using keywords
* Filter jobs by category and location
* Apply for available jobs
* View application history
* Responsive dashboard
* Dark and Light theme support
* Toast notifications for important actions

### Admin Features

* Admin dashboard
* Create, update, and delete job postings
* Manage job categories
* View application statistics
* Export job-related data in CSV format
* Paginated data tables
* Sidebar navigation for quick access

---

## Authentication

The application uses JSON Web Tokens (JWT) for authentication along with cookies for maintaining user sessions securely. Protected routes ensure that only authenticated users can access authorized resources.

---

## Technologies Used

### Frontend

* React.js
* Material UI (MUI)
* Bootstrap
* CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT (JSON Web Tokens)
* Cookies

### Form Validation

* Formik
* Yup

### Other Libraries

* React Router
* React Toastify
* CSV Export

---

## Project Structure

```
job-portal/

│

├── client/
│ ├── public/
│ └── src/
│ ├── components/
│ ├── context/
│ ├── pages/
│ ├── styles/
│ └── utils/

│

├── server/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ └── config/

│

├── README.md

└── package.json
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/job-portal.git
```

### Navigate to the project folder

```bash
cd job-portal
```

### Install dependencies

Backend

```bash
cd server
npm install
```

Frontend

```bash
cd ../client
npm install
```

---

## Environment Variables

Create a `.env` file inside the server directory and add the following variables.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## Running the Project

Start the backend server.

```bash
npm run server
```

Start the frontend.

```bash
npm start
```

The application will be available at:

```
http://localhost:3000
```

---

## How to Use

### For Job Seekers

1. Register a new account.
2. Login using your credentials.
3. Browse available jobs.
4. Search or filter jobs by category and location.
5. Apply for suitable jobs.
6. View your application history.

### For Administrators

1. Login using admin credentials.
2. Create and manage job postings.
3. Manage job categories.
4. View application statistics.
5. Export reports in CSV format.

---

## Future Improvements

Some features that can be added in future versions include:

* Resume upload support
* User profile management
* Email notifications
* Interview scheduling
* Real-time notifications
* Job recommendation system

---

## License

This project is licensed under the MIT License.

---

## Author

**Jyotishka Deb**

