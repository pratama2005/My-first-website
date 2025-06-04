# My-first-website
<!DOCTYPE html>
<html>
<head>
  Website Keren Saya
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Halo Dunia!</h1>
  <p>Ini website pertama saya menggunakan Kodex.</p>

  <button onclick="greetUser()">Klik aku!</button>
  <p id="output"></p>

  <script src="script.js"></script>
</body>
</html>
body {
  background-color: #1e1e2f;
  color: #ffffff;
  font-family: Arial, sans-serif;
  text-align: center;
  margin-top: 50px;
}

button {
  padding: 10px 20px;
  font-size: 16px;
  background-color: #4caf50;
  border: none;
  color: white;
  cursor: pointer;
}
function greetUser() {
  document.getElementById("output").innerHTML = "Terima kasih sudah mengklik!";
}
