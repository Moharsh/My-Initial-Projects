<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Wikipedia Style Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: whitesmoke;
      color: #333;
    }

    .heading {
      text-align: center;
      font-size: 30px;
      margin-top: 0px;
      background-color: aliceblue;
    }

    .container {
      display: flex;
      gap: 40px;
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .index-box {
      padding: 20px;
      border: 2px solid dimgray;
      border-radius: 20px;
      background-color: white;
      flex: 1;
    }

    .right-content {
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      text-align: center;
      flex: 1;
    }

    .references {
      padding: 50px;
      border: 1px solid grey;
      border-radius: 20px;
      background-color: whitesmoke;
      margin-top: 20px;
    }

    h2 {
      margin-top: 30px;
      font-size: 24px;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }

    p {
      margin-bottom: 15px;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      .index-box, .right-content {
        width: 100%;
      }
    }
    
    main {
      padding: 20px auto;
      max-width: 1200px;
      padding: 0 20px;
    }
    
    section {
      margin-bottom: 40px;
      padding: 20px;
      background-color: white;
      border-radius: 20px;
      box-shadow: 0 1px 1.5px 0.75px rgba(0, 0, 0, 1);
    }
    
    section h2{
      margin-top: 0;
      font-size: 2rem;
      box-shadow: #2c3e50;
    }
    
    section h3{
      font-size: 1.5rem;
      color: #34495e;
    }
    
    section ul{
      padding-left: 20px;
    }
    
    section ul li{
      margin: 10px 0;
    }
    
/* Style the back-to-top button */
    #BackToTop {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #2c3e50;
      color: white;
      text-decoration: none;
      padding: 10px 15px;
      border-radius: 5px;
      font-size: 16px;
     opacity: 0;
      transition: opacity 0.3s;
    }

/* Make it appear when scrolling */
    html:has(body:not(:hover)) #BackToTop {
  opacity: 1;
    }

/* Smooth scrolling */
    html {
  scroll-behavior: smooth;
    }
    
    .search-container {
      text-align: center;
      margin: 20px 0;
    }

    #searchInput {
      width: 50%;
      padding: 10px;
      font-size: 16px;
      border: 2px solid #2c3e50;
      border-radius: 50px;
      outline: black;
      background-color: #f9f9f9;
      color: #333;
    }

    #searchInput::placeholder {
     color: #888;
     font-style: italic;
    }
  </style>
</head>

