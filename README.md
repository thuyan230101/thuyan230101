<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang giới thiệu về Thúy An</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .project {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .project img {
            width: 200px;
            margin: 10px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Trang giới thiệu về Thúy An</h1>
    </header>
    <nav>
        <a href="#about">Giới thiệu</a>
        <a href="#projects">Dự án</a>
        <a href="#contact">Liên hệ</a>
    </nav>
    <section id="about">
        <h2>Giới thiệu về Thúy An</h2>
        <p>Xin chào! Tôi là Thúy An, một nhà phát triển web đam mê sáng tạo và hiện đang làm việc tại công ty ABC. Tôi yêu thích việc xây dựng các ứng dụng web và đam mê khám phá công nghệ mới.</p>
    </section>
    <section id="projects">
        <h2>Dự án</h2>
        <div class="project">
            <div>
                <img src="project1.jpg" alt="Dự án 1">
                <p>Dự án 1 - Mô tả dự án này.</p>
            </div>
            <div>
                <img src="project2.jpg" alt="Dự án 2">
                <p>Dự án 2 - Mô tả dự án này.</p>
            </div>
            <div>
                <img src="project3.jpg" alt="Dự án 3">
                <p>Dự án 3 - Mô tả dự án này.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Liên hệ</h2>
        <p>Bạn có thể liên hệ với tôi qua:</p>
        <p>Email: thuyan@example.com</p>
        <p>Phone: 0123-456-789</p>
    </section>
    <footer>
        &copy; 2024 Trang giới thiệu về Thúy An
    </footer>
</body>
</html>
