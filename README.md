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

    /* Banner đầu trang */
    header {
      background-image: url("https://source.unsplash.com/1200x500/?An-Giang,Vietnam");
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 18px;
      background: rgba(0,0,0,0.5);
      display: inline-block;
      padding: 8px 15px;
      border-radius: 5px;
    }

    .section {
      margin: 20px auto;
      width: 90%;
      max-width: 960px;
    }

    h2 {
      color: #00796b;
    }

    /* Giới thiệu có ảnh */
    .intro {
      display: flex;
      gap: 20px;
      align-items: center;
      background: white;
      padding: 15px;
      border-radius: 8px;
    }
    .intro img {
      width: 300px;
      border-radius: 8px;
      object-fit: cover;
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
      .intro {
        flex-direction: column;
      }
      .intro img {
        width: 100%;
      }
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
  <div class="intro">
    <img src="https://source.unsplash.com/600x400/?river,An-Giang" alt="An Giang">
    <p>
      An Giang là tỉnh thuộc vùng Đồng bằng sông Cửu Long, nổi tiếng với cảnh quan đa dạng,
      từ núi non đến sông nước và rừng tràm. Du khách có thể tham quan nhiều điểm đến hấp dẫn,
      tìm hiểu văn hóa bản địa và thưởng thức ẩm thực đặc sản.
    </p>
  </div>
</div>

<div class="section">
  <h2>Địa điểm nổi bật</h2>
  <div class="cards">
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?mountain,Vietnam" alt="Núi Cấm">
      <p><strong>Núi Cấm</strong> – Điểm đến với cảnh đẹp thiên nhiên và không khí trong lành.</p>
    </div>
    <div class="card">
      <img src="https://source.unsplash.com/400x300/?forest,r
