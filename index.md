<style>
  :root {
    --bg-color: #ffffff;
    --text-color: #24292f;
    --heading-color: #1f2328;
    --link-color: #0969da;
    --muted-color: #59636e;
    --border-color: #d0d7de;
  }

  body.dark-mode {
    --bg-color: #2b3036;
    --text-color: #e2e5e9;
    --heading-color: #f4f5f6;
    --link-color: #9fc5ee;
    --muted-color: #bac1c9;
    --border-color: #505860;
  }

  body {
    background-color: var(--bg-color);
    color: var(--text-color);
    transition: background-color 0.25s ease, color 0.25s ease;
  }

  h1,
  h2,
  h3,
  h4,
  h5,
  h6 {
    color: var(--heading-color);
  }

  p,
  li {
    color: var(--text-color);
  }

  a {
    color: var(--link-color);
  }

  hr {
    border-color: var(--border-color);
  }

  .theme-toggle {
    position: fixed;
    top: 20px;
    right: 24px;
    z-index: 9999;
    width: 38px;
    height: 38px;
    border: none;
    border-radius: 50%;
    background: transparent;
    color: var(--text-color);
    font-size: 21px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background-color 0.2s ease, transform 0.2s ease;
  }

  .theme-toggle:hover {
    background-color: rgba(127, 127, 127, 0.14);
    transform: scale(1.05);
  }

  .theme-toggle:focus {
    outline: 2px solid var(--link-color);
    outline-offset: 2px;
  }

  @media (max-width: 600px) {
    .theme-toggle {
      top: 12px;
      right: 12px;
    }
  }
</style>
<button
  id="theme-toggle"
  class="theme-toggle"
  type="button"
  aria-label="Switch to dark mode"
  title="Switch theme"
>
  ☾
</button>

<div style="display: flex; align-items: flex-start; gap: 30px;">

  <div style="flex: 1;">

    <h1>Annie (Chenxi) Zhou</h1>

    <p>📧 Email: annie.zhou (at) wisc (dot) edu</p>

    <p>🔗 <a href="https://www.linkedin.com/in/annie-zhou-aabb09168/">LinkedIn</a></p>

    <p>
      I am a Ph.D. student in Curriculum and Instruction at the University of Wisconsin–Madison, advised by <a href="https://berland.org/">Prof. Matthew Berland</a>. As a learner, designer, and educator, I am committed to designing meaningful and engaging learning experiences that support diverse learners across contexts.
    </p>
    
    <p>📄 You can find my curriculum vitae here: <a href="Annie_Zhou_CV.pdf">CV</a>.</p>

  </div>

  <img src="./Anniezhou_Headshot.jpeg" alt="Profile photo" width="180" style="border-radius: 8px;">

</div>


<h2>Research Interests</h2>

<ul>
  <li>Community-engaged learning</li>
  <li>Culturally responsive mathematics education</li>
  <li>Learning sciences</li>
  <li>Educational technology</li>
</ul>


<h2>Selected Publications</h2>

<ul>
  <li>
    <strong>Zhou, A.</strong>, Seefeldt, K., Hui, J., Bare, C., Sanifu, L., &amp; Dillahunt, T. R. (2026). <a href="https://2026.isls.org/docs/ICLS%20Volume%202026.pdf" target="_blank" rel="noopener noreferrer"> A community-engaged curriculum design model for culturally-responsive tech consulting </a>. In B. K. Litts, D. DeLiema, C. Lee, S. Krist, A. Mawasi, L. Martin, &amp; K. Kumpulainen (Eds.), <em>Proceedings of the 20th International Conference of the Learning Sciences: ICLS 2026</em> (pp. 1797&ndash;1801). International Society of the Learning Sciences.
  </li>

  <li>
    Quintana, R., Tan, Y., Quintana, C., <strong>Zhou, A.</strong>, & Wu, J. (2026). Mapping practitioner openness and hesitation toward GenAI integration in learning design. In Advances in quantitative ethnography: 8th International Conference on Quantitative Ethnography, ICQE 2026, Hiroshima, Japan, November 9–13, 2026, proceedings. Springer.
  </li>
  
  <li>
    <strong>Zhou, A.</strong> (2026, April). 
    <em>Student Self-Positioning and the Development of Mathematical Competencies.</em> Roundtable session accepted for presentation at the Annual Meeting of the American Educational Research Association (AERA).
  </li>

  <li>
    Quintana, R. M., &amp; <strong>Zhou, A.</strong> (2026, April). 
    <em>Using affordance analysis to strategize the integration of AI-generated instructor avatars within MOOCs.</em> Poster session accepted for presentation at the Annual Meeting of the American Educational Research Association (AERA).
  </li>
