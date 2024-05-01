<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>หน้าเข้าสู่ระบบ</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>เข้าสู่ระบบ</h1>
    <form action="login.php" method="post">
      <label for="username">ชื่อผู้ใช้:</label>
      <input type="text" id="username" name="username" required>

      <label for="password">รหัสผ่าน:</label>
      <input type="password" id="password" name="password" required>

      <button type="submit">เข้าสู่ระบบ</button>
    </form>

    <p><a href="#">ลืมรหัสผ่าน?</a></p>
    <p><a href="#">สมัครสมาชิกใหม่</a></p>
  </div>

  <script src="script.js"></script>
</body>
</html>
