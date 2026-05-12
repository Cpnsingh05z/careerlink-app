# CareerLink

CareerLink is a professional networking platform inspired by LinkedIn, built using the MERN stack.
The platform allows users to create professional profiles, connect with others, share posts, interact through comments and likes, and communicate through messaging features.

---

## Features

- User Authentication & Authorization
- Secure Password Hashing with bcrypt.js
- Professional Profile Management
- Create and Share Posts
- Image Uploads using Cloudinary
- Like and Comment System
- Messaging Functionality
- Notifications System
- Connection Requests & Networking
- Suggested Users
- Trending Topics
- Education & Experience Sections
- Responsive UI
- Dark Mode Support

---

## Tech Stack

**Frontend**
- React.js
- Tailwind CSS

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB

**Authentication & Security**
- JWT Authentication
- bcrypt.js

**Media Storage**
- Cloudinary

---

## Installation

1. Clone the repository
```bash
git clone https://github.com/Cpnsingh05z/careerlink-app.git
```

2. Navigate to the project directory
```bash
cd careerlink-app
```

3. Install backend dependencies
```bash
cd backend && npm install
```

4. Install frontend dependencies
```bash
cd ../frontend && npm install
```

5. Start the backend server
```bash
cd .. && npm run dev:backend
```

6. Start the frontend server
```bash
npm run dev:frontend
```

---

## Environment Variables

Create a `.env` file inside the `backend` folder and add the following:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Create a `.env` file inside the `frontend` folder and add the following:

```env
VITE_API_URL=http://localhost:5000
```

---

## Future Improvements

- Advanced search and filtering
- AI-powered recommendations
- Job posting functionality
- Email notifications
- Video post support

---

## Learning Outcomes

This project helped improve my understanding of:

- Full-stack MERN development
- REST API architecture
- Authentication & authorization
- Cloudinary integration
- Database schema design
- Responsive UI development
- State management and application structure
