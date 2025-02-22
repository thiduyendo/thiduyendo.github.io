---
layout: page
title: Home
permalink: /
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thi Duyen Do - CV</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Navbar container */
        .dropdown {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        /* Button with hamburger icon */
        .dropbtn {
            background: none;
            border: none;
            font-size: 24px;
            cursor: pointer;
            color: black; /* Adjust color as needed */
        }

        /* Dropdown content (hidden by default) */
        .dropdown-content {
            display: none;
            position: absolute;
            right: 0;
            background-color: white;
            min-width: 160px;
            box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
            z-index: 1;
            border-radius: 5px;
            overflow: hidden;
        }

        /* Links inside the dropdown */
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
        }

        /* Change color of dropdown links on hover */
        .dropdown-content a:hover {
            background-color: #f1f1f1;
        }

        /* Show the dropdown menu on hover */
        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* Container for centered content */
        .content {
            max-width: 800px;
            margin: 50px auto;
            text-align: center;
        }
        /* Profile image */
        img {
            width: 150px;
            margin-top: 20px;
            border-radius: 50%;
        }
    </style>
</head>
<body>

<!-- Dropdown Menu -->
<div class="dropdown">
    <button class="dropbtn">&#9776;</button>
    <div class="dropdown-content">
        <a href="/about/">About me</a>
        <a href="#publications">Publication</a>
        <a href="/cv/">CV</a>
    </div>  
</div>

<!-- Home Page Content (Image and Description) -->
<p align="center">
  <h1>Thi Duyen Do</h1>
  <img src="images/logo.jpg" width="150">
</p>

<p align="center">
  <h2 style="font-family: 'Roboto', sans-serif;">Welcome to my page</h2>
  <h3 style="font-family: 'Roboto', sans-serif;">This is the website of Thi Duyen Do, Ph.D. in Biomedical Informatics - Taipei Medical University</h3>
</p>