</ul>


<h2>Selected Presentations</h2>

<div style="display: flex; align-items: flex-start; gap: 24px; margin-bottom: 28px;"> <a href="CTC.pdf" style="flex-shrink: 0;"> <div style="width: 100px; height: 100px; overflow: hidden; border-radius: 6px;"> <img src="CTC.jpg" alt="CTC curriculum presentation thumbnail" style="width: 100%; height: 100%; object-fit: cover; display: block;" > </div> </a> <div> <p> <strong>Zhou, A.</strong> (2026, June). <em>A community-engaged curriculum design model for culturally responsive tech consulting.</em> Short paper session accepted for presentation at the 20th International Conference of the Learning Sciences (ICLS 2026). </p> </div> </div>

<div style="display: flex; align-items: flex-start; gap: 24px; margin-bottom: 28px;">
  <a href="https://aera26.ipostersessions.com/Default.aspx?s=E2-A5-29-9B-90-FF-4C-D6-31-83-98-21-81-B9-16-EA" style="flex-shrink: 0;">
    <div style="width: 100px; height: 100px; overflow: hidden; border-radius: 6px;">
      <img 
        src="Positioning.png" 
        alt="Student self-positioning presentation thumbnail" 
        style="width: 100%; height: 100%; object-fit: cover; display: block;"
      >
    </div>
  </a>

  <div>
    <p>
      <strong>Zhou, A.</strong> (2026, April). 
      <em>Student Self-Positioning and the Development of Mathematical Competencies.</em>
      Roundtable session accepted for presentation at the Annual Meeting of the American Educational Research Association (AERA).
    </p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; gap: 24px; margin-bottom: 28px;"> <a href="https://aera26.ipostersessions.com/Default.aspx?s=78-3D-39-8D-93-35-24-3B-DB-F4-94-2B-D2-03-E2-FC" style="flex-shrink: 0;"> <div style="width: 100px; height: 100px; overflow: hidden; border-radius: 6px;"> <img src="Avatar.png" alt="AI-generated instructor avatars poster thumbnail" style="width: 100%; height: 100%; object-fit: cover; display: block;" > </div> </a> <div> <p> Quintana, R. M., &amp; <strong>Zhou, A.</strong> (2026, April). <em>Using affordance analysis to strategize the integration of AI-generated instructor avatars within MOOCs.</em> Poster session accepted for presentation at the Annual Meeting of the American Educational Research Association (AERA). </p> </div> </div>

<h2>Public Scholarship</h2>
<ul>
  <li>
   <strong>Zhou, A.</strong> (2025, June). <a href="https://blogs.lib.umich.edu/student-stories/good-teaching-historical-perspective-culturally-responsive-teaching">Good teaching from a historical perspective: Culturally responsive teaching</a>. <em>University of Michigan Library Student Stories Blog</em>.
  </li>
  <li>
    <strong>Zhou, A.</strong> (2025, February). <a href="https://sites.lsa.umich.edu/equitable-teaching/stories-of-culturally-responsive-teaching-from-frontline-instructors/">Stories of culturally responsive teaching from frontline instructors</a>. <em>Equitable Teaching Project, University of Michigan</em>.
  </li>
 </ul>

<script>
  const themeToggle = document.getElementById("theme-toggle");
  const body = document.body;

  const savedTheme = localStorage.getItem("annie-theme");

  if (savedTheme === "dark") {
    body.classList.add("dark-mode");
    themeToggle.textContent = "☀";
    themeToggle.setAttribute("aria-label", "Switch to light mode");
  }

  themeToggle.addEventListener("click", function () {
    body.classList.toggle("dark-mode");

    if (body.classList.contains("dark-mode")) {
      localStorage.setItem("annie-theme", "dark");
      themeToggle.textContent = "☀";
      themeToggle.setAttribute("aria-label", "Switch to light mode");
    } else {
      localStorage.setItem("annie-theme", "light");
      themeToggle.textContent = "☾";
      themeToggle.setAttribute("aria-label", "Switch to dark mode");
    }
  });
</script>
