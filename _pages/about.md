---
permalink: /
title: "👋🏼 Hello there, I'm Rezuan!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <title>Portfolio</title> -->
    <style>
        /* General Section Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        section {
            margin: 20px auto;
            padding: 20px;
            border-radius: 10px;
            max-width: 800px;
            background-color: #ffffff; /* Keep background for readability */
            box-shadow: 0 -8px 8px -8px rgba(0, 0, 0, 0.2), 0 8px 8px -8px rgba(0, 0, 0, 0.2); /* Shadow only on top and bottom */
        }

        /* Image Styling */
        img {
            height: auto;
            max-height: 200px;
            width: 30%;
            border-radius: 10px;
            margin: 10px;
        }

        /* Center images within their container */
        .image-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
    </style>
</head>
<body>

    <!-- About Section with Vertical Shadow -->
    <section id="about">
        <h2>👨🏻‍💻 About Me</h2>
        <p>I recently graduated from North South University with a Bachelor's in Computer Science & Engineering.</p>
        <p>My research areas encompass the application of Machine learning (ML) in medical image analysis and the advancement of ML through Quantum computing.</p>
        <p>I am excited to pursue a Master's in Computer Science, where I hope to collaborate with leading researchers and contribute to advancements in ML.</p>
    </section>

    <!-- Research Experience Section with Vertical Shadow -->
    <section id="research-experience">
        <h2>👨🏻‍🔬 Research Experience</h2>
        <p>I worked as a <strong>Student Researcher</strong> at North South University under the supervision of Dr. Mohammad Abdul Qayum on <strong>Quantum Machine Learning</strong>, where I developed a hybrid classical-quantum machine learning model for breast cancer classification. Our work has been submitted to the 27th International Conference on Computer and Information Technology (ICCIT 2024).</p>
    </section>

    <!-- Projects Section with Vertical Shadow -->
    <section id="projects">
        <h2>💻 Projects</h2>

        <h3>Drug Repurposing for COVID-19 using Graph Neural Network</h3>

        <h3>Bad Root Canal Detection</h3>
        <p>We implemented an auto tooth segmentation system powered by <strong>YOLOv7</strong> and the <strong>Segment Anything Model</strong>. The object detection model was trained to detect bad root canals, which were later used as a prompt for the segmentation model to generate the segmentation mask.</p>

        <div class="image-container">
            <img src="images/project1.1.png" alt="First Image" />
            <!-- <img src="images/project1.2.png" alt="Second Image" />
            <img src="images/project1.3.png" alt="Third Image" /> -->
        </div>
    </section>

</body>
</html>
