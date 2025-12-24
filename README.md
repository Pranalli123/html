html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Management System</title>
  <link rel="stylesheet" href="style1.css">
</head>
<body>

  <h1>Student Management System</h1>

  <!-- Form -->
  <input type="text" id="name" placeholder="Student Name">
  <input type="number" id="age" placeholder="Age">
  <button onclick="addStudent()">Add Student</button>

  <!-- Table -->
  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Action</th>
      </tr>
    </thead>
    <tbody id="studentList"></tbody>
  </table>

  <script src="script.js"></script>
</body>
</html>
