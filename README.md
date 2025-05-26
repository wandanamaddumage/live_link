# Live-Link

A full-stack Realtime Chat App built with the MERN stack, enhanced by Socket.io for real-time communication, and styled with TailwindCSS + Daisy UI.

## Highlights

- User Registration & Login (JWT-based authentication)
- Secure Authentication & Logout
- Real-Time Messaging via Socket.io
- Online User Presence Indicator
- Cloudinary Integration for Image Uploads
- Global State Management with Zustand
- Client & Server-Side Error Handling
- Responsive UI using TailwindCSS & Daisy UI

## Getting Started

1. Clone the repository

```
git clone https://github.com/wandanamaddumage/live-link.git
cd live-link
```

2. Install dependencies
   For both frontend and backend:

```
# In the backend folder
npm install

# Move to frontend and install

cd frontend
npm install
```

## Setup Environment Variables

Create a .env file in the server directory and add:

```
MONGODB_URI=your_mongo_connection_string
PORT=5001
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

## Build the App

In the client folder:

```
npm run build
```

## Start the App

In the server folder:

```
npm start
```

The app will start running at: http://localhost:5001
