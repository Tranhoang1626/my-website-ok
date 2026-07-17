<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Của Tôi</title>
    <style>
        /* Thiết lập cơ bản */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Thanh điều hướng (Header) */
        header {
            background-color: #ffffff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .nav-container {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #2c3e50;
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 20px;
        }

        .nav-links a {
            text-decoration: none;
            color: #555;
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #3498db;
        }

        /* Khu vực giới thiệu chính (Hero Section) */
        .hero {
            max-width: 1000px;
            margin: 60px auto;
            padding: 40px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
            color: #2c3e50;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            color: #7f8c8d;
            max-width: 600px;
            margin: 0 auto 30px;
        }

        .btn {
            display: inline-block;
            background-color: #3498db;
            color: white;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s, transform 0.2s;
            box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3);
        }

        .btn:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
        }

        /* Khu vực tính năng/Nội dung (Features Section) */
        .content-section {
            background-color: #ffffff;
            padding: 60px 20px;
        }

        .section-container {
            max-width: 1000px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            color: #2c3e50;
            margin-bottom: 40px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card {
            background: #fdfdfd;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.03);
            border: 1px solid #eee;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 20px;
        }

        .card p {
            color: #7f8c8d;
            font-size: 15px;
        }

        /* Chân trang (Footer) */
        footer {
            background-color: #2c3e50;
            color: #bdc3c7;
            text-align: center;
            padding: 30px 20px;
            margin-top: 60px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Thanh Điều Hướng -->
    <header>
        <div class="nav-container">
            <a href="#" class="logo">My Website</a>
            <ul class="nav-links">
                <li><a href="#about">Giới thiệu</a></li>
                <li><a href="#services">Dịch vụ</a></li>
                <li><a href="#contact">Liên hệ</a></li>
            </ul>
        </div>
    </header>

    <!-- Phần Giới Thiệu Chính -->
    <section class="hero" id="about">
        <h1>Xin chào, mình là Hoàng!</h1>
        <p>Chào mừng bạn đến với góc nhỏ của mình trên Internet. Đây là nơi mình chia sẻ những dự án, kiến thức và sở thích cá nhân.</p>
        <a href="#services" class="btn">Khám phá ngay</a>
    </section>

    <!-- Phần Nội Dung / Tính Năng -->
    <section class="content-section" id="services">
        <div class="section-container">
            <h2 class="section-title">Mình làm được gì?</h2>
            
            <div class="grid">
                <!-- Thẻ nội dung 1 -->
                <div class="card">
                    <h3>Thiết kế Web</h3>
                    <p>Tạo ra các giao diện trang web đẹp mắt, hiện đại và tối ưu hóa trải nghiệm người dùng trên mọi thiết bị.</p>
                </div>

                <!-- Thẻ nội dung 2 -->
                <div class="card">
                    <h3>Lập trình HTML/CSS</h3>
                    <p>Biến các ý tưởng thiết kế sáng tạo thành các trang web hoạt động mượt mà và chuẩn SEO.</p>
                </div>

                <!-- Thẻ nội dung 3 -->
                <div class="card">
                    <h3>Tối ưu hóa</h3>
                    <p>Giúp trang web tải nhanh hơn, cấu trúc code gọn gàng, sạch sẽ giúp dễ dàng bảo trì và nâng cấp.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Chân trang -->
    <footer>
        <p>&copy; 2026 Designed by Tranhoang1626. Powered by GitHub Pages.</p>
    </footer>

</body>
</html>
