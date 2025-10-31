# Social Media App (MiniSocial)
## Features
- User signup/login (JWT)
- Create posts with optional image upload (stored locally in backend/uploads)
- Like/unlike posts
- Comment on posts
- Simple React frontend and Express backend

## Quick setup
1. Backend
   - cd backend
   - copy .env.example to .env and set MONGODB_URI and JWT_SECRET
   - npm install
   - npm start

2. Frontend
   - cd frontend
   - npm install
   - npm start

Notes: For AWS deployment, use Elastic Beanstalk. When deploying, ensure `uploads/` is persisted (use an attached EFS or switch to S3 for production).
