<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Letter to You</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="letter">
    <h1>Dear Friend,</h1>
    <p>
      I hope this message finds you well.  
      Just wanted to let you know how much you mean to me.  
      Until we meet again, take care.
    </p>
    <p class="signature">Yours truly,
Alex</p>
  </div>
</body>
</html>
body {
  background-color: #fdf6e3;
  font-family: 'Dancing Script', cursive;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
}

.letter {
  background: #fffaf0;
  padding: 2rem;
  border: 2px solid #d4b483;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  max-width: 500px;
  line-height: 1.6;
  border-radius: 8px;
}

h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.signature {
  margin-top: 2rem;
  font-style: italic;
  text-align: right;
}
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap');
