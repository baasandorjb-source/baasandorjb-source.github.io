<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Profile</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #667eea, #764ba2);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .card {
            background: white;
            width: 350px;
            border-radius: 15px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            text-align: center;
            padding: 30px;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #667eea;
        }

        h1 {
            margin: 15px 0 5px;
        }

        p {
            color: gray;
            font-size: 14px;
        }

        .skills {
            margin-top: 20px;
        }

        .skills span {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            margin: 5px;
        }

        .btn {
            margin-top: 20px;
            display: inline-block;
            padding: 10px 20px;
            background: #764ba2;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #5a3c91;
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://via.placeholder.com/150" class="profile-img">
        <h1>Баасандорж</h1>
        <p>Software Engineering Student</p>

        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
            <span>Java</span>
            <span>MySQL</span>
        </div>

        <a href="#" class="btn">Contact Me</a>
    </div>

</body>
</html>
