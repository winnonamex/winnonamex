<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liên Quân Mobile - Cộng Đồng Game Thủ</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#">
                    <img src="images/logo_lqm.png" alt="Liên Quân Mobile Logo">
                </a>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Trang Chủ</a></li>
                    <li><a href="#heroes">Tướng</a></li>
                    <li><a href="#news">Tin Tức</a></li>
                    <li><a href="#guides">Hướng Dẫn</a></li>
                    <li><a href="#community">Cộng Đồng</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="hero-section">
            <div class="container">
                <h1>Chào Mừng Đến Với Thế Giới Liên Quân Mobile!</h1>
                <p>Khám phá các vị tướng, cập nhật tin tức mới nhất và tham gia cộng đồng game thủ sôi nổi.</p>
                <a href="#heroes" class="btn-primary">Tìm hiểu về Tướng</a>
            </div>
        </section>

        <section id="heroes" class="section-padded">
            <div class="container">
                <h2>Các Vị Tướng</h2>
                <div class="hero-grid">
                    <div class="hero-card">
                        <img src="images/hero_valhein.jpg" alt="Valhein">
                        <h3>Valhein</h3>
                        <p>Xạ Thủ | Sát thương tầm xa</p>
                        <a href="#" class="btn-secondary">Chi tiết</a>
                    </div>
                    <div class="hero-card">
                        <img src="images/hero_airi.jpg" alt="Airi">
                        <h3>Airi</h3>
                        <p>Đấu Sĩ | Sát thủ linh hoạt</p>
                        <a href="#" class="btn-secondary">Chi tiết</a>
                    </div>
                    <div class="hero-card">
                        <img src="images/hero_murad.jpg" alt="Murad">
                        <h3>Murad</h3>
                        <p>Sát Thủ | Gây sát thương đột biến</p>
                        <a href="#" class="btn-secondary">Chi tiết</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="news" class="section-padded bg-light">
            <div class="container">
                <h2>Tin Tức Mới Nhất</h2>
                <div class="news-grid">
                    <article class="news-item">
                        <img src="images/news_update.jpg" alt="Cập nhật phiên bản mới">
                        <h3>Cập Nhật Phiên Bản Mới: Mùa Giải Khởi Nguyên</h3>
                        <p>Khám phá những thay đổi lớn về tướng, trang bị và bản đồ...</p>
                        <a href="#" class="read-more">Đọc thêm <i class="fas fa-arrow-right"></i></a>
                    </article>
                    <article class="news-item">
                        <img src="images/news_event.jpg" alt="Sự kiện mới">
                        <h3>Sự Kiện Hè Sôi Động: Nhận Trang Phục Miễn Phí!</h3>
                        <p>Tham gia các hoạt động trong game để nhận về nhiều phần quà giá trị...</p>
                        <a href="#" class="read-more">Đọc thêm <i class="fas fa-arrow-right"></i></a>
                    </article>
                </div>
            </div>
        </section>

        <section id="guides" class="section-padded">
            <div class="container">
                <h2>Hướng Dẫn & Mẹo Chơi</h2>
                <div class="guide-grid">
                    <div class="guide-card">
                        <h3><i class="fas fa-book"></i> Hướng Dẫn Đi Rừng Hiệu Quả</h3>
                        <p>Nắm vững cách farm, kiểm soát mục tiêu và gank đường.</p>
                        <a href="#" class="btn-secondary">Xem chi tiết</a>
                    </div>
                    <div class="guide-card">
                        <h3><i class="fas fa-trophy"></i> Xây Dựng Trang Bị Mạnh Nhất</h3>
                        <p>Phân tích các loại trang bị và cách lên đồ phù hợp cho từng tướng.</p>
                        <a href="#" class="btn-secondary">Xem chi tiết</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="community" class="section-padded bg-light">
            <div class="container text-center">
                <h2>Tham Gia Cộng Đồng</h2>
                <p>Kết nối với hàng triệu game thủ Liên Quân khác!</p>
                <div class="social-links">
                    <a href="https://facebook.com/lienquanmobile" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a>
                    <a href="https://youtube.com/lienquanmobile" target="_blank"><i class="fab fa-youtube"></i> YouTube</a>
                    <a href="#" target="_blank"><i class="fab fa-discord"></i> Discord</a>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Liên Quân Mobile Fanpage. Tất cả quyền được bảo lưu.</p>
            <p>Trang web này được tạo bởi cộng đồng hâm mộ.</p>
        </div>
    </footer>
