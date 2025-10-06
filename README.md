<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Smart Notes Hub by Raj</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #eef2f8;
      color: #222;
      line-height: 1.6;
    }

    /* HEADER */
    header {
      background: linear-gradient(135deg, #2563eb, #1d4ed8);
      color: white;
      text-align: center;
      padding: 60px 20px;
      border-bottom-left-radius: 60px;
      border-bottom-right-radius: 60px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 40px;
      font-weight: 700;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      opacity: 0.95;
    }

    /* MAIN CONTENT */
    .content {
      max-width: 900px;
      margin: 60px auto;
      background: white;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }

    h2 {
      text-align: center;
      color: #2563eb;
      font-size: 30px;
      margin-bottom: 20px;
    }

    p {
      font-size: 17px;
      text-align: center;
      color: #333;
      margin-bottom: 20px;
    }

    /* FEATURES */
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .card {
      background: #f9fafb;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.08);
      text-align: center;
      transition: all 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      background: #eef3ff;
    }

    .card h3 {
      color: #1d4ed8;
      margin-bottom: 10px;
    }

    .contact {
      text-align: center;
      margin-top: 50px;
    }

    .contact p {
      font-size: 18px;
      color: #333;
    }

    .email {
      color: #2563eb;
      font-weight: bold;
    }

    /* FOOTER */
    footer {
      background: #2563eb;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 70px;
      border-top-left-radius: 60px;
      border-top-right-radius: 60px;
      font-size: 15px;
    }

    footer a {
      color: #fff;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <h1>Smart Notes Hub by Raj</h1>
    <p>Your Study Partner for Smarter Learning</p>
  </header>

  <section class="content">
    <h2>Welcome to Smart Notes Hub</h2>
    <p>Make your studies easier and smarter! Access quality NCERT notes, topic summaries, and practice questions — all designed to help you succeed.</p>

    <div class="features">
      <div class="card">
        <h3>📘 NCERT Notes</h3>
        <p>Organized chapter-wise notes for faster revision.</p>
      </div>

      <div class="card">
        <h3>🧠 Concept Boost</h3>
        <p>Understand every topic deeply with clear explanations.</p>
      </div>

      <div class="card">
        <h3>📝 Practice Questions</h3>
        <p>Check your preparation with important Q&A sets.</p>
      </div>

      <div class="card">
        <h3>🎯 Exam Ready</h3>
        <p>Be fully prepared with expert-curated study resources.</p>
      </div>
    </div>

    <div class="contact">
      <p>📧 Contact us at: <span class="email">smartnoteshub3@gmail.com</span></p>
    </div>
  </section>

  <footer>
    <p>© 2025 Smart Notes Hub by Raj | Designed for Learners</p>
  </footer>
</body>
</html>