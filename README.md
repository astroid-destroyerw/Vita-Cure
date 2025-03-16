# VitaCure - Healthcare Management System

A modern healthcare management system built with React.js and Node.js that streamlines hospital operations, appointment booking, and patient management.

## Features

- OPD Queue Management
- Online Appointment Scheduling
- Patient Profile Management
- Hospital Dashboard
- Lab Test Booking
- Real-time Notifications

## Tech Stack

- Frontend: React.js, TailwindCSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Deployment: Docker

## Screenshots

### Home Page
![Home Page](client/public/screenshots/home.png)

### Hospital Dashboard
![Dashboard](client/public/screenshots/dashboard.png)

### Appointment Booking
![Appointment](client/public/screenshots/appointment.png)

### Lab Tests
![Lab Tests](client/public/screenshots/labtest.png)

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/[astroid-destroyerw]/vitacure.git
cd vitacure
```

2. Install dependencies:
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables:
```bash
# Create .env file in server directory
cd server
echo "MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=8080" > .env
```

4. Run with Docker:
```bash
docker compose build
docker compose up
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:8080

## Author

Created by [Mohit Meharde]
- GitHub: [astroid-destroyerw](https://github.com/astroid-destroyerw)
- LinkedIn: [Mohit Meharde](https://linkedin.com/in/mohitmeharde19)

## License

This project is open source and available under the [MIT License](LICENSE).


