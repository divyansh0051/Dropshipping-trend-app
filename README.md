Dropshipping Product Trend Web App

A full stack e-commerce intelligence tool that identifies high-demand trending products using machine learning, with a React frontend and Node.js + Express backend.

 
🛠️ Tech Stack
- **Frontend:** React, Bootstrap, HTML5, CSS3
- **Backend:** Node.js, Express.js, REST API
- **Database:** MongoDB
- **ML Model:** Python, Scikit-learn
- **Deployment:** Vercel

✨ Features
- Identifies trending products from 10,000+ historical sales records
- 6 REST API endpoints for product search, trend scoring, and category filtering
- ML model achieving 88% accuracy on product demand prediction
- Mobile-first responsive design across all screen sizes
- Decoupled ML service for clean web layer architecture

📁 Project Structure

├── client/          # React + Bootstrap frontend
│   └── src/
│       ├── components/
│       └── pages/
├── server/          # Node.js + Express backend
│   ├── routes/
│   ├── models/
│   └── controllers/
└── ml_model/        # Python trend prediction engine

⚙️ Getting Started

bash
Clone the repo
git clone https://github.com/divyansh0051/Dropshipping-trend-app

Install backend dependencies
cd server
npm install

Install frontend dependencies
cd ../client
npm install

Run backend
cd ../server
npm start

Run frontend
cd ../client
npm start

👨‍💻 Author
Divyansh Goyal** — [github.com/divyansh0051]
