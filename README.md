Codalyx: Your AI-Powered Developer Growth Companion

Codalyx is designed for developers who are tired of switching between multiple platforms just to understand their progress.

Today, most developers use platforms like GitHub, LeetCode, Codeforces, CodeChef, and AtCoder. However, tracking performance across all of them is fragmented and inefficient. Codalyx solves this by bringing everything together into a single, unified dashboard.

In addition, it includes an AI-powered Performance Coach (built using Google Gemini) that not only tracks your progress but also helps you identify weaknesses and improve in a structured way.

Codalyx is not just a dashboard. It is a system that helps you grow as a developer.

---

## Key Features

### Unified Developer Dashboard

Codalyx provides a centralized view of your entire coding journey.

- Track GitHub repositories, language usage, and development activity  
- Analyze performance across platforms like LeetCode, Codeforces, and CodeChef  
- Understand your consistency and problem-solving behavior through structured analytics  

---

### Contest Tracking and Reminders

For competitive programmers, staying consistent is critical.

- View upcoming contests from multiple platforms in one place  
- Receive automated reminders before contests  
- Analyze your post-contest performance, including ranking trends  

---

### AI Performance Coach

The AI layer makes Codalyx more than just a tracking tool.

- Generates personalized roadmaps based on your weak areas  
- Provides clear explanations of important concepts such as DSA, OS, DBMS, and SQL  
- Maintains a revision system to help you retain previously learned topics  

---

### Chrome Extension Integration

Codalyx integrates directly into your workflow.

- Sync data seamlessly from coding platforms  
- Eliminate the need for manual updates  

---

## Tech Stack

- Frontend: React 19, Vite, Tailwind CSS, Framer Motion  
- Backend: Node.js, Express, MongoDB (Mongoose)  
- Authentication: JWT with Passport.js  
- AI Engine: Google Gemini Pro (v1.5)  
- Performance Optimization: Smart scraping and caching for low-latency updates  

---

## Installation and Setup

### Prerequisites

- Node.js (v18 or higher)  
- MongoDB Atlas account  
- Google Gemini API Key  

---

### Environment Configuration

Create a `.env` file in the `server/` directory:

PORT=4000
MONGODB_URI=your_atlas_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_key
CLIENT_URL=http://localhost:5173

Create a `.env` file in the `client/` directory:

VITE_API_URL=http://localhost:4000/api

---

### Run Locally

# Install dependencies
cd server && npm install
cd ../client && npm install

# Start backend
cd server
npm run dev

# Start frontend
cd client
npm run dev

---

## Contribution

Contributions are welcome. You can open an issue or submit a pull request for improvements, features, or bug fixes.

---

## License

This project is licensed under the MIT License.


