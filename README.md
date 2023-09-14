<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Digital Library</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            margin: 0 auto;
            width: 960px;
        }
        .navbar {
            background-color: #333;
            color: white;
            height: 40px;
            list-style: none;
            padding: 0;
            text-align: right;
        }
        .navbar li {
            display: inline-block;
            margin-right: 30px;
            padding: 10px 20px;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .navbar li:hover {
            background-color: #2c2c2c;
        }
        .navbar .logo {
            background-color: #2c2c2c;
            border-radius: 5px;
            display: inline-block;
            font-size: 24px;
            height: 20px;
            margin-right: 10px;
            text-align: center;
            width: 70px;
        }
        .navbar-form {
            display: inline-block;
            margin-top: 20px;
        }
        .navbar-form input[type="text"] {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
            padding: 8px 12px;
            width: 100%;
        }
        .navbar-form button[type="submit"] {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 10px 20px;
            text-transform: uppercase; 
