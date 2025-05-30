<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Pay with bKash</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 500px;
      margin: 40px auto;
      text-align: center;
    }
    img {
      width: 200px;
      margin: 20px 0;
    }
    input, button {
      padding: 10px;
      margin: 10px 0;
      width: 80%;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <h2>Pay with bKash</h2>
  <p>Scan the QR code below to complete your payment.</p>

  <!-- Replace this with your actual QR code image -->
  <img src="https://chart.googleapis.com/chart?cht=qr&chs=300x300&chl=01891669706" alt="bKash QR Code">

  <p>After you send the money, enter your Transaction ID below:</p>

  <form action="confirm.php" method="post">
    <input type="text" name="trxid" placeholder="Enter Transaction ID" required><br>
    <button type="submit">Confirm Payment</button>
  </form>

</body>
</html>
