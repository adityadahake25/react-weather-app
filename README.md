# Weather Forecasting App (React)

A weather forecasting web application built using React that fetches real-time weather data from external APIs and displays detailed weather parameters for user-entered locations with proper error handling.

---

## Project Overview
This project allows users to search for any city and view current weather conditions. It retrieves live weather data from a weather API, processes the response, and dynamically renders key weather information using a component-based React architecture.

---

## Features
- Location-based weather search
- Real-time weather data using APIs
- Displays essential weather parameters:
  - Temperature
  - Minimum Temperature
  - Maximum Temperature
  - Humidity
  - Weather condition and description
  - Feels-like temperature
- Graceful error handling for:
  - Invalid city names
  - API failures
  - Network issues

---

## 🛠️ Tech Stack
- **React** – Component-based UI development  
- **JavaScript (ES6)** – Application logic and API handling  
- **JSX** – UI structure  
- **CSS** – Styling and responsive layout  
- **Vite** – Fast development and build tool  
- **Weather API** – Real-time weather data source  

---

## Technical Implementation
- Weather data fetched using JavaScript `fetch` with async/await
- Application state used to manage dynamic weather updates
- Conditional rendering based on API response and error states
- Input validation to handle invalid or empty search queries
- Reusable React components for better code organization

---

## Getting Started
Follow the steps below to run the project locally.

### Prerequisites
- Node.js installed on your system

### Installation & Run
```bash
npm install
npm run dev
