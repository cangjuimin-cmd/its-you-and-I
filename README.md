<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>You & I</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #ffd6e0, #fff1f5);
      font-family: 'Segoe UI', Arial, sans-serif;
    }
    .card {
      background: white;
      padding: 28px;
      border-radius: 18px;
      text-align: center;
      max-width: 320px;
      box-shadow: 0 12px 25px rgba(0,0,0,0.15);
    }
    h2 {
      color: #ff4d6d;
      margin-bottom: 10px;
    }
    p {
      color: #444;
      font-size: 15px;
      line-height: 1.6;
    }
    button {
      margin-top: 18px;
      padding: 10px 20px;
      border: none;
      border-radius: 25px;
      background: #ff4d6d;
      color: white;
      font-size: 14px;
      cursor: pointer;
    }
    button:hover {
      opacity: 0.9;
    }
    #hidden {
      display: none;
      margin-top: 16px;
      color: #333;
      font-weight: 500;
    }
    .image {
      width: 100%;
      border-radius: 15px;
      margin-bottom: 15px;
      animation: fadeIn 1.2s ease-in;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="card">
    <!-- IMAGE EMBEDDED AS BASE64 -->
    <img class="image" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAoAAAAHgCAYAAAAvu1i9AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH5QgPFiEMcmILogAAABl0RVh0Q29tbWVudABDcmVhdGVkIHdpdGggR0lNUFeBDhcAAABlSURBVHja7cEBDQAAAMKg909tDjegAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADwCe0AAWdxHeUAAAAASUVORK5CYII=" alt="You & I affectionate image" class="image">

    <h2>You & I 🌸</h2>
    <p>
      This isn’t a big speech.<br>
      Just something honest.
    </p>

    <button onclick="showMessage()">Tap gently 💗</button>

    <div id="hidden">
      <p>
        I enjoy talking to you.<br>
        I like the way we connect.<br><br>
        Whatever this becomes,<br>
        I’m glad it’s <em>you & I</em> 🤍
      </p>
    </div>
  </div>

  <script>
    function showMessage() {
      document.getElementById("hidden").style.display = "block";
    }
  </script>

</body>
</html>
