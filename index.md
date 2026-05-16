---
layout: default
title: "Home"
---

<!-- Page Container -->
<div style="position: relative;">

  <!-- Background Video -->
  <video autoplay muted loop playsinline
         style="position: fixed; top: 0; left: 0; width: 100vw; height: 100vh;
                object-fit: cover; z-index: 0;">
    <source src="/pics/vid2.MP4" type="video/mp4">
  </video>

  <!-- Foreground Content -->
  <div style="position: relative; z-index: 1; display: flex; flex-direction: column; align-items: center; padding: 60px 20px;">

    <!-- Profile Card -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center; 
                padding: 25px; max-width: 400px; border-radius: 14px;
                box-shadow: 0 6px 20px rgba(0,0,0,0.12); background-color: rgba(255,255,255,0.85);
                transition: transform 0.3s; margin-top: 80px;">
      
      <img src="/pics/Isaiahagboola.jpeg" 
           alt="Isaiah Agboola, PhD Candidate in Mechanical Engineering." 
           style="width: 180px; height: 180px; border-radius: 50%; object-fit: cover; margin-bottom: 15px;">
      <h1 style="margin: 0; font-size: 3rem;"><strong>Check back, website under construction</strong></h1>
      <h1 style="margin: 0; font-size: 1.9rem;"><strong>Isaiah Agboola</strong></h1>
      <p style="margin: 6px 0 15px 0; font-size: 1rem; color: #555;">
        <strong>PhD Candidate</strong> in Mechanical Engineering, University of Michigan
      </p>

      <div style="font-size: 0.95rem; color: #444; line-height: 1.6;">
        📧 <a href="mailto:agboola@umich.edu">agboola@umich.edu</a><br>
        🔗 <a href="https://scholar.google.com/citations?user=zls1RxgAAAAJ&hl=en" target="_blank">Google Scholar</a> · 
           <a href="https://github.com/isagboola/" target="_blank">GitHub</a> · 
           <a href="https://www.linkedin.com/in/isaiah-agboola-799b58166/" target="_blank">LinkedIn</a>
      </div>
    </div>

    <!-- Bio Section -->
    <div style="max-width: 800px; margin-top: 40px; line-height: 1.7; font-size: 1rem; color: #333; background-color: rgba(255,255,255,0.85); padding: 20px; border-radius: 14px;">
      <p>
      I am a second-year Ph.D student at the
      <a href="https://aisys.engin.umich.edu/" target="_blank">AI sys Lab</a>, part of the 
      <a href="https://me.engin.umich.edu/" target="_blank">Department of Mechanical Engineering</a> at the University of Michigan, Ann Arbor. 
      I am advised by <a href="https://me.engin.umich.edu/people/faculty/uduak-inyang-udoh/" target="_blank">Professor Uduak Inyang-Udoh</a>. 
      My research is at the intersection of <strong> controls and advanced manufacturing </strong>, with a focus on additive manufacturing specifically, <strong> Directed Energy Deposition</strong>. I also work on  <strong>optimal control</strong> in autonomous systems, especially in safety-critical settings. 
      </p>

      <p>
        Previously, I worked as Mechanical Engineering Intern at
        <a href="https://www.dangote.com/" target="_blank">Dangote Cement, Nigeria</a>.
      </p>
    </div>

  </div>
</div>

<style>
  /* Hover effect for profile card */
  .profile-card:hover {
    transform: translateY(-5px);
  }

  /* Ensure responsive stacking */
  @media (max-width: 768px) {
    .profile-card, .bio-section {
      width: 90%;
    }
  }
</style>
