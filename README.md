# Maker Hours

![logo.png](https://github.com/DiazMarco2005/PooProyecto/blob/main/DesignProcess/banding/logotxt.png)

# Scholarship Hours Control Platform

A full-stack platform designed to manage and track scholarship working hours, providing a structured way to register, validate, and administer user activity. The system simulates a real-world environment with a clear separation between frontend, backend, and database layers.

---

##  Project Overview

This project is a **full-stack client-server application** built to manage scholarship hour records efficiently. It allows users to log their working hours while administrators can manage, validate, and monitor the recorded data.

The application follows a modular architecture and is designed to be easily deployable using containerization.

---

## Architecture

The project is structured into three main components:

- **shc-client**: Frontend application built with React Native Expo.
- **shc-server**: Backend REST API developed using Spring Boot.
- **shc-db**: MariaDB database configuration and initialization.

Each component runs independently and communicates through well-defined interfaces.

---

## Technologies Used

### Backend
- Java 11+
- Spring Boot
- RESTful API
- Maven

### Frontend
- React Native (Expo)

### Database
- MariaDB
- SQL

### DevOps / Tooling
- Docker
- Docker Compose

---

##  Features

- User authentication and authorization
- Registration and management of scholarship working hours
- Backend API handling business logic and data persistence
- Relational database modeling
- Fully dockerized environment for local development and testing

---

## Getting Started

### Prerequisites

- Docker
- Docker Compose
- Node.js
- Java JDK (11 or higher)
- Maven

---

### Installation & Execution

1. **Clone the repository**
   ```bash
   git clone https://github.com/eldmark/PooProyecto.git
   cd PooProyecto
2. Build the backend
   ```bash
   cd shc-server
   mvn clean install


3. Run the complete environment
   ```bash
   docker-compose up --build

### Service Ports

Frontend (React Native Expo): http://localhost:5173

Backend (Spring Boot API): http://localhost:8080

Database (MariaDB): localhost:3306

### Frontend Usage

1. To start the frontend in web mode:
   ```bash
   cd shc-client
   npx expo start --web --port 5173

### API

The backend exposes a REST API that handles authentication and business logic.
Endpoints can be tested using tools such as Postman.

API documentation: [documentation] (https://github.com/DiazMarco2005/PooProyecto/blob/main/shc-server/src/main/java/com/shc/shc_server/controller/reference.md)

### Database
The MariaDB database is automatically initialized using Docker Compose.
You can access it using tools such as MySQL Workbench or via terminal-based SQL clients.

### Design

UI designs were created using Figma.

Design link: [Design](https://www.figma.com/design/KfhdDIbVsgEq5CshWKiQGE/Poo-Design?node-id=27-295&t=G8gTddLDvlSw19Ms-1)

Individual Contributions

This project was developed as a team collaboration.
eldmark: (Marco Díaz) commits DiazMarco2005
- Design process with figma
- Profile Screen
- Home screen
   - Using async calls to show information of the user
- Statistics on Profile Module
- Published Activities frontend


🔁 GitHub Account Note

This repository was originally developed using a different GitHub account ( DiazMarco2005 ).
The project was later transferred to this account to consolidate our professional portfolio.
All commits and contributions belong to the original authors of the project.

📄 License

This project is licensed under the GPL-2.0 License.
See the LICENSE file for more details.


