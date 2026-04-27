---
layout: default
title: People
---

<div class="people-section">

<div class="person-card principal-investigator">
  <div class="person-image">
    <img src="/assets/images/2023/02/headshot3.jpg" alt="Philip J. Freda, Jr., Ph.D., M.S." class="headshot-img">
    <div class="nasa-names clickable" onclick="openLandsatModal()" title="Click to learn more about these NASA images">
      <img src="/assets/images/Philip.png" alt="Philip spelled in NASA satellite imagery" class="nasa-name-img">
      <img src="/assets/images/Freda.png" alt="Freda spelled in NASA satellite imagery" class="nasa-name-img">
    </div>
  </div>
  <div class="person-info">
    <h2>Philip J. Freda, Jr., Ph.D., M.S.</h2>
    <p class="person-title">Principal Investigator</p>
    <p class="person-affiliation">Research Scientist I<br>Department of Computational Biomedicine<br>Cedars-Sinai Health Sciences University</p>

    <div class="person-bio">
      <p>Phil is a clinical informatician, computational biologist, and AI researcher passionate about making healthcare data work harder for patients. His research focuses on building intelligent systems that can navigate the complexity of real-world clinical data, from messy EHR records to unstructured clinical notes, and transform them into actionable insights for clinicians and researchers. His work also extends to computational genetics, where he develops evolutionary computation approaches for uncovering complex genetic associations.</p>

      <p>Before diving into clinical AI, Phil spent years studying thermal biology and evolutionary genetics in fruit flies, earning his Ph.D. from Kansas State University. That training in dealing with noisy biological data, complex interactions, and the importance of rigorous methodology followed him into the clinical domain, where he now applies similar thinking to human health challenges.</p>

      <p>When not wrestling with data pipelines or agentic frameworks, Phil can be found exploring Los Angeles with his wife, contemplating the mysteries of evolutionary theory, gaming, watching the Eagles, or searching for the perfect piece of sushi. He's a firm believer that the best science happens at the intersection of curiosity and persistence.</p>
    </div>

    <div class="person-interests">
      <h3>Research Interests</h3>
      <ul>
        <li>Agentic AI systems for clinical data processing</li>
        <li>Natural language processing for substance use phenotyping</li>
        <li>Perioperative risk prediction in spine surgery</li>
        <li>Knowledge graphs for transparent AI workflows</li>
        <li>Epistasis and gene-gene interactions</li>
      </ul>
    </div>

    <div class="person-links">
      <a href="mailto:philip.freda@cshs.org" class="btn">Email</a>
      <a href="https://scholar.google.com/citations?user=1NaI6RgAAAAJ&hl=en" class="btn" target="_blank" rel="noopener">Google Scholar</a>
      <a href="https://www.linkedin.com/in/philipfreda" class="btn" target="_blank" rel="noopener">LinkedIn</a>
    </div>

    <div class="person-pages">
      <h3>More About Phil</h3>
      <div class="person-page-links">
        <a href="/cv/" class="page-link-card">
          <span class="page-link-icon">📄</span>
          <span class="page-link-title">CV</span>
          <span class="page-link-desc">Academic curriculum vitae</span>
        </a>
        <a href="/education/" class="page-link-card">
          <span class="page-link-icon">🎓</span>
          <span class="page-link-title">Education</span>
          <span class="page-link-desc">Academic background & training</span>
        </a>
        <a href="/teaching/" class="page-link-card">
          <span class="page-link-icon">👨‍🏫</span>
          <span class="page-link-title">Teaching</span>
          <span class="page-link-desc">Courses & science outreach</span>
        </a>
        <a href="/photography/" class="page-link-card">
          <span class="page-link-icon">📷</span>
          <span class="page-link-title">Photography</span>
          <span class="page-link-desc">Nature & wildlife photography</span>
        </a>
        <a href="/timeline/" class="page-link-card">
          <span class="page-link-icon">🛤️</span>
          <span class="page-link-title">The Road So Far</span>
          <span class="page-link-desc">Career timeline & milestones</span>
        </a>
      </div>
    </div>
  </div>
</div>

</div>

<div class="join-section">
  <h2>Collaborate With Us</h2>
  <p>We're always open to collaborations with researchers, clinicians, and industry partners who share our passion for clinical AI, NLP, and improving healthcare through data-driven insights. If you have an interesting problem or dataset and think there might be synergy with our work, <a href="mailto:philip.freda@cshs.org">let's talk</a>.</p>
</div>

<!-- NASA Landsat Modal -->
<div id="landsatModal" class="landsat-modal" onclick="closeLandsatModal()">
  <div class="modal-content" onclick="event.stopPropagation()">
    <span class="close-btn" onclick="closeLandsatModal()">&times;</span>
    <h2 class="modal-title">Your Name in Landsat</h2>
    <div class="modal-images">
      <img src="/assets/images/Philip.png" alt="Philip in Landsat" class="modal-image">
      <img src="/assets/images/Freda.png" alt="Freda in Landsat" class="modal-image">
    </div>
    <p>With this online interactive, users can type in their name then view and export the graphic of that name spelled out in Earth features found in Landsat images.</p>
    
    <h3>About</h3>
    <p>The satellite images used in this interactive are part of Landsat's extensive record, spanning more than 50 years. These Landsat satellite images were sourced from NASA Earth Observatory, NASA Worldview, USGS EarthExplorer, and ESA Sentinel Hub.</p>
    
    <div class="modal-action">
      <a href="https://science.nasa.gov/mission/landsat/outreach/your-name-in-landsat/" class="btn" target="_blank" rel="noopener">Try it yourself</a>
    </div>
  </div>
</div>

<script>
  function openLandsatModal() {
    document.getElementById('landsatModal').classList.add('show');
    document.body.style.overflow = 'hidden'; 
  }
  function closeLandsatModal() {
    document.getElementById('landsatModal').classList.remove('show');
    document.body.style.overflow = '';
  }
  
  document.addEventListener('keydown', function(event) {
    if (event.key === 'Escape') {
      closeLandsatModal();
    }
  });
</script>
