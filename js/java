<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login</title>
<style>
  body {
    font-family: Arial, sans-serif;
  }
  form {
    max-width: 300px;
    margin: 50px auto;
  }
  input[type="text"], input[type="password"] {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }
  input[type="submit"] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 10px;
    margin: 10px 0;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  input[type="submit"]:hover {
    background-color: #45a049;
  }
</style>
</head>
<body>

<form id="loginForm" onsubmit="login(event)">
  <h2>Login</h2>
  <input type="text" id="username" placeholder="Username" required><br>
  <input type="password" id="password" placeholder="Password" required><br>
  <input type="submit" value="Login">
</form>

<script>
  function login(event) {
    event.preventDefault(); // Prevent form submission
    var username = document.getElementById('username').value;
    var password = document.getElementById('password').value;

    // Check if username and password match
    if (username === 'user' && password 
