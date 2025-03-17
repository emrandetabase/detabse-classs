<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Thinkers Database Class</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
            background-color: #7B1113;
            color: white;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
        }
        .logos {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .logo {
            max-width: 70px;
        }
        .logo-container {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .white-circle {
            width: 80px;
            height: 80px;
            background-color: white;
            border-radius: 50%;
            position: absolute;
            z-index: 0;
        }
        .logo-container img {
            position: relative;
            z-index: 1;
        }
        h1 {
            font-size: 42px;
            font-weight: bold;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.6);
            color: #FFD700;
            padding-bottom: 10px;
            border-bottom: 3px solid #FFD700;
        }
        .content {
            font-size: 14px;
            margin-top: 20px;
            line-height: 1.6;
            font-family: 'Georgia', serif;
        }
        .details {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
        }
        .details p {
            font-size: 16px;
            font-weight: bold;
            background: rgba(0, 0, 0, 0.3);
            padding: 10px;
            border-radius: 5px;
            flex: 1;
            text-align: center;
            margin: 5px;
            white-space: nowrap;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logos">
            <img src="Microsoft_Office_Access_(2019-present).svg.png" alt="Access Logo" class="logo">
            <div class="logo-container">
                <div class="white-circle"></div>
                <img src="image-removebg-preview (2).png" alt="Creative Thinkers Logo" class="logo">
            </div>
        </div>
        <h1>Creative Thinkers Database Class</h1>
        <div class="content">
            <p>The Database class was a two-month intensive program under the Access Program, focused on equipping students with core database management skills. The course covered essential concepts such as data organization, analysis, and structuring, offering practical experience through hands-on projects. Students applied their knowledge to solve real-world database challenges, enhancing both their technical and analytical abilities.</p>
        </div>
        <div class="details">
            <p>Instructor: <strong>Emran Akbari</strong></p>
            <p>Duration: <strong>Two months</strong></p>
            <p>Organization: <strong>Creative Thinkers</strong></p>
        </div>
    </div>
</body>
</html>
