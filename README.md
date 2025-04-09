<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Đăng nhập - Bill Fake</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background: #0f172a;
      color: #1e293b;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      padding: 20px;
    }
    .container {
      background: white;
      border-radius: 12px;
      display: flex;
      flex-direction: row;
      overflow: hidden;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      max-width: 900px;
      width: 100%;
    }
    .left {
      background: #f1f5f9;
      padding: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      flex: 1;
    }
    .left img {
      width: 300px;
      max-width: 100%;
    }
    .right {
      padding: 40px;
      flex: 1;
    }
    h1 {
      color: #f97316;
      font-size: 28px;
      font-weight: 700;
    }
    h2 {
      margin-top: 8px;
      font-size: 18px;
      font-weight: 500;
    }
    label {
      display: block;
      margin-top: 20px;
      font-weight: 600;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .btn {
      margin-top: 20px;
      width: 100%;
      background: #3b82f6;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-weight: 600;
    }
    .info {
      margin-top: 20px;
      background: #f8fafc;
      padding: 10px;
      border-radius: 6px;
      font-size: 14px;
    }
    .info strong {
      display: block;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
      .left, .right {
        padding: 20px;
      }
      .left img {
        width: 200px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="left">
      <img src="https://cdn-icons-png.flaticon.com/512/2910/2910791.png" alt="illustration">
    </div>
    <div class="right">
      <h1>BILL FAKE</h1>
      <h2>All In One</h2>
      <form>
        <label for="username">* Tên đăng nhập</label>
        <input type="text" id="username" placeholder="Nhập tên đăng nhập">

        <label for="password">* Mật khẩu</label>
        <input type="password" id="password" placeholder="Nhập mật khẩu">

        <button type="submit" class="btn">ĐĂNG NHẬP</button>
      </form>
      <div class="info">
        <strong>Thông tin đăng nhập của bạn</strong>
        FingerprintId: cdf3929c98112dac92ef11ba2f35206<br>
        IP: 
      </div>
    </div>
  </div>
</body>
</html>
