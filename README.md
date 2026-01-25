# to3
<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Du lịch An Giang</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
    }
    header {
      background: #00796b;
      color: white;
      text-align: center;
      padding: 20px 0;
    }
    .section {
      margin: 20px auto;
      width: 90%;
      max-width: 960px;
    }
    h2 {
      color: #00796b;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }
    .card {
      background: white;
      border-radius: 8px;
      overflow: hidden;
      width: calc(50% - 10px);
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .card p {
      padding: 10px;
    }
    .btn {
      display: inline-block;
      background: #00796b;
      color: white;
      padding: 10px 18px;
      border-radius: 4px;
      text-decoration: none;
      margin-top: 10px;
    }
    @media (max-width: 600px) {
      .card { width: 100%; }
    }
  </style>
</head>
<body>

<header>
  <h1>Du lịch An Giang</h1>
  <p>Khám phá thiên nhiên – văn hóa – trải nghiệm đặc sắc miền Tây Nam Bộ</p>
</header>

<div class="section">
  <h2>Giới thiệu</h2>
  <p>An Giang là tỉnh thuộc vùng Đồng bằng sông Cửu Long, nổi tiếng với cảnh quan đa dạng, từ núi non đến sông nước và rừng tràm. Du khách có thể tham quan nhiều điểm đến hấp dẫn, tìm hiểu văn hóa bản địa và thưởng thức ẩm thực đặc sản.</p>
</div>

<div class="section">
  <h2>Địa điểm nổi bật</h2>
  <div class="cards">
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?mountain,Vietnam" alt="Núi Cấm">
      <p><strong>Núi Cấm</strong> – Điểm đến với cảnh đẹp thiên nhiên và không khí trong lành.</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?forest,river" alt="Rừng Tràm Trà Sư">
      <p><strong>Rừng Tràm Trà Sư</strong> – Trải nghiệm du lịch sinh thái thú vị.</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?temple,Vietnam" alt="Miếu Bà Chúa Xứ">
      <p><strong>Miếu Bà Chúa Xứ</strong> – Điểm tâm linh nổi tiếng.</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?market,boat" alt="Chợ nổi Long Xuyên">
      <p><strong>Chợ nổi Long Xuyên</strong> – Trải nghiệm văn hóa chợ nổi độc đáo.</p>
    </div>
  </div>
</div>

<div class="section">
  <h2>Các tour hấp dẫn</h2>
  <ul>
    <li>Tour 1 ngày: Châu Đốc – Miếu Bà – Núi Sam</li>
    <li>Tour 2 ngày 1 đêm: Núi Cấm – Rừng Tràm Trà Sư</li>
    <li>Tour 3 ngày: Long Xuyên – Núi Cấm – Trà Sư</li>
  </ul>
  <a href="#booking" class="btn">Đăng ký tour</a>
</div>

<div class="section" id="booking">
  <h2>Liên hệ & Đăng ký</h2>
  <p>📞 Điện thoại: 0987 654 321</p>
  <p>Nếu bạn muốn đăng ký tour hoặc cần thêm thông tin, vui lòng gọi ngay hoặc gửi email.</p>
</div>

</body>
</html>
