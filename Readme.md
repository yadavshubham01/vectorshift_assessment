# VectorShift Integrations Technical Assessment

## Assignment Overview
This repository contains the solution to the VectorShift Integrations Technical Assessment. The project consists of a frontend built using React and a backend implemented with FastAPI. The goal of this project is to create a flexible and reusable node abstraction, enhance the styling, improve the text node logic, and integrate the frontend with the backend for Integrations.

## Project Structure
- Frontend: Located in the `/frontend` folder.
- Backend: Located in the `/backend` folder.

## How to Run

### Frontend:
1. Navigate to the `/frontend` folder.
2. Run the following commands:
   ```sh
   npm install
   npm start
   ``` 
3. The frontend will start on http://localhost:3000.

### Backend:
1. Navigate to the /backend folder.
2. Run the following command:
 ```sh
    uvicorn main:app --reload
 ```
3. The backend will start on http://localhost:8000.

### Redis:
* Start a Redis instance using the following command:
```
  redis-server
```

## Technologies Used
### Frontend:
* JavaScript
* React
### Backend:
* Python
* FastAPI
* Redis