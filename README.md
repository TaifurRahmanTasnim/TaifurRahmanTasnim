<!DOCTYPE html>
<html>
<head>
<title>Toggle Button</title>
</head>
<body>

<button id="toggleButton" onclick="toggleVisibility()">Toggle Visibility</button>
<p id="content" style="display: none;">This is some hidden content.</p>

<script>
function toggleVisibility() {
  var content = document.getElementById("content");
  if (content.style.display === "none") {
    content.style.display = "block";
  } else {
    content.style.display = "none";
  }
}
</script>

</body>
</html>