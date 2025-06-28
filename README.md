<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Join WhatsApp Channel</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      background-color: #f0f2f5;
    }
    .container {
      text-align: center;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      max-width: 350px;
      width: 90%;
    }
    h1 {
      font-size: 22px;
      color: #25D366;
      margin: 0 0 10px;
    }
    p {
      font-size: 14px;
      margin: 0 0 15px;
    }
    .whatsapp-button {
      display: inline-block;
      padding: 10px 20px;
      background: #25D366;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 20px;
      transition: background 0.3s;
    }
    .whatsapp-button:hover {
      background: #20b858;
    }
    .qrcode-container {
      margin-top: 15px;
      padding: 8px;
      border: 2px solid #25D366;
      border-radius: 8px;
      display: inline-block;
    }
    @media (max-width: 600px) {
      .container { padding: 15px; }
      h1 { font-size: 18px; }
      .whatsapp-button { padding: 8px 16px; font-size: 14px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Join Our WhatsApp Channel</h1>
    <p>Get the latest updates by joining our channel!</p>
    <a href="https://whatsapp.com/channel/0029VaS41YEDeON6Qr6Csh3D" target="_blank" class="whatsapp-button">Join Now</a>
    <p>Or scan the QR code:</p>
    <div class="qrcode-container" id="qrcode"></div>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.min.js"></script>
  <script>
    new QRCode(document.getElementById("qrcode"), {
      text: "https://whatsapp.com/channel/0029VaS41YEDeON6Qr6Csh3D",
      width: 120,
      height: 120
    });
  </script>
</body>
</html>
