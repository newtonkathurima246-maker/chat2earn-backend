const express = require("express");
const app = express();

app.get("/", (req, res) => {
  res.send(`
    <!DOCTYPE html>
    <html>
    <head>
      <title>Chat2Earn</title>
      <style>
        body{
          font-family: Arial, sans-serif;
          text-align:center;
          background:#0f172a;
          color:white;
          padding:50px;
        }
        h1{
          color:#22c55e;
        }
        .btn{
          display:inline-block;
          margin:10px;
          padding:12px 24px;
          background:#22c55e;
          color:white;
          text-decoration:none;
          border-radius:8px;
        }
      </style>
    </head>
    <body>
      <h1>💬 Chat2Earn</h1>
      <p>Chat, Refer Friends, and Earn Rewards.</p>
      <a href="/login" class="btn">Login</a>
      <a href="/register" class="btn">Register</a>
    </body>
    </html>
  `);
});

app.get("/login", (req, res) => {
  res.send("<h1>Login Page - Coming Soon</h1>");
});

app.get("/register", (req, res) => {
  res.send("<h1>Register Page - Coming Soon</h1>");
});

const PORT = process.env.PORT || 3000;

app.listen(PORT, () => {
  console.log(`Server running on port ${PORT}`);
});
