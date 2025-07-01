# PollHub - Social Polling Platform

![PollHub Logo](https://github.com/akash-kumar-saw/PollHub/blob/master/frontend/src/assets/images/pollhub.png) 

PollHub is a social media platform for creating and participating in polls. Share your opinions and see what others think!

## Features

### User Authentication
- Secure signup and login using email
- JWT-based authentication

### Poll Management
- Create custom polls with multiple options
- Vote on existing polls
- Bookmark favorite polls for quick access
- View real-time poll results

## Tech Stack

**Frontend:**
- React.js
- Vite.js
- TailwindCSS

**Backend:**
- Node.js
- Express.js
- MongoDB
- JWT (JSON Web Token) 

## Getting Started

### Prerequisites
- Node.js
- MongoDB Atlas account or local MongoDB instance
- npm or yarn

### Installation

#### Clone the Repository
   ```bash
   git clone https://github.com/akash-kumar-saw/pollhub.git
   ```

#### Backend Setup
1. Navigate to backend directory:
   ```bash
   cd backend
   ```

2. Create .env file:
   ```bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=8000
   ```

   Generate JWT_SECRET by running in terminal:
   ```bash
   node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"
   ```
   
3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm run dev
   ```

#### Frontend Setup
1. Navigate to frontend directory:
   ```bash
   cd frontend
   ```

2. Create .env file:
   ```bash
   VITE_API_BASE_URL=http://localhost:8000
   ```

3. Install dependencies:
   ```bash
   npm install
   ```



4. Start the development server:
   ```bash
   npm run dev
   ```

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (git checkout -b username/feature)
3. Commit your changes (git commit -m 'Added some Feature')
4. Push to the branch (git push origin username/feature)
5. Open a Pull Request
