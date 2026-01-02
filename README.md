# Weather App (Flask + React)

A simple full-stack weather web app with user authentication and favorites. Users can register/login, search weather by city, view a forecast, and save favorite cities for quick access.

## Features
- User registration + login (JWT-based auth)
- Current weather lookup by city
- Forecast lookup by city
- Save and view favorite cities (requires login)
- Responsive UI built with React + Bootstrap

## Tech Stack
**Frontend**
- React (Create React App)
- React Router
- Axios
- Bootstrap

**Backend**
- Python + Flask
- Flask-JWT-Extended (JWT auth)
- Flask-CORS
- Requests (OpenWeather API calls)
- (Optional) Flask-Migrate / database support depending on backend config

## Project Structure
Weather-App/
Backend/
pythonProject/
main.py
app/
...
FrontEnd/
weather-frontend/
src/
package.json

## Requirements
- Node.js 18+ (recommended)
- Python 3.11+ (3.12 recommended)
- An OpenWeather API key
