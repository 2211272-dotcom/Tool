<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JavaScript Demo</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      background: #0078ff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background: #005fcc;
    }

    #message {
      margin-top: 20px;
      font-size: 18px;
      color: green;
    }
  </style>
</head>
<body>

<div class="card">
  <h1>JavaScript Example</h1>
  <p>Click the button below.</p>

  <button id="btn">Click Me</button>

  <p id="message"></p>
</div>

<script>
  const button = document.getElementById("btn");
  const message = document.getElementById("message");

  button.addEventListener("click", () => {
    message.textContent = "🎉 Hello! JavaScript is working.";
  });
</script>

</body>
</html>
