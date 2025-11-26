# Bakri<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Your Jobs Portal</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f9f9f9; }
    header { background:#004080; color:#fff; padding:10px 20px; display:flex; align-items:center; justify-content: space-between; }
    header .logo { font-size: 24px; font-weight: bold; }
    header nav a { color: white; margin-right:15px; text-decoration:none; }
    .container { width: 90%; max-width: 1000px; margin: 20px auto; }
    .filter-bar { background: #fff; padding: 15px; border-radius: 5px; margin-bottom: 20px; }
    .filter-bar input, .filter-bar select { padding: 8px; margin-right: 10px; }
    .jobs-list { display: flex; flex-direction: column; gap: 15px; }
    .job-card { background: #fff; padding: 15px; border-radius: 5px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .job-card h3 { margin: 0 0 5px 0; }
    .job-card .meta { color: #555; font-size: 14px; }
    footer { background: #004080; color: #fff; text-align:center; padding:20px; margin-top: 40px; }
  </style>
</head>
<body>
  <header>
    <div class="logo">My Jobs Portal</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Jobs</a>
      <a href="#">Post a Job</a>
      <a href="#">Contact</a>
      <a href="#">Login</a>
      <a href="#">Register</a>
    </nav>
  </header>

  <div class="container">
    <div class="filter-bar">
      <input type="text" placeholder="Location">
      <select>
        <option>Any Job Type</option>
        <option>Full Time</option>
        <option>Part Time</option>
        <option>Contract</option>
      </select>
      <select>
        <option>Any Category</option>
        <option>IT</option>
        <option>Healthcare</option>
        <option>Engineering</option>
        <option>Other</option>
      </select>
      <button>Filter</button>
    </div>

    <div class="jobs-list">
      <div class="job-card">
        <h3>Factory Worker – Poland</h3>
        <div class="meta">Tomasz Rapid-Trans | Warsaw, Poland | Full Time | new</div>
      </div>
      <div class="job-card">
        <h3>Hotel Cleaner – UAE</h3>
        <div class="meta">Global Processing LLC | Ras Al Khaimah, UAE | Permanent</div>
      </div>
      <!-- more job-cards here -->
    </div>

    <div style="text-align:center; margin: 20px 0;">
      <button>Show More Jobs</button>
    </div>
  </div>

  <footer>
    <p>© 2025 My Jobs Portal | All Rights Reserved</p>
    <p>Contact: email@example.com</p>
  </footer>
</body>
</html>
