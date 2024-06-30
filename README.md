<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Management</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>User Management System</h1>
        
            <form id="registration Form">
            <h2>Register User</h2>
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Register</button>
        </form>

        
        <div id="userList">
            <h1>Login</h1>
        
        
        <form id="loginForm">
            <label for="email">Email:</label>
            <input type="text" id="email" name="email" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>

            <style>
        body 
        {
            font-family: Arial, sans-serif;
            margin: 50px;
        }
        form 
        {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
        }
        label, input, select, button 
        {
            display: block;
            width: 100%;
            margin-bottom: 10px;
        }
        button 
        {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover 
        {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h2>Book Now</h2>
    <form action="/book" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="service">Select Service:</label>
        <select id="service" name="service" required>
            <option value="">Choose a service</option>
            <option value="service1">Service 1</option>
            <option value="service2">Service 2</option>
            <option value="service3">Service 3</option>
        </select>
        
        <label for="date">Preferred Date:</label>
        <input type="date" id="date" name="date" required>
        
        <label for="time">Preferred Time:</label>
        <input type="time" id="time" name="time" required>
        
        <label for="comments">Additional Comments:</label>
        <textarea id="comments" name="comments" rows="4"></textarea>
        
        <button type="submit">Book Now</button>
</body>
</html>
