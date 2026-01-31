<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>موقعي الشخصي</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .card {
      background: rgba(255, 255, 255, 0.1);
      padding: 40px;
      border-radius: 20px;
      width: 90%;
      max-width: 400px;
      backdrop-filter: blur(10px);
    }

    h1 {
      margin-bottom: 10px;
    }

    p {
      opacity: 0.9;
    }

    button {
      margin-top: 20px;
      padding: 10px 20px;
      border: none;
      border-radius: 25px;
      background: #00c6ff;
      color: black;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #00aaff;
    }
  </style>
</head>

<body>
  <div class="card">
    <h1>أهلاً 👋</h1>
    <p>هذا أول موقع لي على GitHub Pages</p>
    <button onclick="alert('شكراً لزيارتك ❤️')">اضغطني</button>
  </div>
</body>
