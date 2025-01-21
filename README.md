# User Management Dashboard

Welcome to the **User Management Dashboard**—a simple yet functional web application that allows users to view, add, edit, and delete user details. This application interacts with the JSONPlaceholder API to fetch and manipulate user data, demonstrating CRUD (Create, Read, Update, Delete) operations. The responsive and clean user interface ensures a seamless experience across devices. Users can navigate through the dashboard to manage details such as ID, First Name, Last Name, Email, and Department efficiently.

## Features
- **View Users**: Displays a list of users fetched from the `/users` endpoint of the JSONPlaceholder API.
- **Add Users**: Includes a form to add new users, with simulated successful responses.
- **Edit Users**: Fetches current user details, allowing edits to be saved via the API.
- **Delete Users**: Enables deletion of users by sending delete requests to the API.
- **Error Handling**: Displays appropriate error messages if API requests fail.
- **Bonus Features**:
  - Client-side validation for user input forms.
  - Responsive design for optimal usage across devices.

## Deployment
The project is deployed and accessible at: [User Management Dashboard](https://spiffy-kheer-bd1ab8.netlify.app/).

## Tech Stack
- **Frontend**: React.js
- **HTTP Requests**: Axios
- **API**: JSONPlaceholder

## Setup Instructions
1. Clone the repository using:
   ```bash
   git clone <repository-link>
cd MERN-CRUD <br>
cd client<br>
npm install<br>
npm start

## Challenges and Reflections
During development, managing API integration with simulated responses required careful handling of asynchronous requests and user feedback. Responsive design was implemented to ensure usability across different devices. Given more time, advanced features like pagination or infinite scrolling could be integrated for enhanced usability.

### Author
-Gaurav Shukla
(Full-Stack Developer)
