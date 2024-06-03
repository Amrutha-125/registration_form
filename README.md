User Registration App
This is a simple user registration web application built with Node.js, Express, and MongoDB. Users can register by providing their name, email, and password.

Features
User Registration: Users can register by providing their name, email, and password.
Password Encryption: Passwords are encrypted using bcrypt before storing them in the database.
Static File Serving: Static files (HTML, CSS, etc.) are served using Express's built-in static middleware.
Dependencies
Express: Fast, unopinionated, minimalist web framework for Node.js.
Mongoose: Elegant MongoDB object modeling for Node.js.
bcrypt: A library to help you hash passwords.
Configuration
MongoDB URI: Modify the MongoDB connection URI in server.js if your MongoDB server is running on a different host or port.
