---
permalink: /
title: "👋🏼 Hello there, I'm Rezuan!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <title>Portfolio</title> -->
    <style>
        /* General Section Styles */
        body {
            font-family: Arial, sans-serif; /* Add a default font */
            background-color: #f0f0f0; /* Light background color */
            color: #333; /* Text color */
            margin: 0;
            padding: 0;
        }

        section {
            margin: 20px auto; /* Center the sections */
            padding: 20px;
            border-radius: 10px;
            max-width: 800px; /* Limit the max width */
        }

        /* Shadow for the About Section */
        .shadow-1 {
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background-color: #f8f9fa;
        }

        /* Shadow for the Research Experience Section */
        .shadow-2 {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            background-color: #ffffff;
        }

        /* Shadow for the Projects Section */
        .shadow-3 {
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.3);
            background-color: #f1f1f1;
        }
        
        /* Image Container Styling */
        img {
            height: auto;
            max-height: 200px;
            width: 30%; /* Set the image width to 30% */
            border-radius: 10px;
            margin: 10px;
        }

        /* Center images within their container */
        .image-container {
            display: flex;
            justify-content: center; /* Center images */
            flex-wrap: wrap; /* Wrap images to new line if needed */
        }
    </style>
</head>
<body>

    <!-- About Section with Shadow -->
    <section id="about" class="shadow-1">
        <h2>👨🏻‍💻 About Me</h2>
        <p>I recently graduated from North South University with a Bachelor's in Computer Science & Engineering.</p>
        <p>My research areas encompass the application of Machine learning (ML) in medical image analysis and the advancement of ML through Quantum computing.</p>
        <p>I am excited to pursue a Master's in Computer Science, where I hope to collaborate with leading researchers and contribute to advancements in ML.</p>
    </section>

    <!-- Research Experience Section with Shadow -->
    <section id="research-experience" class="shadow-2">
        <h2>👨🏻‍🔬 Research Experience</h2>
        <p>I worked as a <strong>Student Researcher</strong> at North South University under the supervision of Dr. Mohammad Abdul Qayum on <strong>Quantum Machine Learning</strong>, where I developed a hybrid classical-quantum machine learning model for breast cancer classification. Our work has been submitted to the 27th International Conference on Computer and Information Technology (ICCIT 2024).</p>
    </section>

    <!-- Projects Section with Shadow -->
    <section id="projects" class="shadow-3">
        <h2>💻 Projects</h2>

        <h3>Drug Repurposing for COVID-19 using Graph Neural Network</h3>

        <h3>Bad Root Canal Detection</h3>
        <p>We implemented an auto tooth segmentation system powered by <strong>YOLOv7</strong> and the <strong>Segment Anything Model</strong>. The object detection model was trained to detect bad root canals, which were later used as a prompt for the segmentation model to generate the segmentation mask.</p>

        <div class="image-container">
            <img src="images/project1.1.png" alt="First Image" />
            <img src="images/project1.2.png" alt="Second Image" />
            <img src="images/project1.3.png" alt="Third Image" />
        </div>
    </section>

</body>
</html>