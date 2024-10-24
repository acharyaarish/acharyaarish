<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arish Acharya - Full Stack Developer</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1, h2, h3 {
            font-weight: bold;
            text-align: center;
            color: #2c3e50;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0.5em;
            animation: fadeIn 1s;
        }
        h2 {
            font-size: 2.5em;
            margin-top: 1.5em;
            color: #3498db;
        }
        h3 {
            font-size: 2em;
            margin-top: 1em;
        }
        .about {
            text-align: center;
            font-size: 1.2em;
            margin: 20px 0;
            animation: slideIn 1s;
        }
        .skills {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .skill-badge {
            margin: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
            border-radius: 5px;
            padding: 10px;
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .skill-badge:hover {
            transform: scale(1.1);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }
        .projects {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 20px 0;
        }
        .project {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            margin: 20px;
            padding: 20px;
            text-align: center;
            width: 80%;
            transition: transform 0.3s;
        }
        .project:hover {
            transform: scale(1.05);
        }
        .quote {
            text-align: center;
            font-style: italic;
            margin: 40px 0;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #888;
        }
    </style>
</head>
<body>

<h1>👋 Welcome to My World!</h1>
<div class="about">
    <p><strong>I'm Arish Acharya</strong>, a passionate Full Stack Developer always learning and improving my skills.</p>
    <p>Currently diving deep into UI frameworks and AWS cloud solutions. Let's build something great together!</p>
</div>

<h2>Core Skills</h2>
<div class="skills">
    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/Chakra_UI-319795?style=for-the-badge&logo=chakraui&logoColor=white" alt="Chakra UI Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/Material_UI-0081CB?style=for-the-badge&logo=mui&logoColor=white" alt="Material UI Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/AWS_Amplify-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Amplify Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white" alt="AWS S3 Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/AWS_Glue-00B2E2?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Glue Badge" class="skill-badge" />
    <img src="https://img.shields.io/badge/AWS_Redshift-9B4F96?style=for-the-badge&logo=amazonredshift&logoColor=white" alt="AWS Redshift Badge" class="skill-badge" />
</div>

<h2>Featured Projects</h2>
<div class="projects">
    <div class="project">
        <h3><a href="https://github.com/acharyaarish/wildlife_incidents_dashboard">Wildlife Incidents Dashboard</a></h3>
        <p>Analyzed wildlife incidents using AWS EC2—because every animal deserves a second chance at fame!</p>
        <strong>✨ Watch the demo:</strong> <a href="https://example.com">Demo Link</a>
    </div>
    <div class="project">
        <h3><a href="https://github.com/acharyaarish/dog_breed_detector">Dog Breed Detector Game</a></h3>
        <p>Web app for identifying dog breeds using React and Node.js. Your pup can finally get the recognition it deserves!</p>
        <strong>🐾 Try it out:</strong> <a href="https://example.com">Try It Now</a>
    </div>
    <div class="project">
        <h3><a href="https://github.com/acharyaarish/Excel_Dashboard">Sales Dashboard Analysis</a></h3>
        <p>Excel dashboard with Pivot Tables for visualizing sales data. Making decision-makers more decisive!</p>
        <strong>📊 View Analysis:</strong> <a href="https://example.com">View Here</a>
    </div>
    <div class="project">
        <h3><a href="https://paldip.com">EdTech Platform Enhancement</a></h3>
        <p>Improved usability and functionality for an educational tech platform—because learning should never be boring.</p>
        <strong>📚 Check it out:</strong> <a href="https://example.com">Explore Now</a>
    </div>
</div>

<div class="quote">
    <h2>Motivational Quote</h2>
    <p>"Why do programmers always mix up Christmas and Halloween? Because Oct 31 == Dec 25!"</p>
</div>

<footer>
    <p>Feel free to reach out!</p>
    <p><strong>Email:</strong> <a href="mailto:acharyaarish@gmail.com">acharyaarish@gmail.com</a></p>
    <p><strong>Portfolio:</strong> <a href="https://arish.app">arish.app</a></p>
    <p><strong>GitHub:</strong> <a href="https://github.com/acharyaarish">github.com/acharyaarish</a></p>
</footer>

</body>
</html>
