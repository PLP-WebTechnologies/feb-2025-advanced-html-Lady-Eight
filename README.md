<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Engineer Judith Mwangi - Registration Portal</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f0f8ff;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    header, footer {
      background: #00796b;
      color: white;
      text-align: center;
      padding: 15px 0;
      border-radius: 8px;
    }
    h1, h2 {
      color: #00695c;
    }
    section {
      margin-bottom: 30px;
      background: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    th {
      background-color: #e0f7fa;
    }
    input, select {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    input[type="submit"] {
      background-color: #00796b;
      color: white;
      border: none;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #004d40;
    }
    label {
      font-weight: bold;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }
    a {
      color: #b2dfdb;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Welcome to Judith W. Mwangi's Engineering Network</h1>
    <p>Empowering sustainable communities through innovative infrastructure solutions.</p>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Steps to Engage with My Engineering Projects</h2>
    <ol type="I">
      <li>Explore my background in structural and environmental engineering.</li>
      <li>Review project contributions and community impact work.</li>
      <li>Register to collaborate or receive updates.</li>
    </ol>
  </section>

  <!-- External Image -->
  <section>
    <h2>Fieldwork and Innovation</h2>
    <img src="https://drive.google.com/file/d/1Edg5_fosQCtLCnfbdX-2JXO1_aSLVwTE/view?usp=sharing" alt="Engineering at work">
  </section>

  <!-- Contact Table -->
  <section>
    <h2>Project Team Contacts</h2>
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Judith W. Mwangi</td>
          <td>Fadhili Estate, Nairobi</td>
          <td>+254700724917</td>
          <td>mwangij8dy@gmail.com</td>
        </tr>
        <tr>
          <td>Amina Ali</td>
          <td>789 Shanzu, Mombasa</td>
          <td>+254712345680</td>
          <td>amina@example.com</td>
        </tr>
        <tr>
          <td>Brian Otieno</td>
          <td>321 Moray, Eldoret</td>
          <td>+254712345681</td>
          <td>brian@example.com</td>
        </tr>
        <tr>
          <td>Susan Wanjiru</td>
          <td>654 Kiratina, Nakuru</td>
          <td>+254712345682</td>
          <td>susan@example.com</td>
        </tr>
        <tr>
          <td>Kevin Mwangi</td>
          <td>101 Banana Hill, Kiambu</td>
          <td>+254798765432</td>
          <td>kevin@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>
  <!-- Registration Form -->
  <section>
    <h2>Collaborator Registration Form</h2>
    <form action="#" method="post">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Your full name" required>
   <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" placeholder="example@domain.com" required>
 <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Create a password" minlength="6" required>
 <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required>
   <label for="interest">Area of Interest:</label>
      <select id="interest" name="interest" required>
        <option value="">--Please choose an option--</option>
        <option value="sustainability">Sustainable Engineering</option>
        <option value="transport">Green Transportation</option>
        <option value="waste">Waste Management</option>
      </select>
 <p>Preferred Collaboration Mode:</p>
      <input type="radio" id="online" name="mode" value="online" required>
      <label for="online">Online</label>
      <input type="radio" id="onsite" name="mode" value="onsite">
      <label for="onsite">On-site</label>
   <p>Skills You Bring:</p>
      <input type="checkbox" id="cad" name="skills" value="cad">
      <label for="cad">AutoCAD</label>
      <input type="checkbox" id="gis" name="skills" value="gis">
      <label for="gis">GIS</label>
      <input type="checkbox" id="policy" name="skills" value="policy">
      <label for="policy">Policy Research</label>
  <input type="submit" value="Join the Network">
    </form>
  </section>
  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Judith W. Mwangi | Graduate Engineer | LinkedIn: <a href="https://www.linkedin.com/in/jmwangi01" target="_blank">jmwangi01</a></p>
  </footer>

</body>
</html>

