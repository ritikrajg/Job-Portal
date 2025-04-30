# Job Portal Application

A full-stack job portal application built with React, Node.js, and MongoDB, providing a platform for job seekers and employers to connect.

## Features

- User Authentication (Job Seeker & Employer)
- Job Posting and Management
- Job Search and Filtering
- Resume Upload and Management
- Application Tracking System
- Real-time Notifications
- Responsive Design

## Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Redux (State Management)
- Axios (API Calls)

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- RESTful API

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install
```

3. Set up environment variables
Create a `.env` file in the backend directory with:
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the development servers
```bash
# Backend
cd backend
npm run dev

# Frontend
cd frontend
npm run dev
```

## Project Structure

```
backend/
├── controllers/    # Request handlers
├── models/         # Database models
├── routes/         # API routes
├── middlewares/    # Custom middleware
├── utils/          # Utility functions
└── index.js        # Server entry point

frontend/
├── src/
│   ├── components/ # Reusable components
│   ├── pages/      # Page components
│   ├── store/      # Redux store
│   ├── utils/      # Utility functions
│   └── App.js      # Main component
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
"Developed a full-stack job portal application using MERN stack (MongoDB, Express.js, React, Node.js) with features including user authentication, job posting, and application tracking system."
"Implemented RESTful APIs with JWT authentication, enabling secure user interactions and real-time notifications for job applications and updates."
"Built a responsive frontend using React and Tailwind CSS, incorporating Redux for state management and implementing advanced search and filtering capabilities for job listings."