# Full-Stack Weather Dashboard

A comprehensive weather monitoring application that provides real-time data and 5-day forecasts. This project demonstrates a decoupled architecture using a Python Flask REST API and a React frontend, secured with JSON Web Tokens (JWT).

## Engineering Highlights

* **Secure Authentication:** Implemented JWT-based user sessions, allowing for secure registration, login, and protected "Favorite Cities" data.
* **Asynchronous API Handling:** Integrated the OpenWeatherMap API using Axios (Frontend) and Requests (Backend) to provide live data updates without page refreshes.
* **Persistent User Data:** Designed a "Favorites" system that allows authenticated users to save frequently searched locations for instant access.
* **Responsive Design:** Leveraged React and Bootstrap to ensure the dashboard provides a seamless experience across desktop and mobile devices.

## Tech Stack

**Frontend**
* React (React Router, Axios)
* Bootstrap (UI Components)

**Backend**
* Python + Flask
* Flask-JWT-Extended (Security)
* Flask-CORS (Cross-Origin Resource Sharing)
* OpenWeather API Integration



---

## Setup and Installation

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd Backend/pythonProject
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Flask server:
   ```bash
   python main.py

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd FrontEnd/weather-frontend
2. Install dependencies:
   ```bash
   npm install
3. Start the React application:
   ```bash
   npm start

**Requirements**

Node.js 18+

Python 3.11+

OpenWeatherMap API Key (placed in backend configuration)
