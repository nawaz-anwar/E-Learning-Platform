## E-Learning Platform: Enroll, Learn, and Grow
Welcome to the E-Learning Platform! This project aims to provide a robust backend API for an online learning platform. Users can register, enroll in courses, manage their profiles, and access a wide range of educational resources. This README will guide you through setting up and using the project.

## Demo
[Include a link to the live demo or video demonstration of your project, if available.]

## Technologies Used
Node.js
Express.js
MongoDB
Mongoose
JWT (JSON Web Tokens)
Cloudinary (for image storage)

## Features
User registration with email verification
User authentication using JWT tokens
Profile management with the ability to update name, email, password, and profile picture
Course management for superadmin users, including CRUD operations
Course enrollment with validation to prevent duplicate enrollments
Filtering and pagination for course listings
Integration with Cloudinary for profile picture storage

## Getting Started
To get started with the E-Learning Platform, follow these steps:

Clone the repository to your local machine.
Install dependencies using npm install.
Set up environment variables, including MongoDB connection string, Cloudinary credentials, and JWT secret.
Run the server using npm start.
Access the API endpoints using a tool like Postman or curl.

## Usage
Once the server is running locally, you can use the following API endpoints:

/api/v1/user/register: Register a new user.
/api/v1/user/login: Log in an existing user.
/api/v1/user/profile: View and update user profile.
/api/v1/course/add: Add a new course (superadmin only).
/api/v1/course/get: Get a list of courses with filtering and pagination.
/api/v1/course/enroll/:courseId: Enroll in a course.
/api/v1/course/enrolledCourses: View enrolled courses.


## Contributing
Contributions to the E-Learning Platform are welcome! Please fork the repository, make your changes, and submit a pull request. Be sure to follow the contribution guidelines and code of conduct.

## License
This project is licensed under the MIT License.

## Acknowledgements
We would like to thank the following for their support and inspiration during the development of this project:

OpenAI
Vercel
MongoDB
Cloudinary
stack overflow

## Contact
For inquiries or collaboration opportunities, please contact us at cse.nawaz.2003@gmail.com.
