<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0E1324;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .profile-card {
            background-color: #1D2544;
            border-radius: 12px;
            padding: 20px;
            width: 580px;
            color: #FFFFFF;
            display: flex;
            align-items: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }

        .profile-card img {
            border-radius: 50%;
            width: 60px;
            height: 60px;
            margin-right: 20px;
            border: 2px solid #1D2544;
        }

        .profile-info {
            flex-grow: 1;
        }

        .profile-info h2 {
            margin: 0;
            font-size: 22px;
            color: #F5A623;
        }

        .profile-info a {
            color: #789FF2;
            text-decoration: none;
            font-size: 14px;
        }

        .stats {
            display: flex;
            gap: 12px;
        }

        .stat {
            display: flex;
            align-items: center;
            background-color: #283259;
            border-radius: 10px;
            padding: 5px 10px;
            font-size: 14px;
        }

        .stat img {
            width: 18px;
            height: 18px;
            margin-right: 5px;
        }

        .stat.blue {
            background-color: #2F71D1;
        }

        .stat.pink {
            background-color: #E84D8A;
        }

        .stat.orange {
            background-color: #F5A623;
        }

        .stat.green {
            background-color: #28C76F;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="u1.png" alt="Profile Picture">
        <div class="profile-info">
            <h2>Muhammad Usman Gill</h2>
            <a href="https://github.com/USMANGILL265" target="_blank">GitHub.com/USMANGILL265</a>
        </div>
        <div class="stats">
            <div class="stat blue">
                <img src="https://img.icons8.com/ios-filled/50/ffffff/user-group-man-woman.png" alt="Followers">
                <span>7</span>
            </div>
            <div class="stat pink">
                <img src="https://img.icons8.com/ios-filled/50/ffffff/book.png" alt="Repositories">
                <span>11</span>
            </div>
            <div class="stat orange">
                <img src="https://img.icons8.com/ios-filled/50/ffffff/star.png" alt="Stars">
                <span>2</span>
            </div>
            <div class="stat green">
                <img src="https://img.icons8.com/ios-filled/50/ffffff/contributions.png" alt="Contributions">
                <span>80</span>
            </div>
        </div>
    </div>
</body>
</html>

