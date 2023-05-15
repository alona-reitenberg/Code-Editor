# Code Editor App
### Home Page
<img width="550" alt="1" src="https://github.com/alona-reitenberg/Code-Editor/assets/112491981/ac56a642-6161-4d99-8e59-f40090c7a866">

### Editor Page
<img width="550" alt="2" src="https://github.com/alona-reitenberg/Code-Editor/assets/112491981/540a9b86-0162-4d9e-b626-690fff21728d">

## Technologies

Frontend- React JS.
Backend- Node JS, Web sockets.

## Description
Real time code editor application. <br>
Using this app you can create a new room and connect several users to the same room so they can see online the code you writing.

In order to use this application you need Create a new room & pick your name, and send the room ID to other people using the button "copy room id".
## How to run this project?

1. Open the project in Visual stodio (or another enviorment).

2. In order to run the FrontEnd:<br>
  2.1 Navigate to the frontend folder using "cd frontend" command.<br>
  2.2 Run "npm i" and wait until it finish<br>
  2.3 Add file that called ".env" ender frontend folder with the following content:<br>
    ##### REACT_APP_BACKEND_URL=http://localhost:5000
    <img width="584" alt="1" src="https://github.com/alona-reitenberg/Code-Editor/assets/112491981/e388104f-0bc4-406e-985f-8e07d320f6fe">

   2.4 Run "npm start" - It will open the URL [http://localhost:3000](http://localhost:3000) in your browser.
  
3. In order to run the BackendEnd:<br>
  3.1 Start a new terminal window.<br>
  3.2 Navigate to the backend folder using "cd backend" command.<br>
  3.3 run "npm i" and wait until it finish.<br>
  3.4 run "npm start"
