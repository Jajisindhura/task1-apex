#task 1 of apex
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Welcome to Web Development</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f0f0;
      color: #333;
      text-align: center;
      padding: 20px;
    }

    h1 {
      color: #0077cc;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    img {
      width: 90%;
      max-width: 800px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      margin-bottom: 20px;
    }

    a {
      color: #0077cc;
      text-decoration: none;
    }

    button {
      padding: 10px 20px;
      background-color: #0077cc;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #005fa3;
    }
  </style>
</head>
<body>

  <h1>Welcome to Web Development</h1>
  <p>This simple page includes HTML structure, CSS styling, and a JavaScript interaction.</p>

  <!-- ✅ Real image (can be changed to anything) -->
  <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=1200&q=80" alt="Welcome Image" />
  
  <button onclick="showMessage()">Click Me!</button>

  <script>
    function showMessage() {
      alert("Hello! You've clicked the button. 🎉");
    }
  </script>

</body>
</html>

