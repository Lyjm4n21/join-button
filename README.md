# join-button
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>
  <button class="sub-button">SUBSCRIBE</button>
  <button class="join-button">JOIN</button>
  <button class="tweet-button">Tweet</button>
</body>
</html>

CSS

.sub-button {
  background-color: rgb(227, 37, 16);
  color: white;
  border: none;
  height: 30px;
  width: 100px;
  margin-right: 8px;
  border-radius: 2px;
  cursor: pointer;
  transition: opacity 0.15s;
}
.sub-button:hover {
  opacity: 0.7;
}
.sub-button:active {
  opacity: 0.5;
}
.join-button {
  color: rgb(48, 138, 255);
  height: 30px;
  width: 53px;
  border-width: 1px;
  border-color: rgb(48, 138, 255);
  cursor: pointer;
  margin-right: 8px;
  border-radius: 2px;
  transition: background-color 1s, color 1s;
}
.join-button:hover {
  background-color: rgb(48, 138, 255);
  color: white;
}
.join-button:active {
  opacity: 0.7;
}
.tweet-button {
  background-color: rgb(48, 138, 255);
  color: white;
  border: none;
  height: 30px;
  width: 68px;
  border-radius: 30px;
  cursor: pointer;
  transition: box-shadow .15s;
}
.tweet-button:hover {
  box-shadow: 5px 5px 10px rgb(0, 0, 0, .15);
}
