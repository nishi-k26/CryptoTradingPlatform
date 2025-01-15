# README

This project is a Crypto Trading Full-Stack Application with a **backend** built using **Spring Boot** and a **frontend** developed in **ReactJS**. Follow the steps below to set up and run the application.

[Watch the video on Google Drive](https://drive.google.com/file/d/19boJ3vLcjpijn_nGIr9wEflrWLsnqooz/view?usp=sharing)

## Prerequisites

Ensure you have the following installed on your system:

1. **Node.js** and **npm**: [Download and install Node.js](https://nodejs.org/)
2. **Java Development Kit (JDK)**: Version 8 or later
3. **Maven**: [Download and install Maven](https://maven.apache.org/)
4. **IntelliJ IDEA**: Recommended for building and running the backend

## Project Structure

- **frontend/**: Contains the ReactJS code for the frontend.
- **backend/**: Contains the Spring Boot code for the backend.

---

## Steps to Run the Application

### 1. Setup and Run the Frontend

1. Open a terminal and navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. The frontend should now be running. Typically, it is available at `http://localhost:3000`.

### 2. Setup and Run the Backend

1. Open **IntelliJ IDEA** and load the `backend` folder as a project.
2. Ensure all required binaries and dependencies are installed. In the terminal within IntelliJ or your system terminal, run:
   ```bash
   mvn clean install
   ```
3. Start the backend server:
   ```bash
   mvn spring-boot:run
   ```
4. The backend should now be running. By default, it is available at `http://localhost:8080`.

---

## Accessing the Application

1. Open your browser and navigate to the frontend URL, usually `http://localhost:3000`.
2. The frontend communicates with the backend at `http://localhost:8080`.

---
