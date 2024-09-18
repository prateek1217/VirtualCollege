
Virtual College is a web application built using the MERN stack to manage college academic work by shifting data from hardcopy to softcopy. The application provides real-time communication between students and the administration and sends email credentials to users using Nodemailer. The UI is built using Material-UI, ensuring a clean and responsive interface.

Features
Data Management: Replace hardcopy records with a MongoDB-based softcopy database for easy access and management.
Real-Time Communication: Leverage Socket.io to enable instant messaging between enrolled students and the administration.
Email Integration: Automatically email credentials to new users using Nodemailer.
Responsive Design: Built using Material-UI for a modern and responsive user experience.
Tech Stack
Frontend: React, Material-UI
Backend: Node.js, Express.js
Database: MongoDB
Real-Time Communication: Socket.io
Email Service: Nodemailer


Installation & Setup
Clone the repository:
git clone https://github.com/your-username/virtual-college.git
cd virtual-college


Install dependencies:

npm install


Set up environment variables. Create a .env file in the root directory and add the following:
MONGODB_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
EMAIL_USER=your-email
EMAIL_PASS=your-email-password


Start the development server:
npm run dev


Usage
Admin: Can add new students, manage academic records, and send credentials via email.
Students: Can log in with the provided credentials, view academic records, and communicate with the administration in real time.
