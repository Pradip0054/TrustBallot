 # TrustBallot - Decentralized Blockchain Based Voting System 
## About The Project

TrustBallot is a decentralized blockchain-based voting platform designed to ensure secure, anonymous, and tamper-proof elections. It leverages blockchain technology to create a transparent and trustworthy digital voting environment.
In traditional voting systems, concerns such as vote tampering, lack of transparency, and centralized control reduce public trust. TrustBallot addresses these challenges by using cryptographic hashing and a custom blockchain to guarantee immutable and verifiable election records.

### Why this project?
- Security: Protects votes using SHA-256 hashing and blockchain immutability.  
- Privacy: Ensures anonymous voting by separating voter identity from vote data.  
- Transparency: Provides real-time vote verification and a publicly verifiable ledger.  
- Fairness: Enforces a strict one-person-one-vote system.  
- Social Impact: Promotes digital democracy and builds trust in modern election systems using secure technology.
# Core Features
- Secure User Authentication  
- One-Person-One-Vote System  
- Anonymous Voting  
- Blockchain-Based Vote Storage  
- Tamper-Proof Election Records  
- Real-Time Vote Verification  
- Transparent & Decentralized Ledger  
- Admin Dashboard for Election Management  
- QR Code Vote Verification 
## Tech Stack
This project is built using the following technologies:
### Frontend
- React.js
- CSS3 
- Axios
### Backend
- FastAPI 
- Uvicorn
- Pydantic 
### Blockchain
- Custom Python Blockchain 
- SHA-256 Cryptographic Hashing
- Proof-of-Integrity Mechanism
### Database
- SQLite (For voter & admin management)
## Project Structure

```
TrustBallot/
│
├── backend/
│   ├── main.py              # FastAPI main application
│   ├── blockchain.py        # Custom blockchain logic
│   ├── models.py            # SQLite database models
│   ├── database.py          # Database connection setup
│   ├── requirements.txt     # Backend dependencies
│   └── venv/                # (Ignored - Not pushed to GitHub)
│
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   └── manifest.json
│   │
│   ├── src/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── components/
│   │
│   ├── package.json
│   ├── package-lock.json
│   └── node_modules/        # (Ignored - Not pushed to GitHub)
│
├── .gitignore
└── README.md
```
# Getting Started (Installation Guide)
Follow these steps to set up **TrustBallot** locally on your machine.
---
# Prerequisites
Make sure you have installed:
- Python 3.10+
- Node.js (v18+ recommended)
- Git
- Docker
- VS Code (Recommended)
---
# Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/TrustBallot.git
cd TrustBallot
```
---
# Backend Setup (FastAPI)
## Navigate to Backend Folder
```bash
cd backend
```
---
## Create Virtual Environment
```bash
python -m venv venv
```
### Activate Virtual Environment
### Windows
```bash
venv\Scripts\activate
```
### Mac/Linux
```bash
source venv/bin/activate
```
---
## Install Dependencies
```bash
pip install -r requirements.txt
```
Example `requirements.txt`:
```
fastapi
uvicorn
pydantic
sqlalchemy
python-dotenv
```
---
## Run Backend Server
```bash
uvicorn main:app --reload
```
### Backend Runs On:
```
http://127.0.0.1:8000
```
### API Documentation:
```
http://127.0.0.1:8000/docs
```
---
# Frontend Setup (React)
Open a new terminal.
## Navigate to Frontend Folder
```bash
cd frontend
```
---
##  Install Node Modules
```bash
npm install
```
---
## Start React Application
```bash
npm start
```
### Frontend Runs On:
```
http://localhost:3000
```
---
### Run with Docker
From root directory:
```bash
docker-compose up --build
```
Stop containers:
```bash
docker-compose down
```
---

