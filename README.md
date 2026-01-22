<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Do You Love Me? ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- QUESTION -->
  <div class="question-container container" id="questionBox">
    <video class="local-gif" src="Reply me love.mp4" autoplay loop muted></video>
    <h2 class="question">Do you love me? 💕</h2>

    <div class="button-container">
      <button class="yes-btn btn" id="yesBtn">Yes 💖</button>
      <button class="no-btn btn" id="noBtn">No 💔</button>
    </div>
  </div>

  <!-- RESULT -->
  <div class="result-container container hidden" id="resultBox">
    <video class="gif-result" src="Love me.mp4" autoplay loop muted></video>
    <h2>I knew it! 😍</h2>

    <div class="cssload-main">
      <div class="cssload-heart">
        <span class="cssload-heartL"></span>
        <span class="cssload-heartR"></span>
        <span class="cssload-square"></span>
      </div>
      <div class="cssload-shadow"></div>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
