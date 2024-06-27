Features
Create: Add new form entries.
Read: View a list of all form entries.
Update: Edit existing form entries.
Delete: Remove form entries.
Technologies Used
Backend: Node.js with Express.js
Frontend: React.js
Database: MongoDB
Other: Mongoose for MongoDB object modeling, Axios for HTTP requests
Getting Started
Prerequisites
Node.js and npm (Node package manager) installed
MongoDB installed and running
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/chance12regine/full-stack-operation.git
cd crud-form-app
Install backend dependencies:

bash
Copy code
cd backend
npm install
Install frontend dependencies:

bash
Copy code
cd ../frontend
npm install
Configuration
Create a .env file in the backend directory and add the following:
makefile
Copy code
PORT=5000
MONGODB_URI=your_mongodb_connection_string
Running the Application
Start the backend server:

bash
Copy code
cd backend
npm start
Start the frontend server:

bash
Copy code
cd ../frontend
npm start
Open your web browser and go to http://localhost:3000 to see the application running.

API Endpoints
Backend
GET /api/forms: Retrieve all form entries.
POST /api/forms: Create a new form entry.
GET /api/forms/:id: Retrieve a single form entry by ID.
PUT /api/forms/:id: Update a form entry by ID.
DELETE /api/forms/:id: Delete a form entry by ID.
Frontend
The frontend interacts with the backend API to perform CRUD operations and display the form entries.

Project Structure
Backend
bash
Copy code
backend/
├── models/
│   └── Form.js
├── routes/
│   └── forms.js
├── controllers/
│   └── formController.js
├── .env
├── server.js
└── package.json
Frontend
css
Copy code
frontend/
├── src/
│   ├── components/
│   │   ├── Form.js
│   │   ├── FormList.js
│   │   └── FormItem.js
│   ├── App.js
│   ├── index.js
│   └── api.js
├── public/
│   └── index.html
└── package.json
Contributing
Contributions are welcome! Please create an issue or submit a pull request for any features, bug fixes, or improvements.
