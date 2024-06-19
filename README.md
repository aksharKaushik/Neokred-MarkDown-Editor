# Neokred-MarkDown-Editor
Real-time Markdown Editor with Live Preview

This repository consists of two folders namely frontend and backend.
Open a terminal and cd frontend folder and write command "npm i" then "npm start" to run frontend. 
Open another terminal and cd backend folder and "npm i" then "node index.js" to run backend.

As, markdown to html can be done in frontend only but in order to include backend into picture, I have used socket.io to get the markdown input from frontend to backend and to return the same input from backend to frontend in the realtime. Also I have used debouncing in the frontend to avoid multiple socket calls.