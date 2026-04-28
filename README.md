💰 Full-Stack Expense Tracker with Budget Management

A modern full-stack expense tracking platform with authentication and real-time analytics. Built with React, Node.js, and PostgreSQL.

🚀 Features
🔐 Authentication
Secure user registration with username, email, and password
User login with username and password
Google OAuth integration
JWT-based authentication
Persistent session management
💸 Expense Tracking
Create and manage expense categories
Add transactions with amounts and categories
View transactions by category
Filter transactions by date range
Real-time expense statistics
Daily average calculations
🎨 Modern UI/UX
Dark theme with violet accents
Responsive design for all screen sizes
Interactive data visualizations
Smooth animations and transitions
Loading states and skeletons
Clean and intuitive interface
🛠️ Tech Stack
🌐 Frontend
React.js with hooks
Material UI components
React Router for navigation
Axios for API requests
Modern ES6 JavaScript
Responsive CSS with MUI styling
⚙️ Backend
Node.js and Express
PostgreSQL database
Sequelize ORM
JWT authentication
Google OAuth2
RESTful API design
🐳 DevOps
Docker containerization
Docker Compose for services
Environment configuration
Persistent data storage
📋 Prerequisites
Docker and Docker Compose
Node.js for local development
Google OAuth credentials
PostgreSQL (local or containerized)
⚙️ Setup
Clone the repository
Configure environment variables

backend/.env

GOOGLE_CLIENT_ID=your-google-client-id  
GOOGLE_CLIENT_SECRET=your-google-client-secret  
JWT_SECRET=your-jwt-secret  
DATABASE_URL=postgresql://postgres:postgres@db:5432/budget_buddy  
▶️ Running the Application
Build and start the containers
docker-compose up --build
Access the application
🌐 Frontend: http://localhost:3000
⚙️ Backend API: http://localhost:5000
🗄️ Database: localhost:5432
🔗 API Endpoints
🔐 Authentication
POST /api/auth/register
POST /api/auth/login
GET /api/auth/google
GET /api/auth/google/callback
GET /api/protected
💸 Transactions
GET /api/sections/:section/transactions
POST /api/transactions
GET /api/transactions
GET /api/transactions/stats
📂 Categories
GET /api/sections
POST /api/sections
PUT /api/sections/:id
DELETE /api/sections/:id
🔒 Security Features
Secure password hashing with bcrypt
JWT-based authentication
Protected API routes
CORS configuration
Environment variable protection
SQL injection prevention
XSS protection
Rate limiting
💻 Development
🌐 Frontend
cd frontend  
npm install  
npm start  
⚙️ Backend
cd backend  
npm install  
npm run dev  
🗄️ Database
PostgreSQL with Sequelize ORM
Automatic migrations
Data persistence


ate a Pull Request
