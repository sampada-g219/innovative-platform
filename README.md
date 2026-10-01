# SMART FORESIGHT — Artificial Intelligence for GNSS Error Prediction and Correction

Full-stack educational project with a Node.js backend and browser frontend. It uses a local JSON file as the database, so PostgreSQL is not required.

## Run
1. Install Node.js 18+.
2. Extract and open this folder in VS Code.
3. Terminal -> New Terminal.
4. Run `node server.js`.
5. Open `http://localhost:3000`.

Windows: double-click `start.bat`.

## Demo accounts
Admin: admin@smartforesight.com / Admin@123
User: user@smartforesight.com / User@123

## Backend APIs
POST /api/login
POST /api/register
POST /api/predict
GET /api/predictions
GET /api/stats
GET /api/health

## AI note
The included predictor is an explainable deterministic AI-style estimator for demonstration. It combines GNSS geometry, signal quality, satellite count, multipath and atmospheric indicators. A research-grade version can replace this function with a trained ML model using real GNSS datasets.
