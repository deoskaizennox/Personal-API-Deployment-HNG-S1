# Personal API Deployment

A minimal REST API built with Flask, deployed using ngrok for public access, completed as a task for HNG DevOps Stage 1.

## 📋 Project Overview

This project demonstrates a basic understanding of API development and deployment. It consists of three simple endpoints that return JSON responses.

## 🚀 How to Run Locally

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/deoskaizennox/Personal-API-Deployment-HNG-S1.git
cd Personal-API-Deployment-HNG-S1```

2. Install dependencies: 
```pip install flask```

3. Run the application:
```python3 app.py```

4. The API will be available at: *http://127.0.0.1:5000*

### 📡 API Endpoints

1. *Root Endpoint*
```bash
1 GET /
```
*Response:*
```json  
{
  "message": "API is running"
} 
```
2. *Health Check*
```json
{
  "message": "healthy"
}
```
3. User Information
```bash
1 GET /me
```
*Response:*
```json
{
  "name": "Your Name",
  "email": "Your Email",
  "github": "Your Github URL"
}
```
🌐 *Live Deployment*

The API is publicly accessible at:
URL: https://giveaway-luminance-tutor.ngrok-free.dev

*Test the live endpoints:*
```bash
curl https://giveaway-luminance-tutor.ngrok-free.dev/
curl https://giveaway-luminance-tutor.ngrok-free.dev/health
curl https://giveaway-luminance-tutor.ngrok-free.dev/me
```
🛠️  *Technologies Used*
1. _Python 3_ - Programming language
2. _Flask_ - Web framework
3. _ngrok_ - Tunneling tool for public access

