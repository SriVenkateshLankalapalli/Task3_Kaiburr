# Task3_Kaiburr
This is a React 19 web UI built with TypeScript and Ant Design for managing tasks in the backend application created in Task 1. The UI provides a user-friendly and accessible interface for interacting with tasks stored in a MongoDB database via a REST API.
Task Management Web UI
This is a React 19 web UI built with TypeScript and Ant Design for managing tasks in the backend application created in Task 1. The UI provides a user-friendly and accessible interface for interacting with tasks stored in a MongoDB database via a REST API.

Features
✅ Create new tasks
✅ View all tasks
✅ Search tasks by name
✅ Delete tasks
✅ Run shell commands within Kubernetes pods
✅ View command execution output

Tech Stack
React 19 (Latest version)

TypeScript (For type safety and maintainability)

Ant Design (Modern UI components)

Axios (For API communication)

React Query (For efficient data fetching)

Installation & Setup
Clone the repository:

sh
Copy
Edit
git clone https://github.com/your-repo/task-management-ui.git
cd task-management-ui
Install dependencies:

sh
Copy
Edit
npm install
Start the development server:

sh
Copy
Edit
npm run dev
The application should now be running at http://localhost:3000

Backend API
Ensure that the backend service (Task 1) is running before using the UI. Update the .env file with the correct backend API URL:

env
Copy
Edit
REACT_APP_API_URL=http://localhost:8080/api
Screenshots
(Screenshots showing task creation, search, deletion, command execution, and output should be embedded here.)

Deployment
To build and deploy the project:

sh
Copy
Edit
npm run build
Serve the static files using Vercel, Netlify, or a custom server.
