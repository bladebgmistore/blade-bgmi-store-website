<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLADE BGMI STORE</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f0f2f5;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
            color: #e74c3c; /* Red color for BLADE */
        }
        header h1 span {
            color: white; /* White color for BGMI STORE */
        }
        .social-links {
            margin-top: 5px;
            font-size: 0.9em;
        }
        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 8px;
        }
        .social-links i {
            margin-right: 5px;
        }
        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        nav button {
            background-color: #e74c3c;
            color: white;
            border: none;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            transition: background-color 0.3s ease;
        }
        nav button:hover {
            background-color: #c0392b;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 20px auto;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .section-title {
            text-align: center;
            color: #e74c3c;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .account-grid, .uc-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .item-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
            padding-bottom: 15px;
            transition: transform 0.2s;
        }
        .item-card:hover {
            transform: translateY(-5px);
        }
        .item-card img {
            max-width: 100%;
            height: 200px; /* Fixed height for images */
            object-fit: cover; /* Ensures images cover the area without distortion */
            border-bottom: 1px solid #eee;
            margin-bottom: 10px;
        }
        .item-card h3 {
            margin: 10px 0;
            color: #34495e;
        }
        .item-card p {
            font-size: 1.2em;
            color: #28a745; /* Price color */
            margin-bottom: 15px;
            font-weight: bold;
        }
        .item-card button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 25px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }
        .item-card button:hover {
            background-color: #218838;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            margin-top: 30px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>BLADE <span>BGMI STORE</span></h1>
        <div class="social-links">
            <a href="https://www.youtube.com/channel/UCf5w9oE5z3J4J8Q3p9Y4c6A" target="_blank"><i class="fab fa-youtube"></i>YouTube</a>
            <a href="https://www.instagram.com/bladebgmistore" target="_blank"><i class="fab fa-instagram"></i>Instagram: @bladebgmistore</a>
            <a href="
