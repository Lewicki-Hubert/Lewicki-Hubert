<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hubert Lewicki's Profile</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }
        canvas {
            max-width: 600px;
            margin: auto;
        }
    </style>
</head>
<body>
    <!-- Personal Information -->
    <h1 align="left" style="color: black;"><strong>👋 Hi, My name is Hubert Lewicki</strong></h1>
    <p align="left" style="color: black;"><strong>👨‍🎓I am a third year college student at PJATK University</strong></p>
    <p align="left" style="color: black;"><strong>👨‍💻 I’m interested in Computer science</strong></p>
    <p align="left" style="color: black;"><strong>📚 Continuously developing my skill in programming languages mostly Python</strong></p>
    <p align="left" style="color: black;"><strong>🥅 My goal: Combine programming with Data science and progressively develop my skill in it 📊</strong></p>
    <p align="left" style="color: black;"><strong>🎼 Fun fact: I am a Music lover, and in my free time, I create my own music in a program called FL Studio</strong></p>
    <p align="left" style="color: black;"><strong>🕺 Love any type of meetings or going outs</strong></p>
    <p align="left" style="color: black;"><strong>💼 Open for any type of Intership (preferably IT department)</strong></strong></p>
    <p align="left" style="color: black;"><strong>📫 You can reach me through mail "hlewicki02@gmail.com" or LinkedIn https://www.linkedin.com/in/hubert-lewicki-0abb73283/</strong></p>

    <!-- Profile Views -->
    <p align="left"> <img src="https://komarev.com/ghpvc/?username=lewicki-hubert&label=Profile%20views&color=0e75b6&style=flat" alt="lewicki-hubert" /> </p>

    <!-- Connect Section -->
    <h3 align="left" style="color: black;"><strong>Connect with me:</strong></h3>
    <p align="left">
        <a href="https://www.linkedin.com/in/hubert-lewicki-0abb73283/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="hubert lewicki" height="30" width="40" /></a>
        <a href="https://www.facebook.com/hubert.lewicki.33" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="hubert lewicki" height="30" width="40" /></a>
        <a href="https://www.instagram.com/teddy_berti/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="teddy_berti" height="30" width="40" /></a>
    </p>

    <!-- Languages and Tools Section -->
    <h3 align="left" style="color: black;"><strong>Languages and Tools:</strong></h3>
    <p align="left">
        <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>
        <a href="https://www.JavaScript.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
        <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
        <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>
        <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a>
    </p>

    <!-- Languages Usage Chart -->
    <h2>My Most Used Programming Languages</h2>
    <canvas id="languagesChart"></canvas>

    <script>
        const ctx = document.getElementById('languagesChart').getContext('2d');
        
        const languagesChart = new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['Python', 'JavaScript', 'Java', 'C++', 'SQL'], // Change these
                datasets: [{
                    label: 'Usage Percentage',
                    data: [40, 25, 15, 10, 10], // Adjust the usage percentages
                    backgroundColor: ['#3776AB', '#F7DF1E', '#007396', '#00599C', '#F29111'],
                    borderColor: ['#25507C', '#C7A500', '#005A8E', '#003F6B', '#BF7300'],
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 100
                    }
                }
            }
        });
    </script>

    <!-- GitHub Stats -->
    <p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=lewicki-hubert&show_icons=true&locale=en&layout=compact" alt="lewicki-hubert" /></p>

    <p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=lewicki-hubert&show_icons=true&locale=en" alt="lewicki-hubert" /></p>

    <p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=lewicki-hubert&" alt="lewicki-hubert" /></p>
</body>
</html>
