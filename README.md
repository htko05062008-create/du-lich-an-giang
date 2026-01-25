<!DOCTYPE html>
<html>
<head>
 <meta charset="utf-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>Du lịch An Giang</title>

 <style>
  .banner {
      background: url("images/banner.png") no-repeat center center;
      background-size: cover;
      padding: 12rem 0;
      text-align: center;
      color: darkred;
  }

  .slogan {
      background-color: rgb(230, 240, 250);
      text-align: center;
      padding: 2rem;
  }

  .row {
      display: flex;
      flex-wrap: wrap;
      padding: 0 3rem;
  }

  .block_3 {
      width: 33.33333%;
  }

  #b3a:hover, #b3b:hover, #b3c:hover {
      font-size: 120%;
      color: red;
  }

  table {
      width: 90%;
      margin: 2rem auto;
  }

  .cell_img, .cell_text {
      width: 50%;
  }

  .cell_text {
      padding-left: 5rem;
  }

  .img {
      width: 100%;
      height: auto;
  }

  .link {
      color: navy;
  }

  a:hover {
      color: magenta;
  }

  footer {
      background-color: lightgrey;
      padding: 10px;
  }

  fieldset {
      width: 60%;
      margin: 2rem auto;
      padding: 1.5rem;
  }

  form table {
      width: 100%;
  }

  form td {
      padding: 8px;
  }

  button {
      color: blue;
      font-weight: bold;
  }
 </style>
</head>

<body>

<!-- ===== HEADER ===== -->
<header>
 <div class="banner">
  <h1>Du lịch An Giang – Vùng đất non nước hữu tình</h1>
 </div>

 <div class="slogan">
  <div class="row">
   <div id="b3a" class="block_3">
    <h2>Thiên nhiên</h2>
    <p>Núi non – sông nước – rừng tràm</p>
   </div>
   <div id="b3b" class="block_3">
    <h2>Văn hóa</h2>
    <p>Bản sắc dân tộc đa dạng</p>
   </div>
   <div id="b3c" class="block_3">
    <h2>Trải nghiệm</h2>
    <p>Ẩm thực và lễ hội đặc sắc</p>
   </div>
  </div>
 </div>
</header>

<!-- ===== NỘI DUNG ===== -->
<table>
 <tr>
  <td class="cell_text">
   <h3>An Giang – Điểm đến hấp dẫn</h3>
   <ul>
    <li>Rừng tràm Trà Sư</li>
    <li>Núi Cấm – Thất Sơn</li>
    <li>Miếu Bà Chúa Xứ Núi Sam</li>
    <li>Ẩm thực đậm chất miền Tây</li>
   </ul>
  </td>
  <td class="cell_img">
   <img src="images/an_giang.png" class="img">
  </td>
 </tr>
</table>

<!-- ===== FORM ĐĂNG KÝ ===== -->
<form>
 <fieldset>
  <h2 style="text-align:center;">ĐĂNG KÝ THAM QUAN DU LỊCH AN GIANG</h2>

  <table>
   <tr>
    <td><label for="hoten">Họ và tên:</label></td>
    <td><input id="hoten" type="text" required></td>
   </tr>

   <tr>
    <td><label for="email">Email:</label></td>
    <td><input id="email" type="email" required></td>
   </tr>

   <tr>
    <td><label for="ngaysinh">Ngày sinh:</label></td>
    <td><input id="ngaysinh" type="date"></td>
   </tr>

   <tr>
    <td>Giới tính:</td>
    <td>
     <input type="radio" name="gioitinh" id="nam">
     <label for="nam">Nam</label>
     <input type="radio" name="gioitinh" id="nu">
     <label for="nu">Nữ</label>
    </td>
   </tr>
   <tr>
    <td><label for="diachi">Địa chỉ:</label></td>
    <td><textarea id="diachi" rows="4"></textarea></td>
   </tr>

   <tr>
    <td>Sở thích:</td>
    <td>
     <input type="checkbox" id="st1">
     <label for="st1">Sinh thái</label>
     <input type="checkbox" id="st2">
     <label for="st2">Tâm linh</label>
     <input type="checkbox" id="st3">
     <label for="st3">Ẩm thực</label>
    </td>
   </tr>

   <tr>
    <td><label for="hoso">Giấy tờ đính kèm:</label></td>
    <td><input type="file" id="hoso"></td>
   </tr>

   <tr>
    <td><label for="tour">Chọn điểm tham quan:</label></td>
    <td>
     <select id="tour">
      <option>Rừng tràm Trà Sư</option>
      <option>Núi Cấm</option>
      <option>Miếu Bà Chúa Xứ</option>
      <option>Hồ Tà Pạ</option>
     </select>
    </td>
   </tr>

   <tr>
    <td></td>
    <td><button type="submit">Gửi thông tin</button></td>
   </tr>
  </table>
 </fieldset>
</form>

<!-- ===== FOOTER ===== -->
<footer>
 <p>© Du lịch An Giang | Liên hệ: 0296 123 456</p>
</footer>

</body>
</html>
