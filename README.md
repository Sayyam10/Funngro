<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KYC & Non-KYC Projects</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #121e2c, #004e92, #00b4db);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            max-width: 900px;
            padding: 30px;
            background: rgba(18, 30, 44, 0.9);
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
            text-align: center;
            overflow: hidden;
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
        }
        .header img {
            max-width: 100%;
            height: auto;
        }
        h2 {
            color: #07ab67;
            text-transform: uppercase;
            letter-spacing: 2px;
            border-bottom: 2px solid #07ab67;
            display: inline-block;
            padding-bottom: 5px;
            animation: glow 1.5s infinite alternate;
        }
        @keyframes glow {
            from { text-shadow: 0 0 5px #07ab67; }
            to { text-shadow: 0 0 15px #07ab67; }
        }
        .project {
            background: rgba(18, 30, 44, 0.85);
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px;
            transition: 0.3s;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .project:hover {
            background: #07ab67;
            color: #121e2c;
            transform: scale(1.05);
            box-shadow: 0 0 20px rgba(7, 171, 103, 0.6);
        }
        .project:hover h3 {
            color: #121e2c; /* Changes project title color to #121e2c on hover */
        }
        .project:hover a {
            color: #121e2c; /* Changes link color to #121e2c on hover */
        }
        .project:hover .btn {
            background: #121e2c; /* Changes button background color to #121e2c on hover */
            color: #07ab67; /* Changes button text color to #07ab67 on hover */
        }
        .project a {
            color: #07ab67;
            text-decoration: none;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            background: #07ab67;
            color: #121e2c;
            padding: 12px 18px;
            margin-top: 10px;
            border-radius: 8px;
            font-weight: bold;
            transition: 0.3s;
            box-shadow: 0 0 10px rgba(7, 171, 103, 0.6);
            cursor: pointer;
        }
        .btn:hover {
            background: #121e2c; /* Changes button background color to #121e2c on hover */
            color: #07ab67; /* Changes button text color to #07ab67 on hover */
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="https://cdn.prod.website-files.com/638b48215fd2fd34538fa6bc/638c80735fd2fd0810a24fba_funngro-logo.svg" alt="Funngro Logo">
        </div>
        <h2>KYC Projects</h2>
        <div class="project">
            <h3>Angle One</h3>
            <a href="https://funngro.page.link/PAAc" target="_blank" rel="noopener noreferrer">🔗 KYC Link</a>
            <button class="btn" onclick="openLink('https://drive.google.com/file/d/1EJ2M4_IcelJAyu4weIY1i5qIlvWxVudi/view?usp=drivesdk')">📺 Watch Tutorial</button>
        </div>
        <div class="project">
            <h3>MStock</h3>
            <a href="https://funngro.page.link/jqYj" target="_blank" rel="noopener noreferrer">🔗 KYC Link</a>
            <button class="btn" onclick="openLink('https://drive.google.com/file/d/1TnnNM42lCmamknKjqQIKHfcHrKKyAhRN/view?usp=drivesdk')">📺 Watch Tutorial</button>
        </div>
        <h2>Non-KYC Projects</h2>
        <div class="project">
            <h3>First Naukri</h3>
            <a href="https://funngro.page.link/Jpjy" target="_blank" rel="noopener noreferrer">🔗 Sign-up</a>
        </div>
        <div class="project">
            <h3>Jar</h3>
            <a href="https://funngro.page.link/ZLRV" target="_blank" rel="noopener noreferrer">🔗 Sign-up</a>
        </div>
        <p style="text-align:center; color:#07ab67; font-weight:bold;">🔊 Use Referral Code: FUN500 (Compulsory)</p>
    </div>

    <script>
        function openLink(url) {
            window.open(url, '_blank', 'noopener,noreferrer');
        }
    </script>
</body>
</html>