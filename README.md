# U-Snap: Interactive User Management with Tiles

**U-Snap** is a full-stack web application for creating, managing, and storing user data. The application assigns unique IDs to each user and displays the data in an interactive tile-based format. Built with a modern tech stack for scalability, consistency, and performance.

## Features
- Create, update, and delete users with ease.
- Display user data in dynamic, interactive tiles.
- Unique ID generation for each user.
- Real-time API interaction with a Go backend.
- Persistent data storage using PostgreSQL.
- Dockerized for consistent development and deployment environments.

## Tech Stack
- **Backend**: [Go](https://golang.org/) (for server-side logic)
- **Frontend**: [Next.js](https://nextjs.org/), [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/)
- **Database**: [PostgreSQL](https://www.postgresql.org/) (for relational data management)
- **API Communication**: [Axios](https://axios-http.com/) (for handling API requests)
- **Containerization**: [Docker](https://www.docker.com/) (for environment consistency)

## Project Structure
```bash
|-- backend
    |-- main.go             # Go server handling API requests
    |-- go.mod              # Go dependencies
    |-- go.sum              # Dependency versioning file
    |-- go.dockerfile       # Dockerfile for the Go server
|-- frontend
    |-- components
        |-- CardComponent.tsx   # Displays user data in interactive tile format
        |-- UserInterface.tsx   # User interface for managing user data
    |-- pages
        |-- index.tsx           # Main page of the application
    |-- public
        |-- [backendName]logo.svg  # Dynamic backend logos

## Installation
### Prerequisites
