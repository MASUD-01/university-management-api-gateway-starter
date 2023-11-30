# University Management API Gateway

Welcome to the University Management API Gateway project, a tutorial project designed to help you level up your web development skills as part of the "Programming Hero Next Level Web Development Course."

# Project Overview:

This GitHub repository hosts a comprehensive tutorial and project for building a University Management API Gateway. Whether you're a beginner or an experienced developer, this project offers step-by-step instructions, code examples, and best practices to guide you through the process. By the end of this hands-on tutorial, you'll have a functional API Gateway that includes integration with two essential services: um-auth (University Management Auth Service) and um-core (University Management Core Service).

# What You'll Learn:

Setting up a Node.js project structure.
Creating a robust API Gateway using Express.js.
Implementing proxy routes to route requests to um-auth and um-core services.
Handling authentication and core functionalities seamlessly.
Understanding best practices in API Gateway development.
Technologies Used:
Express.js: A web application framework for Node.js that makes building APIs and web applications a breeze.
Node.js: A JavaScript runtime that allows you to build scalable network applications.
Redis: An open-source, in-memory data store used for caching and session management.
Multer: Middleware for handling file uploads in Node.js applications.
Cloudinary: A cloud-based media management solution for storing, managing, and delivering images and videos.

# Why This Project Matters:

API Gateways are critical components in modern web development, enabling efficient and secure communication between various microservices and clients. This project not only teaches you valuable skills but also provides you with a practical application of those skills in a real-world scenario.

credentials for .env

NODE_ENV=development
PORT=3030

JWT_SECRET=programming-hero
REDIS_URL='redis://localhost:6379'
AUTH_SERVICE_URL=http://localhost:3001/api/v1
CORE_SERVICE_URL=http://localhost:3002/api/v1
