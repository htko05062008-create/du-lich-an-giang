<!DOCTYPE html>
<html lang="vi">
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Du lịch An Giang</title>

	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
		}

		.banner {
			background: url("images/banner_an_giang.png") no-repeat center;
			background-size: cover;
			padding: 10rem 0;
			text-align: center;
			color: darkgreen;
		}

		.slogan {
			background-color: #e6f4f1;
			text-align: center;
			padding: 2rem;
		}

		.row {
			display: flex;
			flex-wrap: wrap;
		}

		.block_3 {
			width: 33.33%;
		}

		#b3a:hover,
		#b3b:hover,
		#b3c:hover {
			font-size: 120%;
			color: red;
		}

		table {
			width: 90%;
			margin: auto;
		}

		.cell_text {
			width: 50%;
			padding: 3rem;
		}

		.cell_img {
			width: 50%;
		}

		.img {
			width: 100%;
		}

		footer {
			background-color: lightgrey;
			padding: 10px;
		}

		.link {
			color: navy;
		}

		a:hover {
			color: magenta;
		}

		form {
			margin: 40px;
		}
	</style>
</head>
<body>

<!-- HEADER -->
<header>
	<div class="banner">
		<h1>Du lịch An Giang</h1>
		<p>Khám phá vẻ đẹp miền Tây sông nước</p>
	</div>

	<div class="slogan">
		<div class="row">
			<div id="b3a" class="block_3">
				<h2>Thiên nhiên</h2>
				<p>Núi non – rừng tràm – sông nước</p>
			</div>
			<div id="b3b" class="block_3">
				<h2>Văn hóa</h2>
				<p>Bản sắc Chăm – Khmer – Kinh</p>
			</div>
			<div id="b3c" class="block_3">
				<h2>Trải nghiệm</h2>
				<p>Ẩm thực – lễ hội – tâm linh</p>
			</div>
		</div>
	</div>
</header>

<!-- NỘI DUNG -->
<table>
	<tr>
		<td class="cell_text">
			<h3>Giới thiệu An Giang</h3>
			<p>
				An Giang là tỉnh thuộc Đồng bằng sông Cửu Long, nổi tiếng với cảnh quan đa dạng
				và nền văn hóa đặc sắc.
			</p>
			<ul>
				<li>Núi Cấm – Núi Sam</li>
				<li>Rừng Tràm Trà Sư</li>
				<li>Miếu Bà Chúa Xứ</li>
				<li>Chợ nổi Long Xuyên</li>
			</ul>
		</td>
		<td class="cell_img">
			<img src="images/an_giang.png" class="img">
		</td>
	</tr>

	<tr>
		<td class="cell_img">
			<img src="images/tra_su.png" class="img">
		</td>
		<td class="cell_text">
			<h3>Du lịch sinh thái</h3>
			<p>
				Rừng Tràm Trà Sư là khu rừng ngập nước tiêu biểu, nơi du khách có thể
				ngồi xuồng ngắm chim và chụp ảnh thiên nhiên.
			</p>
		</td>
	</tr>

	<tr>
		<td class="cell_text">
			<h3>Du lịch tâm linh</h3>
			<p>
				Miếu Bà Chúa Xứ Núi Sam là điểm hành hương nổi tiếng,
				thu hút hàng triệu du khách mỗi năm.
			</p>
		</td>
		<td class="cell_img">
			<img src="images/mieu_ba.png" class="img">
		</td>
	</tr>
</table>

<!-- FORM ĐĂNG KÝ -->
<form>
	<fieldset style="width:50%; margin:auto;">
		<h2>ĐĂNG KÝ TOUR DU LỊCH AN GIANG</h2>

		<table>
			<tr>
				<td>Họ và tên:</td>
				<td><input type="text"></td>
			</tr>
			<tr>
				<td>Email:</td>
				<td><input type="email"></td>
			</tr>
			<tr>
				<td>Số điện thoại:</td>
				<td><input type="tel"></td>
			</tr>
			<tr>
				<td>Ngày khởi hành:</td>
				<td><input type="date"></td>
			</tr>
			<tr>
				<td>Chọn tour:</td>
				<td>
					<select>
						<option>Núi Cấm</option>
						<option>Rừng Tràm Trà Sư</option>
						<option>Miếu Bà Chúa Xứ</option>
						<option>Chợ nổi Long Xuyên</option>
					</select>
				</td>
			</tr>
			<tr>
				<td></td>
				<td><button type="submit">Gửi đăng ký</button></td>
			</tr>
		</table>
	</fieldset>
</form>

<!-- FOOTER -->
<footer>
	<div class="row">
		<div style="width:60%">
			<p>Liên hệ:</p>
			<ul>
				<li>📞 0987 654 321</li>
				<li>🌐 Du lịch An Giang</li>
			</ul>
		</div>
		<div style="width:40%">
			<p>Khám phá thêm:</p>
			<ul>
				<li>Du lịch sinh thái</li>
				<li>Du lịch tâm linh</li>
			</ul>
		</div>
	</div>
</footer>

</body>
</html>
