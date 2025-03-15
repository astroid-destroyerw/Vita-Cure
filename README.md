# VitaCure - Healthcare Management System

A modern healthcare management system built with React.js and Node.js that streamlines hospital operations, appointment booking, and patient management.

##🚀 About the Project

When seconds matter in a medical emergency, delays can be frustrating, stressful, and even life-threatening. Hospitals struggle with bed allotment, patients lack real-time updates, and ambulance coordination is often chaotic.

VitaConnect fixes this. It's an AI-powered, real-time hospital & emergency management system that connects:
✅ Patients & Families – Instantly request emergency help & track progress.
✅ Hospitals & Doctors – Automate patient prioritization & optimize resources.
✅ Ambulance Services – Ensure faster response & seamless coordination.

Whether it's urgent care, hospital queue management, or digital medical records, VitaConnect does it all—without the hassle.

## Tech Stack

- Frontend: React.js, TailwindCSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Deployment: Docker

##🎯 Future Enhancements

🔹 Expand to rural hospitals with offline support.
🔹 Add multilingual support for better accessibility.
🔹 Use AI to predict emergency hotspots & prevent overcrowding.

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

Created by [Mohit Meharde] with the help of [Anuj Dave, Navneet Sharma, Siddhant Purohit]
- GitHub: [astroid-destroyerw](https://github.com/astroid-destroyerw)
- LinkedIn: [Mohit Meharde](https://linkedin.com/in/mohitmeharde19)

## License

This project is open source and available under the [MIT License](LICENSE).


