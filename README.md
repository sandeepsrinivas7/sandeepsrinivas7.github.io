<!DOCTYPE html>
<html>
  <head>
    <style>
      /* Set the background color */
      body {
        background-color: #3c3b3f;
      }

      /* Set the font and font color */
      h1, h2, h3, h4, h5, h6, p {
        font-family: 'Montserrat', sans-serif;
        color: #f5f5f5;
      }

      /* Add a gradient to the background */
      .gradient-bg {
        background-image: linear-gradient(to right, #667eea, #764ba2);
        padding: 50px 0;
      }

      /* Style the resume section */
      .resume {
        max-width: 800px;
        margin: 0 auto;
      }

      /* Style the contact info section */
      .contact-info {
        background-color: #343337;
        padding: 20px;
        border-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: space-around;
      }

      /* Style the contact info icons */
      .contact-info i {
        font-size: 2rem;
        color: #f5f5f5;
      }

      /* Style the experience section */
      .experience {
        margin: 50px 0;
      }

      /* Style the experience timeline */
      .experience .timeline {
        display: flex;
        align-items: center;
        position: relative;
      }

      /* Style the experience timeline dates */
      .experience .timeline .date {
        width: 100px;
        text-align: right;
        padding-right: 10px;
      }

      /* Style the experience timeline bars */
      .experience .timeline .bar {
        flex-grow: 1;
        height: 3px;
        background-color: #f5f5f5;
        position: relative;
      }

      /* Style the experience timeline event */
      .experience .timeline .event {
        width: 400px;
        background-color: #343337;
        padding: 20px;
        position: relative;
        margin-left: 10px;
        border-radius: 10px;
      }

      /* Style the experience timeline event content */
      .experience .timeline .event .content {
        color: #f5f5f5;
      }

      /* Style the experience timeline event company */
      .experience .timeline .event .company {
        font-weight: bold;
        margin-bottom: 5px;
      }
    </style>

    <!-- Add font imports -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

    <title>Resume</title>
  </head>
  <body>
    <!-- Add a gradient background -->
    <div class="gradient-bg">
      <!-- Add the resume section -->
      <div class
