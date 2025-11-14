<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background: #f0f8ff;
    }

    h1 {
      font-size: 2.5rem;
      color: #ff69b4; /* لون العنوان */
    }

    .wave-hand {
      display: inline-block;
      font-size: 3rem;
      animation: wave 1s infinite; /* الحركة المستمرة */
      transform-origin: 70% 70%; /* محور الحركة */
    }

    @keyframes wave {
      0% { transform: rotate(0deg); }
      15% { transform: rotate(15deg); }
      30% { transform: rotate(-10deg); }
      45% { transform: rotate(15deg); }
      60% { transform: rotate(-10deg); }
      75% { transform: rotate(15deg); }
      100% { transform: rotate(0deg); }
    }
  </style>
</head>
<body>
  <h1>Hi, I'm Suzan Jaber <span class="wave-hand">👋</span></h1>
</body>
</html>
