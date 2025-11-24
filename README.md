<?xml version="1.0" encoding="UTF-8"?>
<!-- typing-badge.svg -->
<svg xmlns="http://www.w3.org/2000/svg" width="760" height="120" viewBox="0 0 760 120" role="img" aria-label="Typing badge">
  <style>
    /* Layout */
    .bg { fill: transparent; }
    .wrap {
      font-family: "Inter", "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      font-weight: 600;
      font-size: 20px;
      line-height: 1;
      fill: #0f172a;
    }

    /* container (foreignObject) styles */
    .container {
      display: flex;
      align-items: center;
      height: 100%;
      padding-left: 12px;
      padding-right: 12px;
      box-sizing: border-box;
    }

    /* typing area */
    .typing {
      white-space: nowrap;
      overflow: hidden;
      display: inline-block;
      vertical-align: middle;
      position: relative;
    }

    /* caret */
    .typing::after {
      content: "";
      display: inline-block;
      width: 2px;
      height: 1.1em;
      background: #0f172a;
      margin-left: 6px;
      vertical-align: middle;
      animation: blink 1s steps(2,start) infinite;
      position: relative;
      top: 2px;
    }

    @keyframes blink {
      0%, 49% { opacity: 1; }
      50%, 100% { opacity: 0; }
    }

    /* Each phrase has its own typing animation (type in, pause, delete, pause) */
    .word {
      display: inline-block;
      vertical-align: middle;
      overflow: hidden;
      white-space: nowrap;
    }

    /* Phrase-specific widths and step counts tuned to approximate character counts.
       - word1: "Aspiring Cloud & DevOps Engineer" -> 32ch
       - word2: "Lifelong Learner" -> 16ch
       - word3: "Automation Enthusiast" -> 21ch
    */
    .word1 { width: 0ch; animation: type1 9s steps(32) infinite; }
    .word2 { width: 0ch; animation: type2 9s steps(16) infinite; }
    .word3 { width: 0ch; animation: type3 9s steps(21) infinite; }

    /* Sequence timings: 
       - Each full cycle = 9s.
       - For each phrase: type ~2.4s, hold ~1.6s, delete ~2.4s, pause ~2.6s while other phrases run.
    */
    @keyframes type1 {
      0%   { width: 0ch; }
      26%  { width: 32ch; }    /* typed */
      44%  { width: 32ch; }    /* hold */
      70%  { width: 0ch; }     /* deleted */
      100% { width: 0ch; }
    }

    @keyframes type2 {
      0%   { width: 0ch; }
      33%  { width: 0ch; }     /* wait while word1 types */
      58%  { width: 16ch; }    /* typed */
      76%  { width: 16ch; }    /* hold */
      100% { width: 0ch; }     /* delete and loop */
    }

    @keyframes type3 {
      0%   { width: 0ch; }
      44%  { width: 0ch; }     /* wait while previous words run */
      70%  { width: 21ch; }    /* typed */
      88%  { width: 21ch; }    /* hold */
      100% { width: 0ch; }     /* delete and loop */
    }

    /* responsive tweak for smaller embeds */
    @media (max-width:420px) {
      .wrap { font-size: 16px; }
    }
  </style>

  <!-- Optional rounded rectangle background (transparent by default) -->
  <rect x="4" y="4" width="752" height="112" rx="12" ry="12" fill="#ffffff" fill-opacity="0.03" stroke="#e6eef8" stroke-opacity="0.06"/>

  <!-- Use foreignObject so we can rely on CSS stepping animations for the typing effect -->
  <foreignObject x="12" y="20" width="736" height="80">
    <div xmlns="http://www.w3.org/1999/xhtml" class="container wrap">
      <div style="display:flex;align-items:center;gap:12px;">
        <!-- optional icon -->
        <div style="font-size:22px;line-height:1; color:#0f172a;">👋</div>

        <!-- typing block -->
        <div class="typing" aria-hidden="false" role="img" aria-label="Typing text">
          <span class="word word1">Aspiring Cloud &amp; DevOps Engineer</span>
          <span class="word" style="width:0ch; margin-left:6px;">&nbsp;</span>
          <span class="word word2">Lifelong Learner</span>
          <span class="word" style="width:0ch; margin-left:6px;">&nbsp;</span>
          <span class="word word3">Automation Enthusiast</span>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>


<div align="center">
  
[![Website](https://img.shields.io/badge/Website-trainwithshubham.com-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.trainwithshubham.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubhamlondhe1996/)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/shubhamlondhe96/)
[![Email](https://img.shields.io/badge/Email-trainwithshubham@gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:trainwithshubham@gmail.com)

</div>

---

<div align="center">
  
### 💡 "Building the future, one deployment at a time" 

![Profile Views](https://komarev.com/ghpvc/?username=LondheShubham153&color=brightgreen&style=flat-square)
[![GitHub followers](https://img.shields.io/github/followers/LondheShubham153?label=Follow&style=social)](https://github.com/LondheShubham153)

</div>
