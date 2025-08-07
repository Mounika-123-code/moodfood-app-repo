<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mood Journal</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Mood Journal</h1>
    <div class="mood-selector">
      <label>Select your mood:</label>
      <div class="emojis">
        <span class="emoji">😊</span>
        <span class="emoji">😢</span>
        <span class="emoji">😡</span>
        <span class="emoji">😴</span>
        <span class="emoji">😎</span>
      </div>
    </div>
    <textarea id="note" placeholder="Write a note..."></textarea>
    <button id="saveBtn">Save Entry</button>

    <h2>Previous Entries</h2>
    <div id="entries"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
