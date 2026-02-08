<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Student Central – Campus Marketplace</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background: #f9fafb;
      padding: 20px;
      color: #111827;
    }
    .container {
      max-width: 900px;
      margin: auto;
      background: #ffffff;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }
    h1, h2, h3 {
      color: #1f2937;
    }
    ul {
      margin-left: 20px;
    }
    code, pre {
      background: #f3f4f6;
      padding: 10px;
      border-radius: 5px;
      display: block;
      overflow-x: auto;
    }
    .copy-btn {
      background: #2563eb;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
      margin-bottom: 15px;
      font-size: 14px;
    }
    .copy-btn:hover {
      background: #1d4ed8;
    }
    footer {
      margin-top: 30px;
      font-size: 14px;
      color: #6b7280;
    }
  </style>
</head>
<body>

  <button class="copy-btn" onclick="copyReadme()">📋 Copy README</button>

  <div class="container" id="readme-content">
    <header>
      <h1>🎓 Student Central – Campus Marketplace</h1>
      <p>
        <strong>Student Central</strong> is a college-exclusive online marketplace
        that allows students to buy and sell <strong>used items within the same college</strong>,
        similar to OLX but restricted to a trusted campus community.
      </p>
    </header>

    <section>
      <h2>🚀 Features</h2>
      <ul>
        <li>🛒 Buy & sell used items (books, electronics, hostel essentials, etc.)</li>
        <li>🏫 Access restricted to students of the same college</li>
        <li>🔍 Category-based item listings</li>
        <li>💬 Direct student-to-student communication</li>
        <li>🧑‍🎓 Simple and student-friendly UI</li>
        <li>🔐 Safer transactions within campus</li>
      </ul>
    </section>

    <section>
      <h2>🛠️ Tech Stack</h2>
      <ul>
        <li><strong>Frontend:</strong> HTML, CSS, JavaScript / React</li>
        <li><strong>Backend:</strong> Node.js, Express.js</li>
        <li><strong>Database:</strong> MongoDB</li>
        <li><strong>Authentication:</strong> College email-based login</li>
        <li><strong>Version Control:</strong> Git & GitHub</li>
      </ul>
    </section>

    <section>
      <h2>📂 Project Structure</h2>
      <pre>
Student-Central/
│── client/
│── server/
│── models/
│── routes/
│── controllers/
│── public/
│── package.json
│── README.md
      </pre>
    </section>

    <section>
      <h2>⚙️ Installation & Setup</h2>
      <pre>
git clone https://github.com/your-username/student-central.git
cd student-central
npm install
npm start
      </pre>
    </section>

    <section>
      <h2>🎯 Project Objective</h2>
      <p>
        To create a <strong>secure and affordable campus marketplace</strong> where students
        can sell unused items and purchase second-hand products from fellow students,
        promoting reuse, sustainability, and convenience within the college community.
      </p>
    </section>

    <section>
      <h2>📌 Future Enhancements</h2>
      <ul>
        <li>College email verification</li>
        <li>In-app payments</li>
        <li>Seller ratings & reviews</li>
        <li>Real-time chat & notifications</li>
        <li>Mobile-first responsive design</li>
      </ul>
    </section>

    <section>
      <h2>🤝 Contribution</h2>
      <p>
        Contributions are welcome. Fork the repository and submit a pull request
        to improve the project.
      </p>
    </section>

    <section>
      <h2>📄 License</h2>
      <p>This project is licensed under the <strong>MIT License</strong>.</p>
    </section>

    <footer>
      <p>Made for students, by students 🎓</p>
    </footer>
  </div>

  <script>
    function copyReadme() {
      const text = document.getElementById("readme-content").innerText;
      navigator.clipboard.writeText(text).then(() => {
        alert("README copied to clipboard!");
      });
    }
  </script>

</body>
</html>
