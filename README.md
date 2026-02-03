[index.html](https://github.com/user-attachments/files/25044355/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÂU HỎI VÊ BẠN SỰ 😎😎😎</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #f7f7f7;
      font-family: Arial, sans-serif;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      width: 280px;
    }

    .card img {
      width: 200px;
      border-radius: 12px;
    }

    h2 {
      margin: 15px 0;
      font-weight: normal;
    }

    .buttons {
      margin-top: 10px;
    }

    button {
      padding: 10px 20px;
      margin: 0 10px;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      font-size: 16px;
    }

    #yes {
      background: #ff4d6d;
      color: white;
    }

    #no {
      background: #ddd;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="https://i.imgur.com/8RKXAIV.png" alt="minions"/>
    <h2>SỰ, BẠN CÓ PHẢI NGƯỜI THÔNG MINH? </h2>
    <div class="buttons">
      <button id="yes">Yes</button>
      <button id="no">No</button>
    </div>
  </div>

  <script>
    const noBtn = document.getElementById('no');
    const yesBtn = document.getElementById('yes');

    noBtn.addEventListener('mouseover', () => {
      const x = Math.random() * 200 - 100;
      const y = Math.random() * 200 - 100;
      noBtn.style.transform = `translate(${x}px, ${y}px)`;
    });

    yesBtn.addEventListener('click', () => {
      alert('🤣🤣🤣🤣🤣🤣🤣🤣🤣')
    });
  </script>
</body>
</html>
