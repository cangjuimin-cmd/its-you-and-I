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
    <!-- embedded image -->
    <img class="image" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAZAAAAGQCAIAAAB3V3BaAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH5QgPFiEaH2P5CgAABZlJREFUeF7tnQm4JGX5hv89uvbbbyPbe737rr6mm3Z1uXdtDu7sXdqu90u3Vdm5GQpd2SlS02iWogvPZgQQIjAAIFrb9efWcIn/AiD94FQaBIGEBiGECCCEJxAIQYhAgghCcQCEGIQIIIRCEYhkQcA7f++Nzd3Tuw3l9Z2aP3+l7u7su7VzSWwHWFNfPxcVZxa8u3YwIgGUEIACIIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQuBmAYgQQCICHADKAxAQgIgiA4gQVwLkFYmU+F6BrC/gPq3H33e/R7H5kxmt3g3/7vVEAA4AXIqAEQCAEIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADiABCV7Uu/Nz3Y9st/t/6damHDp5723be+cQ+zrL9v7bX4kUzT3e/N786GyPtInv+vzQemZp7lZqAcIuP5f8akV+4H8P7nOAcAQCoCQEQCAEIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADIh/A/4F1Z8Bkb8d23agE+bae38eL/r25+wCApAMgQQCICHADKAxAQgIgiA4gQAgCIJAEgIQmBADiABAjkx6+mQAAAIABJREFUZgDIRgMAAAAAAACAw4cCGigfQ3+NPjI7fxxl4L7/XtBoA4AQCoCQEQCAEIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADiAhwIgiA4gQQCICHADKAxAQgIgiA4gQAgCIJAEgIQmBADiABAV/Cg97I+3o/G6/vf8BYnMAIB2ALoV4P0L6vHokAAABgAQCoCQEQCAEIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADiARCKgeAL+D8KcB/8PhG+vP5vvz3+wCgFAAgBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQuDAAgBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADiABwsQAgBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQuC/DPz/Pf6sAAAAgL8EIBEIBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQuDCCEBiBBAIgkAYSCEJgQAIgiA4gQAgCIJAEgIQmBADIhoPx/X9FeXf9dl/3JpAMJgQAIgiA4gQAgCIJAEgIQmBADiABAhC4tF+dgAAAP//AwBXHXpjN9hiQwAAAABJRU5ErkJggg==">

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
