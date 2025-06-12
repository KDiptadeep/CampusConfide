# How to run the project
## 1. Open both the frontend and backend directories in two separate terminals.
## 2. In the `final-project-frontend` directory, run the command: `npm start`
## 3. In the `final-project-backend` directory, start the server with: `node server.js`

### This project uses a local MongoDB instance. To configure it:
### - Create a `.env` file in the backend folder
### - Add the following lines:
###   `MONGO_URI=mongodb://127.0.0.1:27017/echohub-db`
###   `JWT_SECRET=your-custom-secret`

### Replace `your-custom-secret` with a secure string. It will be used for authenticating users via JWT.
