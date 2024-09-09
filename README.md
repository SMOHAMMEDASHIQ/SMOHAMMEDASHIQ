<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
        }

        /* Centering Content */
        .center {
            text-align: center;
            margin-top: 50px;
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            0% { opacity: 0; transform: translateX(-100px); }
            100% { opacity: 1; transform: translateX(0); }
        }

        /* Styling and Animation for "Hi there" */
        h1 {
            font-size: 48px;
            color: #0078D4;
            margin-bottom: 20px;
            animation: fadeIn 1s ease-in-out;
            position: relative;
        }

        h1::after {
            content: '👋';
            position: absolute;
            right: -60px;
            animation: wave 2s infinite;
            transform-origin: 70% 70%;
        }

        @keyframes wave {
            0%, 100% { transform: rotate(0deg); }
            25% { transform: rotate(15deg); }
            50% { transform: rotate(-10deg); }
            75% { transform: rotate(15deg); }
        }

        p {
            font-size: 20px;
            color: #555;
            margin-bottom: 30px;
            animation: slideIn 1.5s ease-in-out;
        }

        /* Styling for Tech Stack Section */
        .tech-stack {
            margin-top: 40px;
            animation: fadeIn 2s ease-in-out;
        }

        .tech-stack h2 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #0078D4;
        }

        .tech-stack ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
        }

        .tech-stack ul li {
            font-size: 18px;
            background: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .tech-stack ul li:hover {
            transform: scale(1.1);
        }

        /* Additional Sections */
        .projects, .contact {
            margin-top: 50px;
            animation: fadeIn 2s ease-in-out;
        }

        .projects h2, .contact h2 {
            font-size: 28px;
            margin-bottom: 20px;
            color: #0078D4;
        }

        .contact ul {
            list-style: none;
            padding: 0;
            font-size: 18px;
        }

        .contact ul li {
            margin-bottom: 10px;
        }

        .contact ul li a {
            text-decoration: none;
            color: #0078D4;
            transition: color 0.3s ease;
        }

        .contact ul li a:hover {
            color: #005bb5;
        }
    </style>
</head>
<body>
    <div class="center">
        <h1>Hi there!</h1>
        <p>I am <strong>S MOHAMMED ASHIQ</strong>, currently pursuing my BE from RV College of Engineering. I am a passionate developer and analyst with a strong interest in various technologies, including web and app development, machine learning, and data analytics.</p>
    </div>

    <div class="tech-stack">
        <h2>Tech Stacks</h2>
        <ul>
            <!-- Programming Languages -->
            <li>![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)</li>
            <li>![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)</li>
            <li>![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)</li>
            <!-- Frontend Development -->
            <li>![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)</li>
            <li>![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)</li>
            <li>![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)</li>
            <li>![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)</li>
            <!-- Backend Development -->
            <li>![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node-dot-js&logoColor=white)</li>
            <li>![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)</li>
            <li>![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)</li>
            <li>![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)</li>
            <li>![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)</li>
            <!-- Frameworks and Libraries -->
            <li>![Java SWINGS](https://img.shields.io/badge/Java_Swings-007396?style=flat-square&logo=java&logoColor=white)</li>
            <li>![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)</li>
            <li>![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)</li>
            <li>![Sklearn](https://img.shields.io/badge/Sklearn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)</li>
            <!-- Tools and Platforms -->
            <li>![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)</li>
            <li>![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)</li>
            <li>![SSMS](https://img.shields.io/badge/SQL_Server_Management_Studio-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)</li>
            <li>![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)</li>
            <li>![VS Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=flat-square&logo=visual-studio-code&logoColor=white)</li>
            <li>![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellij-idea&logoColor=white)</li>
            <li>![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white)</li>
            <li>![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)</li>
            <!-- Salesforce -->
            <li>![Sales Cloud](https://img.shields.io/badge/Sales_Cloud-00A1E0?style=flat-square&logo=salesforce&logoColor=white)</li>
            <li>![Service Cloud](https://img.shields.io/badge/Service_Cloud-00A1E0?style=flat-square&logo=salesforce&logoColor=white)</li>
            <li>![Experience Cloud](https://img.shields.io/badge/Experience_Cloud-00A1E0?style=flat-square&logo=salesforce&logoColor=white)</li>
            <li>![Education Cloud](https://img.shields.io/badge/Education_Cloud-00A1E0?style=flat-square&logo=salesforce&logoColor=white)</li>
            <li>![Healthcare Cloud](https://img.shields.io/badge/Healthcare_Cloud-00A1E0?style=flat-square&logo=salesforce&logoColor=white)</li>
        </ul>
    </div>

    <div class="projects">
        <h2>🔭 I’m currently working on...</h2>
        <p>Developing machine learning models for data analysis</p>
    </div>

    <div class="contact">
        <h2>📫 How to reach me:</h2>
        <ul>
            <li>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile">Your LinkedIn Profile</a></li>
        </ul>
    </div>
</body>
</html>
