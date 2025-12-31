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
