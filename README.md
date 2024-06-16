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
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>

        
        <div id="bookingSection" class="hidden">
            <h2>Booking Functionality</h2>
            <p>Welcome, <span id="userDisplayName"></span>!</p>
            <button id="bookNow">Book Now</button>
        </div>
    </div>                            
    <script src="script.js"></script>
</body>
</html>

