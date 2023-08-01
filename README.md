# Socially-Social-Media

## Overview

The Social Media App is a web-based application designed to provide users with a platform to connect, share, and engage with others through various social media features. This README file serves as a guide to help developers understand the project structure and other essential information.
Features

The Social Media App includes the following features:

   1. User Registration and Authentication: Users can create an account and securely log in using their credentials.

   2. Profile Management: Users can create and manage their profiles by adding personal information, profile pictures, and cover photos.

   3. Post Creation and Interaction: Users can create posts containing text, images, and videos. They can also like, comment on, and share posts from other users.

   4. Friend/Follow System: Users can send and accept friend/follow requests, view their friends/followers list, and receive notifications about friend activities.

   5. News Feed: Users have access to a personalized news feed that displays posts from their friends and followed accounts.

    

## Tech Stack

The Social Media App is built using the following technologies:


    Frontend: HTML, CSS, JavaScript, React, React Router, Redux toolkit, Redux persistent, Formik & yup, React Dropzone
    
    Backend: Node.js, Express.js, Mongoose, Multer
    
    Database: MongoDB
    
    Authentication: JSON Web Tokens (JWT)
    
    

## Installation

To set up the Social Media App locally, follow these steps:

 Clone the repository: 
 ` git clone https://github.com/PranK14/Socially-Social-Media.git `
 
 Install dependencies: 
    ` npm install `
   
  Set up environment variables:
        Create a .env file in the server directory.
        
        Define the following variables in the .env file:
        
            MONGODB_URI: MongoDB connection string
            
            JWT_SECRET: Secret key for JWT authentication
            
            PORT: Port number for the server (default: 3001)

            
   Start the backend in server: 
   ` nodemon index.js `
   
 Start the development server in client:
    `npm start `
    
