<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Dashboard</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f8;

     
    }

    .navbar {
      background-color: black;
      color: white;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .dashboard {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
      display: grid;
      grid-template-columns: 1fr 2fr;
      gap: 30px;
    }

    .profile-card {
      background-color: white;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .profile-card img {
      border-radius: 50%;
      margin-bottom: 15px;
      width: 100px;
      height: 100px;
    }

    .summary-card, .recent-card {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }

    .summary {
      display: flex;
      justify-content: space-between;
      margin-top: 15px;
    }

    .box {
      background-color: white;
      padding: 15px;
      text-align: center;
      border-radius: 8px;
      flex: 1;
      margin: 5px;
    }

    .recent-card table {
      width: 100%;
      margin-top: 15px;
      border-collapse: collapse;
     
    }

    .recent-card th, .recent-card td {
      padding: 12px;
      border: 1px solid #ddd;
      text-align: center;
    }

    .recent-card th {
      background-color: black;
      color: white;
    }
.login{
background-image:url('https://assets.thehansindia.com/h-upload/feeds/2019/03/23/155967-srkr.jpg');
}
  </style>
</head>

<body>

  <nav class="navbar">
    <h2>Attendance Dashboard</h2>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Attendance</a></li>
      <li><a href="login-page.html">Login</a></li>
    </ul>
  </nav>

  <div class="dashboard">
    <!-- Student Profile -->
    <div class="profile-card">
      <img src="https://static.vecteezy.com/system/resources/thumbnails/005/427/608/small_2x/young-indian-student-holding-diary-file-in-hand-free-photo.JPG" alt="Student Photo">
      <h3>G Ganasathya</h3>
      <p>Regd No: 23B95A5412</p>
      <p>Aids: A</p>
    </div>

    <!-- Attendance Summary -->
    <div class="summary-card">
      <h3>Attendance Summary</h3>
      <div class="summary">
        <div class="box">
          <h4>Total Classes</h4>
          <p>50</p>
        </div>
        <div class="box">
          <h4>Present</h4>
          <p>45</p>
        </div>
        <div class="box">
          <h4>Absent</h4>
          <p>5</p>
        </div>
        <div class="box">
          <h4>Percentage</h4>
          <p>90%</p>
        </div>
      </div>
    </div>

    <!-- Recent Attendance -->
    <div class="recent-card">
      <h3>Recent Attendance</h3>
      <table>
        <tr>
          <th>Date</th>
          <th>Status</th>
        </tr>
        <tr>
          <td>20-Mar-2025</td>
          <td>Present</td>
        </tr>
        <tr>
          <td>19-Mar-2025</td>
          <td>Absent</td>
        </tr>
        <tr>
          <td>18-Mar-2025</td>
          <td>Present</td>
        </tr>
        <tr>
          <td>17-Mar-2025</td>
          <td>Present</td>
        </tr>
      </table>
    </div>

  </div>

</body>
</html>
