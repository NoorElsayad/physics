
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Electromagnetic Induction</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #e3f2fd);
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #00acc1;
      color: white;
      padding: 30px 20px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    }

    nav {
      background-color: #0288d1;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      background-color: white;
      margin: 30px auto;
      padding: 20px 30px;
      border-radius: 15px;
      width: 90%;
      max-width: 800px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #1976d2;
      margin-top: 0;
    }

    a {
      color: #0288d1;
      font-weight: bold;
    }

    a:hover {
      color: #01579b;
      text-decoration: underline;
    }

    .equation {
      font-weight: bold;
      background-color: #e3f2fd;
      padding: 10px;
      border-radius: 8px;
      display: inline-block;
    }

    .resources a {
      display: block;
      margin-bottom: 10px;
      background: #f1f8e9;
      padding: 10px 15px;
      border-radius: 8px;
      border-left: 5px solid #8bc34a;
    }

    .resources a:hover {
      background-color: #dcedc8;
    }

    .rating label {
      font-size: 2rem;
      color: #ccc;
      cursor: pointer;
      transition: color 0.2s;
    }

    .rating input:checked ~ label {
      color: #ffca28;
    }

    footer {
      text-align: center;
      font-size: 0.9em;
      margin: 40px 0 20px;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>🔁 Electromagnetic Induction</h1>
    <p>Understanding how changing magnetic fields create electricity</p>

  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#explanation">Explanation</a>
    <a href="#phet">PhET Simulation</a>
    <a href="#quizzes">Quizzes</a>
    <a href="#review">Evaluation</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
  <h2>Welcome!</h2>
  <p>This site is your guide to understanding Electromagnetic Induction — a key concept in physics used in generators, microphones, and more!</p>

  <h3>🎯 Learning Outcomes</h3>
  <ul style="line-height: 1.8; padding-left: 20px;">
    <li>Define electromagnetic induction and explain how it works.</li>
    <li>Describe Faraday’s and Oersted’s discoveries.</li>
    <li>Use the right-hand rule to determine current direction.</li>
    <li>Apply the EMF formula to basic situations.</li>
    <li>Identify real-life applications of electromagnetic induction.</li>
    <li>Explore the concept interactively using a PhET simulation.</li>
    <li>Answer MOE-style questions with confidence.</li>
  </ul>
</section>


  <!-- Explanation Section -->
  <section id="explanation">
    <h2>What is Electromagnetic Induction?</h2>
    <p>Electromagnetic induction is the process of generating electric current from a changing magnetic field.</p>
    <p>Discovered by Michael Faraday in 1831, it's used in electric generators and transformers.</p>
    <a href="https://content.alefed.com/data/ccl/content/33/c2/b9/e7/122983/source/LVF3V5LP27UIU7FQM2LCAVDKRVA/Explore_slide_04.gif" target="_blank">➤ View Faraday's Law Diagram</a>

   <section>
    <h2>Oersted's Experiment 🧲</h2>
    <p>
      In 1820, Hans Christian Oersted discovered that an electric current in a wire creates a magnetic field around it. 
      This showed that <strong>electricity can create magnetism</strong>.
    </p>
    <p>
      But later, Faraday and others found the <strong>opposite is also true</strong>: a changing magnetic field can create electricity! 
      This is what electromagnetic induction is all about — the two phenomena are connected.
    </p>
    <a href="https://content.alefed.com/data/ccl/content/fa/2f/5b/29/121174/source/LKXM63PO3MRUELKE5FF44LYERFE_LKOBX5A7NW3AE7KETR2L5KYPSPY/PH10_MLO_343_IMG_034.jpg" target="_blank">
      ➤ Click here to view Oersted's Experiment Picture
    </a>
  </section>

  <section>
    <h2>What is EMF?</h2>
    <p>
      EMF stands for <strong>Electromotive Force</strong>, but it doesn’t mean a real "force" — it’s actually a voltage.
      So, EMF is very similar to potential difference (<strong>V</strong>). It tells us how much electrical energy is being pushed through a circuit.
    </p>
    <div class="equation">
      EMF = B × L × V × sin(θ)
    </div>
    <p>
      Where:<br>
      B = magnetic field strength (Tesla)<br>
      L = length of the wire in the magnetic field (meters)<br>
      V = velocity (speed of the wire)<br>
      θ = angle between the wire and the field lines
    </p>
  </section>

  <section>
    <h2>Right-Hand Rule ✋</h2>
    <p>
      To find the direction of the induced current, use the <strong>right-hand rule</strong> for generators:
    </p>
    <p>
      ➤ Point your thumb in the direction of the wire's motion (velocity).<br>
      ➤ Point your fingers in the direction of the magnetic field.<br>
      ➤ Your palm will face the direction of the induced current (conventional current).
    </p>
    <a href="https://content.alefed.com/data/ccl/content/f4/6e/f8/1f/123000/source/LGEWQUPCE5NMUBBKY73JBNSSU3Q_LIMEUYWBGXS4EJBUF2YTGBTVWLA/PH10_MLO_345_IMG_015a.jpg" target="_blank">
      ➤ Click here to view Right-Hand Rule Picture
    </a>
  </section>

  <section>
    <h2>Real-Life Application: Microphones 🎤</h2>
    <p>
      Microphones work based on the principle of electromagnetic induction. In a typical microphone, there is a diaphragm that vibrates in response to sound waves. 
      Attached to this diaphragm is a coil of wire that moves within a magnetic field. As the coil moves, it cuts through the magnetic lines of force, inducing an electric current.
      This current is then sent to an amplifier, which converts the vibrations into an audio signal. This is how sound is transformed into an electrical signal in microphones.
    </p>
  </section>

  <section>
   <!-- Video Section -->
<section id="video">
  <h2>🎥 Watch Explainer Video</h2>
  <p>Click below to watch a short video that explains electromagnetic induction in an easy-to-understand way.</p>

  <div class="resources">
    <a href="https://www.youtube.com/watch?v=2tMRPuU78GA" target="_blank">
      ▶️ Electromagnetic Induction – YouTube Video
    </a>
  </div>
</section>


  </section>

  </section>

  <!-- PhET Simulation Section -->
 <!-- PhET Simulation Section -->
<section id="phet">
  <h2>Try the PhET Simulation 🔬</h2>
  <p>Explore how moving a magnet through a coil induces electricity using this interactive simulation.</p>
  <iframe src="https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law_all.html" 
          width="100%" height="500" 
          allowfullscreen 
          style="border: none; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1);">
  </iframe>
  <p>If the simulation doesn't load, you can also open it directly:</p>
  <a href="https://phet.colorado.edu/sims/html/faradays-law/latest/faradays-law_all.html" target="_blank">
    🔗 Open Faraday’s Law Simulation in New Tab
  </a>
</section>


  <!-- Quizzes Section -->
  <section id="quizzes" class="resources">
    <h2>Test Your Knowledge 🧠</h2>
    <a href="https://wordwall.net/resource/14170927" target="_blank">🎮 WordWall Quiz</a>
    <a href="https://www.liveworksheets.com/w/en/science/7519959" target="_blank">📄 Live Worksheet</a>
    <a href="https://quizizz.com/admin/quiz/5b4de474cb768d0019882824/electromagnetic-induction?source=quiz_share" target="_blank">❓ Quizizz</a>
    <a href="https://lmsprodesestorage.blob.core.windows.net/module-storage-course/1576946/6e08c228-5e74-42dc-b8d6-0adb927b2f22/W1_Module%2021_%20L1_%20Inducing%20currents.pptx?sv=2019-07-07&sr=c&sig=EMQa5ckoDAUrpChtElW5firtCeJuVW7AU1u7mi0JLOQ%3D&st=2025-05-04T12%3A08%3A32Z&se=2025-05-06T12%3A08%3A32Z&sp=r" target="_blank">📥 Download Lesson Slides</a>
  </section>
  <!-- MOE Final Exam Questions Section -->
<section id="moe-exams">
  <h2>📘 MOE Final Exam Questions</h2>
  <p>Practice with official questions from Ministry of Education (MOE) final exams. These will help you prepare for what to expect in your real tests.</p>

  <div class="resources">
    <a href="https://drive.google.com/file/d/1_rwajI6qc9ZPxJJ18da0jJGD_EshvSYK/view?usp=sharing" target="_blank">📝 Final Exam Questions – Physics Grade 10</a>
    <a href="https://drive.google.com/file/d/1IoSnaObgc90vdNqyEOGPYFQzsJop88bX/view?usp=sharing" target="_blank">📄 Applications of induced currents  – Past Paper</a>
    <a href="https://drive.google.com/file/d/1ikKVervzbG6LHxlZAjeKZx-Ivh1QS0de/view?usp=sharing" target="_blank">🔍 Inducing currents: Solve Like an MOE Exam</a>
  </div>

  <p>More questions coming soon!</p>
</section>



<!-- Evaluation / Review Section -->
<section id="review">
  <h2>🌟 Website Evaluation</h2>
  <p>How would you rate this website?</p>

  <form id="evaluationForm" onsubmit="return submitFeedback()">
    <div class="rating" style="display: flex; flex-direction: row-reverse; justify-content: start;">
      <input type="radio" id="star5" name="rating" value="5" required><label for="star5" title="5 stars">★</label>
      <input type="radio" id="star4" name="rating" value="4"><label for="star4" title="4 stars">★</label>
      <input type="radio" id="star3" name="rating" value="3"><label for="star3" title="3 stars">★</label>
      <input type="radio" id="star2" name="rating" value="2"><label for="star2" title="2 stars">★</label>
      <input type="radio" id="star1" name="rating" value="1"><label for="star1" title="1 star">★</label>
    </div>

 <p>We would love your feedback! Please click the button below to rate this website and share your thoughts.</p>

  <div class="resources">
    <a href="https://tdiqlpbf.formester.com/f/C8s8vSn4u" target="_blank">
      ✍️ Submit Your Feedback Form
    </a>
  </div>
  </form>
</section>
done by: Noor Amgad
