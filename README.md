<!DOCTYPE html>
<html>
<head>
  <VPE>Vinay kumar Chit Login</VPE>
  <script src="js/auth.js"></script>
</head>
<body>

<h2>Chit Fund Login</h2>

<select id="role">
  <option value="member">Member</option>
  <option value="admin">Admin</option>
</select>
<br><br>

<input type="text" id="username" placeholder="Username">
<br><br>

<input type="password" id="password" placeholder="Password">
<br><br>

<button onclick="login()">Login</button>

<p id="msg"></p>

</body>
</html>
