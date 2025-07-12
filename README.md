<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Register - Musabaka Derrick Learning Platform</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Register</h1>
    <form id="registerForm">
      <label for="surname">Surname:</label>
      <input type="text" id="surname" name="surname" required />

      <label for="firstname">First Name:</label>
      <input type="text" id="firstname" name="firstname" required />

      <label for="location">Location:</label>
      <input type="text" id="location" name="location" required />

      <label for="occupation">Occupation:</label>
      <select id="occupation" name="occupation" required>
        <option value="">--Select--</option>
        <option value="student">Student</option>
        <option value="pupil">Pupil</option>
        <option value="teacher">Teacher</option>
        <option value="custom">Custom</option>
      </select>

      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required />

      <label for="password">Password (min 4 chars):</label>
      <input type="password" id="password" name="password" minlength="4" required />

      <button type="submit">Register</button>
    </form>
    <p>Already registered? <a href="login.html">Login here</a>.</p>
  </div>

  <script src="script.js"></script>
</body>
</html>
