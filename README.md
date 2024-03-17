# Sharify - Social Networking Website

## Overview
This project is a social networking website where users can share the music they are currently listening to by uploading Spotify links. It utilizes the MERN (MongoDB, Express.js, React.js, Node.js) stack along with the Spotify API and SendGrid API for integration. The application is deployed using Render and Netlify.

## Features
- Users can sign up and log in to their accounts.
- Users can upload Spotify links to share the music they are listening to.
- Other users can view and listen to shared music links.
- Users receive notifications through SendGrid API for various activities such as likes, comments, etc.

## Tech Stack
- MongoDB: Database for storing user information and music links.
- Express.js: Backend framework for handling server-side logic and API requests.
- React.js: Frontend library for building user interfaces.
- Node.js: JavaScript runtime environment for running server-side code.
- Spotify API: Integration for retrieving and sharing music links.
- SendGrid API: Integration for sending email notifications.
- Render: Cloud platform for hosting and managing backend services.
- Netlify: Platform for deploying and hosting frontend application.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/your/repository.git`
2. Navigate to the project directory: `cd social-music-network`
3. Install dependencies:
   - Backend: `cd backend && npm install`
   - Frontend: `cd frontend && npm install`
4. Set up environment variables:
   - Create a `.env` file in the `backend` directory and add necessary environment variables such as MongoDB URI, Spotify API credentials, and SendGrid API key.
5. Start the backend server: `npm start` (inside the `backend` directory)
6. Start the frontend development server: `npm start` (inside the `frontend` directory)

## Deployment
- Backend: Deploy the backend server to Render or any preferred hosting service.
- Frontend: Deploy the frontend application to Netlify or any preferred hosting service.
