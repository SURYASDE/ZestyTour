Zesty Tour Node.js License
🌟 Features

    Beautiful Landing Page: Modern design with popular destinations
    Trip Planning Wizard: Multi-step form for creating personalized trips
    Backend API: Node.js server with SQLite database
    Responsive Design: Works on desktop and mobile devices
    Interactive UI: Smooth animations and user-friendly interface

🚀 Live Demo

View Live Demo
📋 Prerequisites

    Node.js (v14 or higher)
    npm (comes with Node.js)
    Python 3 (for serving frontend files)

🛠️ Installation

Clone the repository

git clone https://github.com/YOUR_USERNAME/zesty-tour-app.git
cd zesty-tour-app

Install dependencies

npm install

🏃‍♂️ Running the Application
Option 1: Run both servers separately

Start the Backend Server (in one terminal):

npm start

The backend will run on http://localhost:3001

Start the Frontend Server (in another terminal):

cd frontend
python -m http.server 8000

    The frontend will be available at http://localhost:8000

Option 2: Use provided scripts

    Windows: Run start-app.bat or start-app.ps1
    Debug mode: Run debug.bat for debugging

🌐 Accessing the Application

    Open your web browser
    Navigate to: http://localhost:8000
    You should see the Zesty Tour landing page

📡 API Endpoints

The backend provides the following API endpoints:

    GET /api/recipes - Get all recipes
    POST /api/recipes - Add a new recipe
    POST /api/tour-details - Save tour planning details

📁 Project Structure

zesty-tour-app/
├── backend/
│   ├── server.js          # Node.js backend server
│   └── db.sqlite         # SQLite database
├── frontend/
│   ├── index.html         # Main landing page
│   ├── plan.html          # Trip planning wizard
│   ├── app.js            # Frontend JavaScript
│   └── images/           # Destination images
├── package.json           # Node.js dependencies
├── README.md             # This file
└── .gitignore           # Git ignore file

🎨 Features Overview
Landing Page (index.html)

    Beautiful hero section with search functionality
    Popular destinations with ratings and descriptions
    Category-based exploration
    Trip planning call-to-action

Trip Planning (plan.html)

    Multi-step wizard interface
    Package selection (Basic, Standard, Premium, Luxury)
    Age group and travel style preferences
    Budget slider with real-time calculation
    Transportation options
    Personalized recommendations

Backend Features

    SQLite database for data persistence
    RESTful API endpoints
    CORS enabled for frontend communication
    Error handling and validation

🛠️ Technologies Used

    Frontend: HTML5, CSS3 (Tailwind CSS), JavaScript
    Backend: Node.js, Express.js
    Database: SQLite3
    Icons: Font Awesome
    Styling: Tailwind CSS

🔧 Development

To modify the application:

    Edit HTML files in the frontend/ directory
    Modify JavaScript in frontend/app.js
    Update backend logic in backend/server.js
    Restart servers after making changes

🐛 Troubleshooting
If the backend won't start:

    Make sure Node.js is installed
    Run npm install to install dependencies
    Check if port 3001 is available

If the frontend won't load:

    Make sure Python is installed
    Check if port 8000 is available
    Try a different port: python -m http.server 8080

If images don't load:

    Make sure all image files are in the frontend/images/ directory
    Check that the image paths in HTML files are correct

📝 Contributing

    Fork the repository
    Create your feature branch (git checkout -b feature/AmazingFeature)
    Commit your changes (git commit -m 'Add some AmazingFeature')
    Push to the branch (git push origin feature/AmazingFeature)
    Open a Pull Request

📄 License

This project is licensed under the ISC License.
🙏 Acknowledgments

    Tailwind CSS for the beautiful styling
    Font Awesome for the icons
    Unsplash for the beautiful images
# ZestyTour
A modern travel planning application featuring a beautiful UI and a personalized Trip Planning Wizard 
