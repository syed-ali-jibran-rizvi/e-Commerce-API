
---

# E-Commerce API

This repository contains the source code for an E-Commerce API built using Node.js, Express, and MongoDB.

## Table of Contents
1. [Setup](#setup)
2. [API Documentation](#api-documentation)
3. [Design Decisions](#design-decisions)

## Setup

### Prerequisites
- Node.js installed on your machine
- MongoDB server running locally or accessible remotely

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/syed-ali-jibran-rizvi/e-commerce-api.git
   ```
2. Navigate to the project directory:
   ```bash
   cd e-commerce-api
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add the following environment variables:
     ```
     PORT=3000
     API_URL=/api/v1
     CONNECTION_STRING=mongodb+srv://sajr:RcY7GrbA11h9W4TB@cluster0.jc7okdl.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
     ```
5. Start the server:
   ```bash
   npm start
   ```

## API Documentation

### Base URL
The base URL for accessing the API endpoints is `/api/v1`.


## Design Decisions

- **Express Framework**: Chosen for its simplicity and robustness in building web applications.
- **MongoDB**: Selected as the database due to its flexibility and scalability, suitable for an E-Commerce application where data needs to be stored and queried efficiently.
- **JWT Authentication**: Implemented JSON Web Token (JWT) authentication to secure the API endpoints and allow access to authorized users only.
- **RESTful Architecture**: Designed the API endpoints following RESTful principles for better organization and maintainability.
 Contact syedalijibranrizvi@gmail.com
---
