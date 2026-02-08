# alchemist-website<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Alchemist | Complete Educational Website</title>
  <meta name="description" content="Complete educational website on The Alchemist by Paulo Coelho for school and college students with quizzes, bilingual content, notes, and activities." />  <!-- Google Font -->  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">  <style>
    :root {
      --primary: #5a3e0c;
      --secondary: #d4af37;
      --light: #faf7f2;
      --dark: #2b2b2b;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: var(--light);
      color: var(--dark);
      line-height: 1.7;
    }

    header {
      background: linear-gradient(to right, var(--primary), var(--secondary));
      padding: 15px 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    nav h1 {
      color: white;
      font-size: 24px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    nav ul li a:hover { text-decoration: underline; }

    .hero {
      padding: 90px 20px;
      text-align: center;
      background: url('https://images.unsplash.com/photo-1509021436665-8f07dbf5bf1d') center/cover no-repeat;
      color: white;
    }

    .hero h2 { font-size: 44px; margin-bottom: 20px; }
    .hero p { max-width: 800px; margin: auto; font-size: 18px; }

    section {
      padding: 60px 40px;
      max-width: 1200px;
      margin: auto;
    }

    section h2 {
      color: var(--primary);
      margin-bottom: 20px;
      font-size: 32px;
    }

    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    }

    .card h3 { color: var(--secondary); margin-bottom: 10px; }

    .quote {
      background: var(--primary);
      color: white;
      padding: 30px;
      border-radius: 12px;
      margin-top: 30px;
      font-style: italic;
    }

    .bilingual {
      background: #fff;
      border-left: 5px solid var(--secondary);
      padding: 20px;
      margin-top: 20px;
    }

    .quiz {
      background: #fff;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.1);
    }

    button {
      padding: 10px 20px;
      background: var(--primary);
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      margin-top: 15px;
    }

    button:hover { background: var(--secondary); color: #000; }

    footer {
      background: var(--dark);
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media(max-width:768px){
      .hero h2 { font-size: 32px; }
    }
  </style></head>
<body><header>
  <nav>
    <h1>The Alchemist</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#summary">Summary</a></li>
      <li><a href="#themes">Themes</a></li>
      <li><a href="#characters">Characters</a></li>
      <li><a href="#school">School</a></li>
      <li><a href="#college">College</a></li>
      <li><a href="#quiz">Quiz</a></li>
    </ul>
  </nav>
</header><div class="hero">
  <h2>The Alchemist – Complete Learning Platform</h2>
  <p>Designed for both School and College students with summaries, analysis, activities, quizzes, and bilingual explanations.</p>
</div><section id="about">
  <h2>About the Novel</h2>
  <p><strong>The Alchemist</strong> by Paulo Coelho is a philosophical novel about dreams, destiny, and self‑discovery.</p>
  <div class="bilingual">
    <p><strong>Urdu:</strong> الکیمسٹ ایک فلسفیانہ ناول ہے جو خوابوں، تقدیر اور خود شناسی کے بارے میں ہے۔</p>
  </div>
</section><section id="summary">
  <h2>Detailed Summary</h2>
  <p>Santiago, a shepherd boy, dreams of treasure near the pyramids of Egypt. He leaves Spain, meets mentors, faces hardships, and learns the true meaning of success.</p>
  <div class="quote">"When you want something, all the universe conspires in helping you to achieve it."</div>
</section><section id="themes">
  <h2>Themes & Analysis</h2>
  <div class="card-container">
    <div class="card"><h3>Personal Legend</h3><p>Every individual has a unique purpose in life.</p></div>
    <div class="card"><h3>Dreams</h3><p>Dreams guide humans toward fulfillment.</p></div>
    <div class="card"><h3>Faith & Destiny</h3><p>Belief plays a key role in achieving goals.</p></div>
  </div>
</section><section id="characters">
  <h2>Characters</h2>
  <div class="card-container">
    <div class="card"><h3>Santiago</h3><p>The protagonist seeking his destiny.</p></div>
    <div class="card"><h3>Melchizedek</h3><p>Symbol of wisdom and guidance.</p></div>
    <div class="card"><h3>The Alchemist</h3><p>Teacher of spiritual truths.</p></div>
  </div>
</section><section id="school">
  <h2>School Level Notes & Activities (Detailed)</h2>
  <p><strong>Easy Summary:</strong> The story teaches students to believe in dreams. Santiago learns that hard work, patience, and faith help achieve success.</p>
  <p><strong>Moral Lessons:</strong></p>
  <ul>
    <li>Never give up on your dreams</li>
    <li>Fear stops success</li>
    <li>Learning comes from experience</li>
    <li>True happiness comes from purpose</li>
  </ul>
  <p><strong>Short Questions:</strong></p>
  <ul>
    <li>Who is Santiago?</li>
    <li>What is a Personal Legend?</li>
    <li>Why does Santiago travel?</li>
  </ul>
  <p><strong>Activities:</strong></p>
  <ul>
    <li>Write 5 sentences on your dream</li>
    <li>Draw a journey map of Santiago</li>
    <li>Class discussion on dreams</li>
  </ul>
</section><section id="college">
  <h2>College Level Critical Analysis (Detailed)</h2>
  <p><strong>Symbolism:</strong> The desert represents life challenges. Gold symbolizes wisdom. The journey reflects inner growth.</p>
  <p><strong>Philosophical Ideas:</strong></p>
  <ul>
    <li>Existential purpose</li>
    <li>Human connection with universe</li>
    <li>Spiritual self‑realization</li>
  </ul>
  <p><strong>Character Analysis:</strong></p>
  <ul>
    <li>Santiago – growth through experience</li>
    <li>The Alchemist – spiritual mentor</li>
    <li>Fatima – unconditional love</li>
  </ul>
  <p><strong>Exam‑Oriented Topics:</strong></p>
  <ul>
    <li>Theme of destiny</li>
    <li>Role of dreams</li>
    <li>Journey as metaphor</li>
  </ul>
</section><section id="quiz">
  <h2>Interactive Quiz (Detailed)</h2>
  <div class="quiz">
    <p><strong>Q1:</strong> What is Santiago's profession?</p>
    <button onclick="alert('Correct Answer: Shepherd')">Answer</button>
    <p><strong>Q2:</strong> What does Personal Legend mean?</p>
    <button onclick="alert('Correct Answer: One’s life purpose or destiny')">Answer</button>
    <p><strong>Q3:</strong> Where is the treasure located?</p>
    <button onclick="alert('Correct Answer: Near the pyramids / symbolic self‑realization')">Answer</button>
  </div>
</section><footer>
  <p>© Educational Website on The Alchemist | For Schools & Colleges</p>
</footer></body>
</html>
