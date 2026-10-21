<!DOCTYPE html>
<html>
<head>
  <title>LIGER WORLD APP</title>
  <style>
    /* This is for design - black and white like GHOST */
    body {
      background: black;
      color: white;
      text-align: center;
      font-family: Arial;
      padding-top: 50px;
    }
    .box {
      background: white;
      color: black;
      width: 300px;
      margin: auto;
      padding: 20px;
      border-radius: 15px;
    }
    button {
      width: 100%;
      padding: 12px;
      margin-top: 10px;
      border: none;
      border-radius: 8px;
      font-weight: bold;
    }
    .btn-black { background: black; color: white; }
    .btn-white { background: #eee; color: black; }
  </style>
</head>
<body>

  <h1>LIGER WORLD APP</h1>
  <p>ONE BIG TOOLBOX. ALL APPS INSIDE.</p>

  <div class="box">
    <h2>Welcome</h2>
    <p>This is your first time here</p>
    
    <!-- These are your icons from poster -->
    <p>Facebook | WhatsApp | TikTok | AI | Market | Movie</p>

    <button class="btn-black" onclick="createAccount()">Create Account</button>
    <button class="btn-white" onclick="login()">Login</button>
  </div>

  <script>
    // This is the CODE part - meaning of code

    // 1. REMEMBER - remember that user opened app first time
    let firstTime = true;

    // 2. CHECK - check if first time
    if (firstTime) {
      console.log("Welcome new user!");
    }

    // 3. SHOW - what happens when they click
    function createAccount() {
      alert("Welcome to LIGER WORLD! Let's create your account");
    }

    function login() {
      alert("Welcome back! Login here");
    }
  </script>

</body>
</html>
