<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>B-Bank Online Banking</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f2f2f2;
      padding: 40px;
    }
    .bank-container {
      max-width: 400px;
      margin: auto;
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      text-align: center;
    }
    h1 {
      color: #004080;
    }
    .balance {
      font-size: 2em;
      color: green;
      margin: 20px 0;
    }
    .btn {
      display: block;
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      background-color: #004080;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }
    .btn:disabled {
      background-color: #888;
      cursor: not-allowed;
    }
    .support {
      margin-top: 20px;
    }
    .support a {
      color: #25D366;
      font-weight: bold;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="bank-container">
    <h1>B-Bank Online</h1>
    <p>Account Holder: John Doe</p>
    <div class="balance">Balance: £7,204,890.19</div>
    <button class="btn" onclick="alert('Withdrawals are currently unavailable. Please contact support.')">Withdraw</button>
    <button class="btn" onclick="alert('Deposits are currently unavailable. Please contact support.')">Deposit</button>

    <div class="support">
      <p>Need help? Contact us:</p>
      <a href="https://wa.me/447743033345" target="_blank">WhatsApp Customer Care</a>
    </div>
  </div>
</body>
</html>