<body>
  <header>
    <section class="heading">
      <h1>Wikipedia Style Page</h1>
    </section>
    <hr>
  </header>
  
  <div class="search-container">
  <label for="searchInput">Search:</label>
  <input type="text" id="searchInput" placeholder="Use Ctrl + F to search...">
  </div>

  <div class="container">
    <nav class="index-box">
      <h2>Index</h2>
      <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#early-concepts">Intelligence Early Concepts and Precursor</a></li>
        <li><a href="#birth-of-ai">The Birth of AI (1950s-1960s)</a></li>
        <li><a href="#ai-winter">The AI Winter (1970s-1980s)</a></li>
        <li><a href="#ai-renaissance">The AI Renaissance (1990s-2000s)</a></li>
        <li><a href="#modern-ai">Modern AI (2010s-present)</a></li>
        <li><a href="#types-of-ai">Types of AI</a></li>
        <li><a href="#applications">Applications of AI</a></li>
        <li><a href="#advantages">Advantages</a></li>
        <li><a href="#concerns">Concerns</a></li>
        <li><a href="#future">Future of AI</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
        <li><a href="#references">References</a></li>
      </ul>
    </nav>

    <aside class="right-content">
      <h3>Source</h3>
      <p>This whole website content is taken from ChatGPT.</p>
      <p>Big thanks to ChatGPT and DeepSeek for coding tips, design inspiration, and saving my sanity during this build!</p>
    </aside>
  </div>

  <main>
    <section id="introduction">
      <h2>Introduction</h2>
      <p>Artificial Intelligence (AI) is a branch of computer science that focuses on creating machines and software capable of performing tasks that typically require human intelligence. These tasks include learning, reasoning, problem-solving, perception, natural language processing, and decision-making. AI has evolved rapidly over the past few decades and now plays a significant role in various industries such as healthcare, finance, education, transportation, and entertainment.</p>
      <p>AI is broadly categorized into Narrow AI (Weak AI), which is designed to perform specific tasks, and General AI (Strong AI), which aims to replicate human-level intelligence. Researchers are also exploring Artificial Superintelligence (ASI), which would surpass human intelligence and capabilities.</p>
      <p>Despite its potential, AI presents several challenges, including ethical concerns, job displacement, bias in decision-making, and security risks. Governments, organizations, and researchers are actively working on frameworks to ensure the responsible development and use of AI.</p>
    </section>

    <section id="early-concepts">
      <h2>Intelligence Early Concepts and Precursor</h2>
      <p>The idea of creating artificial beings with intelligence dates back to ancient history. Mythological figures such as Talos (a mechanical giant from Greek mythology) and automata designed by inventors like Leonardo da Vinci in the Renaissance period showcase humanity’s early fascination with artificial intelligence.</p>
      <p>The foundation for AI was laid in the early 20th century with significant developments in logic, mathematics, and computing:</p>
      <ul>
        <li>1854 – George Boole introduced Boolean algebra, which later influenced digital logic.</li>
        <li>1936 – Alan Turing introduced the concept of a "universal machine," now known as the Turing Machine, which demonstrated the principles of modern computation.</li>
      </ul>
    </section>

    <section id="birth-of-ai">
      <h2>The Birth of AI (1950s-1960s)</h2>
      <ul>
        <li>1950 – Alan Turing published <em>Computing Machinery and Intelligence</em>, introducing the Turing Test to evaluate machine intelligence.</li>
        <li>1956 – The Dartmouth Conference, organized by John McCarthy, Marvin Minsky, Nathaniel Rochester, and Claude Shannon, officially introduced AI as a research field.</li>
        <li>1958 – John McCarthy developed the Lisp programming language, which became essential for AI research.</li>
      </ul>
      <p>Early AI systems were based on symbolic logic and expert systems, which relied on hand-crafted rules to solve problems. However, these systems struggled with real-world complexity due to their rigid structure.</p>
    </section>

    <section id="ai-winter">
      <h2>The AI Winter (1970s-1980s)</h2>
      <p>During this period, enthusiasm for AI declined due to funding cuts and failures in developing general intelligence. Many AI programs could not scale to solve real-world problems, leading to skepticism about AI’s feasibility.</p>
      <p>However, key developments included:</p>
      <ul>
        <li>1974 – The introduction of backpropagation in neural networks.</li>
        <li>1980s – The rise of expert systems, such as MYCIN (for medical diagnosis) and XCON (for configuring computer systems).</li>
      </ul>
    </section>

    <section id="ai-renaissance">
      <h2>The AI Renaissance (1990s-2000s)</h2>
      <p>Advancements in computing power, machine learning, and data-driven approaches led to an AI resurgence:</p>
      <ul>
        <li>1997 – IBM’s Deep Blue defeated world chess champion Garry Kasparov.</li>
        <li>2000s – AI-powered recommendation systems (Amazon, Netflix) emerged.</li>
      </ul>
    </section>

    <section id="modern-ai">
      <h2>Modern AI (2010s-present)</h2>
      <p>The modern era of AI is characterized by deep learning, big data, and breakthroughs in neural networks:</p>
      <ul>
        <li>2011 – IBM Watson won Jeopardy! using NLP and deep learning.</li>
        <li>2016 – Google DeepMind’s AlphaGo defeated Go champion Lee Sedol.</li>
        <li>2020s – AI is widely used in self-driving cars, healthcare diagnostics, and creative applications like text and image generation.</li>
      </ul>
    </section>

    <section id="types-of-ai">
      <h2>Types of AI</h2>
      <h3>Based on Capabilities</h3>
      <p><strong>Narrow AI (Weak AI)</strong></p>
      <ul>
        <li>Performs specific tasks (e.g., voice assistants, search engines).</li>
        <li>Examples: Siri, Alexa, Google Translate.</li>
      </ul>
      <p><strong>General AI (Strong AI)</strong></p>
      <ul>
        <li>Theoretical AI that can perform any intellectual task a human can.</li>
        <li>Does not yet exist but is a major goal in AI research.</li>
      </ul>
      <p><strong>Super AI</strong></p>
      <ul>
        <li>Hypothetical AI that surpasses human intelligence.</li>
        <li>Featured in sci-fi concepts like Skynet (Terminator) and HAL 9000 (2001: A Space Odyssey).</li>
      </ul>
      <h3>Based on Functionality</h3>
      <p><strong>Reactive Machines</strong></p>
      <ul>
        <li>Do not store past experiences (e.g., Deep Blue).</li>
      </ul>
      <p><strong>Limited Memory AI</strong></p>
      <ul>
        <li>Can learn from historical data (e.g., self-driving cars).</li>
      </ul>
      <p><strong>Theory of Mind AI</strong></p>
      <ul>
        <li>Hypothetical AI capable of understanding emotions and beliefs.</li>
      </ul>
      <p><strong>Self-Aware AI</strong></p>
      <ul>
        <li>Theoretical AI with self-consciousness and human-like thought.</li>
      </ul>
    </section>

    <section id="applications">
      <h2>Applications of AI</h2>
      <h3>Healthcare</h3>
      <ul>
        <li>AI-powered diagnostics (e.g., IBM Watson).</li>
        <li>Personalized medicine and drug discovery.</li>
        <li>AI-assisted surgeries with robotic precision.</li>
      </ul>
      <h3>Finance</h3>
      <ul>
        <li>Fraud detection in banking.</li>
        <li>Algorithmic trading and risk analysis.</li>
        <li>AI-powered chatbots for customer service.</li>
      </ul>
      <h3>Transportation</h3>
      <ul>
        <li>Self-driving cars (Tesla, Waymo).</li>
        <li>AI in traffic control and logistics.</li>
      </ul>
      <h3>Entertainment</h3>
      <ul>
        <li>AI-generated music, art, and films.</li>
        <li>Recommendation systems (Netflix, Spotify).</li>
      </ul>
      <h3>Education</h3>
      <ul>
        <li>AI-driven personalized learning systems.</li>
        <li>Automated grading and tutoring systems.</li>
      </ul>
    </section>

    <section id="advantages">
      <h2>Advantages of AI</h2>
      <ul>
        <li>Automates repetitive tasks, increasing efficiency.</li>
        <li>Reduces human error in medical and financial sectors.</li>
        <li>Enables faster decision-making with big data analysis.</li>
        <li>Improves accessibility (speech-to-text for disabled users).</li>
      </ul>
    </section>

    <section id="concerns">
      <h2>Challenges and Ethical Concerns</h2>
      <ul>
        <li>Job Displacement – Automation may replace human jobs.</li>
        <li>Bias and Discrimination – AI inherits biases from training data.</li>
        <li>Privacy Issues – AI-driven surveillance raises ethical concerns.</li>
        <li>Security Risks – AI-powered cyberattacks and misinformation threats.</li>
      </ul>
    </section>

    <section id="future">
      <h2>Future of AI</h2>
      <ul>
        <li>Quantum AI – Combining quantum computing with AI for faster processing.</li>
        <li>Ethical AI – Developing AI that aligns with human values.</li>
        <li>Human-AI Collaboration – AI working alongside humans in complex tasks.</li>
      </ul>
    </section>
    
    <section id="case-studies">
  <h2>Case Studies: AI in the Real World</h2>
  
  <h3>AI in Healthcare: Detecting Diseases with Deep Learning</h3>
  <p>Google’s DeepMind developed an AI model that can detect eye diseases with an accuracy comparable to human doctors. By analyzing thousands of retinal scans, the system assists ophthalmologists in diagnosing conditions like diabetic retinopathy and macular degeneration.</p>

  <h3>AI in Finance: Fraud Detection</h3>
  <p>Financial institutions like JPMorgan Chase use AI-powered fraud detection systems. Machine learning algorithms analyze transaction patterns to detect unusual behavior and flag potential fraud in real-time.</p>

  <h3>AI in Entertainment: Netflix’s Recommendation System</h3>
  <p>Netflix uses AI to personalize movie and TV show recommendations. By analyzing viewing history and user behavior, the AI predicts content preferences, keeping users engaged.</p>

    </section>
    
    <section id="future-ai-predictions">
  <h2>Future of AI – Expert Opinions</h2>

  <h3>Human-AI Collaboration</h3>
  <p>Experts believe AI will not replace humans but will work alongside them. AI-powered assistants will enhance productivity in workplaces, automating routine tasks while allowing humans to focus on creativity and decision-making.</p>

  <h3>Ethical AI and Regulations</h3>
  <p>With growing concerns about bias in AI, governments and organizations are working on ethical AI frameworks. Initiatives like the EU AI Act aim to regulate AI development to prevent discrimination and privacy violations.</p>

  <h3>Artificial General Intelligence (AGI)</h3>
  <p>While current AI is specialized, researchers are working on AGI—AI that can think, reason, and learn across multiple domains like humans. Experts like Ray Kurzweil predict AGI could emerge by 2045, revolutionizing industries.</p>

    </section>
    
    <section id="ai-industries">
  <h2>The Role of AI in Different Fields</h2>

  <h3>AI in Space Exploration</h3>
  <p>NASA and SpaceX use AI for space missions. AI-driven autonomous rovers like Perseverance help explore Mars, analyzing terrain and sending valuable data back to Earth. AI also aids in detecting exoplanets using deep learning models.</p>

  <h3>AI in Agriculture</h3>
  <p>AI-powered drones and sensors help farmers optimize crop yield by analyzing soil quality, detecting diseases, and automating irrigation. Companies like John Deere use AI in precision farming to reduce waste and increase efficiency.</p>

  <h3>AI in Cybersecurity</h3>
  <p>AI helps in detecting cyber threats by analyzing patterns in network traffic. Companies like Darktrace use machine learning to identify potential security breaches before they happen, protecting businesses from hackers and malware attacks.</p>

    </section>
    
    <section id="ai-culture">
  <h2>AI in Popular Culture</h2>

  <h3>Movies and TV Shows</h3>
  <ul>
    <li><strong>Terminator (1984)</strong> – Showcases a dystopian future where AI (Skynet) takes over humanity.</li>
    <li><strong>Ex Machina (2015)</strong> – Explores AI consciousness and ethical dilemmas.</li>
    <li><strong>Black Mirror</strong> – A TV series that imagines potential AI-driven futures.</li>
  </ul>

  <h3>Books</h3>
  <ul>
    <li><strong>I, Robot (Isaac Asimov)</strong> – Introduces the famous Three Laws of Robotics.</li>
    <li><strong>The Singularity is Near (Ray Kurzweil)</strong> – Predicts AI surpassing human intelligence.</li>
  </ul>

  <h3>Video Games</h3>
  <ul>
    <li><strong>Detroit: Become Human</strong> – Explores AI-human relationships.</li>
    <li><strong>Portal</strong> – Features AI antagonist GLaDOS, known for its humor and intelligence.</li>
  </ul>

    </section>
    
    <section id="ai-ethics">
  <h2>Ethical Concerns in AI</h2>

  <h3>AI Bias and Discrimination</h3>
  <p>AI systems can inherit biases from their training data. For example, facial recognition software has been criticized for misidentifying people from different ethnic backgrounds, leading to concerns about fairness and discrimination.</p>

  <h3>AI and Privacy</h3>
  <p>AI-powered surveillance tools are used for facial recognition in public spaces, raising questions about individual privacy. Governments and tech companies debate regulations to balance security with civil rights.</p>

  <h3>The Fear of AI Taking Over</h3>
  <p>Some experts warn about AI surpassing human intelligence, leading to an uncontrolled system that could make decisions without human oversight. Figures like Elon Musk and Stephen Hawking have voiced concerns about AI safety.</p>

    </section>
    
    <section id="ai-military">
  <h2>AI in Military and Defense</h2>

  <h3>AI-Powered Drones</h3>
  <p>Military organizations use AI-driven drones for surveillance and combat missions. The U.S. and China are investing in autonomous weapons that can target enemies without human intervention.</p>

  <h3>Cyber Warfare</h3>
  <p>AI is being used in cybersecurity to detect and prevent cyberattacks from rival nations. AI systems can analyze threats in real-time, helping governments protect sensitive data.</p>

  <h3>Ethical Concerns in AI Warfare</h3>
  <p>Many experts argue that AI in warfare raises serious ethical questions. Autonomous weapons could lead to decisions being made without human morality, increasing the risk of war crimes.</p>

    </section>
    
    <section id="conclusion">
      <h2>Conclusion</h2>
      <p>Artificial Intelligence is revolutionizing every industry, from healthcare to finance, transportation to entertainment. While AI offers unprecedented opportunities, it also presents challenges that must be managed responsibly. As AI continues to evolve, research in ethics, regulation, and safety will be crucial to ensuring its positive impact on society.</p>
    </section>
  </main>
  
  <a href="#" id="BackToTop">BACK TO TOP</a>

  <footer class="references">
    <h2>References</h2>
    <ul>
      <li>Turing, A. M. (1950). Computing Machinery and Intelligence. <em>Mind</em>, 59(236), 433-460.</li>
      <li>McCarthy, J., et al. (1956). Proposal for the Dartmouth Summer Research Project on Artificial Intelligence.</li>
      <li>Russell, S., & Norvig, P. (2020). <em>Artificial Intelligence: A Modern Approach</em>. Pearson.</li>
      <li>Goodfellow, I., et al. (2016). <em>Deep Learning</em>. MIT Press.</li>
      <li>Bostrom, N. (2014). <em>Superintelligence: Paths, Dangers, Strategies</em>. Oxford University Press.</li>
      <li>Tegmark, M. (2017). <em>Life 3.0: Being Human in the Age of Artificial Intelligence</em>. Knopf.</li>
      <li>Zuboff, S. (2019). <em>The Age of Surveillance Capitalism</em>. PublicAffairs.</li>
      <li>McKinsey & Company. (2021). The Future of AI in Financial Services.</li>
      <li>Kurzweil, R. (2005). <em>The Singularity Is Near</em>. Penguin.</li>
    </ul>
  </footer>
</body>
</html>