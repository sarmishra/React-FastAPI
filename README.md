# FastAPI + React Project

## Backend - FastAPI:
- POST and GET requests
- Post, add a  new item to the list, and return that item
- Get, return all the items from the list

### Setup:
- `mkdir backend`
- `cd backend`
- Create a virtual environment: `python3 -m venv venv`
- Activate the virtual environment:
  - Mac/Linux: `source ./venv/bin/activate`
  - Windows: `.\venv\Scripts\activate`
- Install the dependencies from [requirements.txt](./backend/requirements.txt)
  - `pip install -r requirements.txt`

### Run the API
- python main.py

## Frontend - React:
- UI is connected to the API request
- Shows all the existing items (get request), plus can add a new one to the list through a post request

### Dependencies 
- NodeJS

### Setup 
- `npm create vite@latest frontend --template react`
- `cd frontend`
- `npm install`
- `npm install axios`

### Components
- Make the following dir structure
  - src/
    - components/
      - Fruits.jsx
      - AddFruitForm.jsx
    - App.jsx
    - main.jsx
    - api.js

### Run the App
- `npm run dev`