</body>
</html>
2. File style.css (CSS cơ bản)
Bạn sẽ cần tạo một file style.css trong cùng thư mục với index.html.

CSS

/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.section-padded {
    padding: 60px 0;
}

.bg-light {
    background-color: #eaeaea;
}

.text-center {
    text-align: center;
}

/* Header */
header {
    background-color: #2c3e50; /* Dark blue/grey */
    color: #fff;
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo img {
    height: 50px; /* Adjust as needed */
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 25px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #f39c12; /* Orange/Gold for hover */
}

/* Buttons */
.btn-primary {
    display: inline-block;
    background-color: #e67e22; /* Orange */
    color: #fff;
    padding: 10px 25px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    transition: background-color 0.3s ease;
}

.btn-primary:hover {
    background-color: #d35400; /* Darker orange */
}

.btn-secondary {
    display: inline-block;
    background-color: #3498db; /* Blue */
    color: #fff;
    padding: 8px 15px;
    text-decoration: none;
    border-radius: 4px;
    margin-top: 10px;
    font-size: 0.9em;
    transition: background-color 0.3s ease;
}

.btn-secondary:hover {
    background-color: #2980b9; /* Darker blue */
}

/* Hero Section */
.hero-section {
    background: url('images/hero_banner.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
    min-height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
}

.hero-section h1 {
    font-size: 3.5em;
    margin-bottom: 10px;
}

.hero-section p {
    font-size: 1.3em;
    margin-bottom: 30px;
    max-width: 800px;
}

/* Sections General */
h2 {
    text-align: center;
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #2c3e50;
    position: relative;
    padding-bottom: 10px;
}

h2::after {
    content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    width: 60px;
    height: 3px;
    background-color: #e67e22;
}

/* Hero Grid */
.hero-grid, .news-grid, .guide-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.hero-card, .news-item, .guide-card {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s ease;
}

.hero-card:hover, .news-item:hover, .guide-card:hover {
    transform: translateY(-5px);
}

.hero-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    display: block;
}

.hero-card h3 {
    margin: 15px 0 5px;
    color: #34495e;
}

.hero-card p {
    font-size: 0.9em;
    color: #7f8c8d;
    padding: 0 15px 15px;
}

/* News Section */
.news-item img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
}

.news-item h3 {
    margin: 15px 15px 10px;
    font-size: 1.3em;
    color: #34495e;
}

.news-item p {
    font-size: 0.9em;
    color: #555;
    padding: 0 15px;
    margin-bottom: 15px;
}

.news-item .read-more {
    display: block;
    padding: 10px 15px;
    background-color: #f39c12;
    color: #fff;
    text-decoration: none;
    text-align: right;
    border-bottom-left-radius: 8px;
    border-bottom-right-radius: 8px;
    transition: background-color 0.3s ease;
}

.news-item .read-more:hover {
    background-color: #e67e22;
}

/* Guide Section */
.guide-card {
    padding: 25px;
    text-align: left;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.guide-card h3 {
    color: #34495e;
    font-size: 1.4em;
    margin-bottom: 10px;
}

.guide-card h3 i {
    margin-right: 10px;
    color: #e67e22;
}

.guide-card p {
    font-size: 0.95em;
    color: #666;
    margin-bottom: 20px;
    flex-grow: 1; /* Makes sure paragraph takes up available space */
}

/* Community Section */
.social-links {
    margin-top: 30px;
}

.social-links a {
    display: inline-block;
    background-color: #3498db;
    color: #fff;
    padding: 12px 25px;
    margin: 0 10px;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.1em;
    transition: background-color 0.3s ease;
}

.social-links a:hover {
    background-color: #2980b9;
}

.social-links a i {
    margin-right: 8px;
}

/* Footer */
footer {
    background-color: #333;
    color: #eee;
    text-align: center;
    padding: 30px 0;
    font-size: 0.9em;
}

footer p {
    margin: 5px 0;
}

/* Responsive Design */
@media (max-width: 768px) {
    header .container {
        flex-direction: column;
    }
    nav ul {
        flex-wrap: wrap;
        justify-content: center;
        margin-top: 10px;
    }
    nav ul li {
        margin: 5px 15px;
    }
    .hero-section h1 {
        font-size: 2.5em;
    }
    .hero-section p {
        font-size: 1.1em;
    }
    .hero-grid, .news-grid, .guide-grid {
        grid-template-columns: 1fr;
    }
}
