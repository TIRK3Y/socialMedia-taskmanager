Setup:
mkdir server
cd server
npm init -y

cd..
npx create-react-app client
cd client

Install Packages (Frontend/client)
multer (store files)
- npm install multer

material UI ( styling and react packages) (Frontend/client)
- npm install @mui/material @emotion/react @emotionstyled axios react-router-dom


File Structure:
Client>
|-src>
|-src>api>auth.js
|-src>api>task.js
|-src>pages>component>Navigation.jsx
|-src>pages>Dashboard.js
|-src>pages>Feed.js
|-src>pages>Login.js
|-src>pages>Signup.js
|-src>pages>TaskManager.js
|-src>pages>TaskManager.css
|-src>theme.js

Server>
|-middlware>auth.js
|-models>Post.js
|-models>Task.js
|-models>User.js
|-routes>auth.js
|-routes>post.js
|-routes>task.js
|-routes>user.js
.env
server.js
