<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Bài tập DOM JavaScript</title>
</head>
<body>

  <select id="colorSelect">
    <option value="">-- Chọn màu --</option>
    <option value="red">Đỏ</option>
    <option value="green">Xanh lá</option>
    <option value="blue">Xanh dương</option>
    <option value="Silver">Xám</option>
    <option value="SkyBlue">Xanh nhạt</option>
  </select>

  <hr>

  <form id="userForm">
    <label>Họ tên: <input type="text" id="name" required></label><br><br>
    <label>Email: <input type="email" id="email" required></label><br><br>
    <label>Số điện thoại: <input type="tel" id="phone" required></label><br><br>
    <label>Địa chỉ: <input type="text" id="address" required></label><br><br>
    <label>Ngày sinh: <input type="date" id="dob" required></label><br><br>

    <label>Giới tính:</label><br>
    <input type="radio" id="male" name="gender" value="Nam" required> <label for="male">Nam</label><br>
    <input type="radio" id="female" name="gender" value="Nữ"> <label for="female">Nữ</label><br><br>

    <label>Sở thích:</label><br>
    <input type="checkbox" name="hobbies" value="Đọc sách"> Đọc sách<br>
    <input type="checkbox" name="hobbies" value="Du lịch"> Du lịch<br>
    <input type="checkbox" name="hobbies" value="Âm nhạc"> Âm nhạc<br>
    <input type="checkbox" name="hobbies" value="Thể thao"> Thể thao<br><br>

    <button type="submit">Gửi</button>
  </form>

  <table border="1" id="userTable">
    <thead>
      <tr>
        <th>Họ tên</th>
        <th>Email</th>
        <th>Số điện thoại</th>
        <th>Địa chỉ</th>
        <th>Ngày sinh</th>
        <th>Giới tính</th>
        <th>Sở thích</th>
      </tr>
    </thead>
    <tbody>

    </tbody>
  </table>

  <script src="script.js"></script>
</body>
</html>

