<!--
  README.md
  Premium GitHub Profile for SAITEJA0217
  Dark Futuristic • Black + Neon Blue • Glassmorphism • Recruiter-friendly
  Built with GitHub Markdown + supported HTML only.
-->

<!-- =========================
     1. Custom SVG Banner
     ========================= -->
<div align="center">
  <!-- SVG: Custom Dark Futuristic Banner with Glassmorphism -->
  <svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="SAITEJA0217 - Dark Futuristic Banner">
    <defs>
      <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#001219" />
        <stop offset="45%" stop-color="#000a12" />
        <stop offset="100%" stop-color="#000000" />
      </linearGradient>

      <linearGradient id="neon" x1="0" x2="1">
        <stop offset="0%" stop-color="#00e6ff" stop-opacity="0.95"/>
        <stop offset="60%" stop-color="#007bff" stop-opacity="0.85"/>
        <stop offset="100%" stop-color="#004cff" stop-opacity="0.8"/>
      </linearGradient>

      <filter id="glass" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="8" result="b"/>
        <feComponentTransfer>
          <feFuncA type="table" tableValues="0 0.25"/>
        </feComponentTransfer>
        <feBlend in="SourceGraphic" in2="b" mode="normal"/>
      </filter>

      <filter id="softShadow" x="-50%" y="-50%" width="200%" height="200%">
        <feDropShadow dx="0" dy="6" stdDeviation="12" flood-color="#000a12" flood-opacity="0.7"/>
      </filter>

      <mask id="fade">
        <rect x="0" y="0" width="1200" height="220" fill="url(#g1)"/>
      </mask>
    </defs>

    <!-- Background -->
    <rect width="1200" height="220" fill="url(#g1)"/>

    <!-- Neon grid lines -->
    <g opacity="0.06" stroke="url(#neon)" stroke-width="1">
      <path d="M0 180 L1200 40" stroke-opacity="0.06"/>
      <path d="M0 160 L1200 20" stroke-opacity="0.04"/>
    </g>

    <!-- Floating glass card -->
    <g transform="translate(40,18)" filter="url(#softShadow)">
      <rect x="0" y="0" rx="14" ry="14" width="1120" height="184" fill="#071018" opacity="0.46" stroke="rgba(0,200,255,0.12)" stroke-width="1" />
      <rect x="2" y="2" rx="12" ry="12" width="1116" height="180" fill="url(#g1)" opacity="0.08" filter="url(#glass)"></rect>

      <!-- Left accent -->
      <rect x="24" y="34" rx="8" ry="8" width="380" height="116" fill="rgba(2,20,30,0.6)"></rect>

      <!-- Neon accent bar -->
      <rect x="24" y="28" rx="4" ry="4" width="10" height="124" fill="url(#neon)"></rect>

      <!-- Name and Title -->
      <g font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif">
        <text x="54" y="66" fill="#00f0ff" font-size="28" font-weight="700" letter-spacing="0.4">SAITEJA K</text>
        <text x="54" y="96" fill="#bcdcff" font-size="14" font-weight="600">AI Engineer • Open Source • Product-focused</text>
        <text x="54" y="122" fill="#9bbfe8" font-size="12" font-weight="500" opacity="0.9">Designing reliable ML systems and production-grade AI experiences.</text>
      </g>

      <!-- Right summary chips -->
      <g transform="translate(580,34)" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif">
        <rect x="0" y="0" rx="8" ry="8" width="468" height="52" fill="rgba(0,12,20,0.36)" stroke="rgba(0,150,255,0.06)"></rect>
        <text x="18" y="24" fill="#9ee9ff" font-size="13" font-weight="700">Recruiter-friendly • Remote-ready • Works well with product teams</text>
        <text x="18" y="40" fill="#8fbfe8" font-size="12">Actively building AI products focused on developer workflows & education.</text>
      </g>

      <!-- Subtle circuit lines -->
      <g stroke="#004cff" stroke-opacity="0.06" stroke-width="1">
        <path d="M480 34 L680 20 L900 40" />
        <path d="M480 150 L700 170 L920 150" />
      </g>
    </g>
  </svg>
</div>

<!-- Small spacer -->
<p></p>

<!-- =========================
     2. Animated Typing Text
     ========================= -->
<div align="center">
  <img alt="typing" src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1500&color=00e6ff&background=00000000&width=780&lines=AI+Engineer;Open+Source+Contributor;Building+Scalable+AI+Products;Mentor+and+Collaborator" />
</div>

<!-- =========================
     3. Professional Hero Section
     ========================= -->
<div align="center" style="margin-top:12px">
  <h1 align="center" style="margin:8px 0 4px 0;font-family: 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;color:#cfefff;">
    SAITEJA K — AI Engineer
  </h1>
  <p align="center" style="max-width:900px;color:#98c9ff;margin:4px 12px 16px 12px;line-height:1.45">
    I build production-grade AI features, automation tools, and developer-first products.
    My work spans backend systems, model integrations, Chrome extensions, and platform tooling.
    Passionate about developer experience, clean architecture, and effective collaboration.
  </p>

  <!-- Quick badges -->
  <p align="center" style="margin:6px 0 18px 0">
    <img src="https://img.shields.io/badge/Role-AI%20Engineer-00bfff?style=for-the-badge&logo=ai" alt="Role" />
    <img src="https://img.shields.io/badge/Location-Remote-0a1f2c?style=for-the-badge" alt="Remote" />
    <img src="https://img.shields.io/badge/Available-Open%20to%20Opportunities-007bff?style=for-the-badge" alt="Open to work" />
  </p>
</div>

<hr style="border:0.5px solid rgba(255,255,255,0.04)">

<!-- =========================
     4. About Me
     ========================= -->
## About Me

I am an AI engineer focused on building reliable ML systems, production integrations, and delightful developer tooling. I bring product-minded engineering to machine learning: shipping features, maintaining systems, and documenting for scale.

- Years: 3+ years building AI-first products.
- Focus: Model integration, data pipelines, automation, Chrome extensions, platform reliability.
- Approach: Minimalist interfaces, pragmatic design, and strong code hygiene.

<p style="margin:6px 0 0 0">
  <strong>Core strengths:</strong>
  clean architecture • API-first design • automated testing • telemetry & metrics • documentation
</p>

<!-- =========================
     5. Experience Timeline
     ========================= -->
## Experience

<section>
  <div style="max-width:960px;margin:8px auto 18px;padding:8px 10px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(0,0,0,0.02));">
    <ol style="list-style:none;margin:0;padding:0;font-family:Inter,Segoe UI,Roboto,Arial,sans-serif;color:#cfefff;">
      <li style="margin:18px 0;padding:12px;border-left:3px solid rgba(0,140,255,0.12);">
        <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;">
          <div>
            <div style="font-weight:700;color:#00e6ff;font-size:14px">AI Engineer • FormPilot (Contract)</div>
            <div style="font-size:12px;color:#b9dff7">Building Chrome extension automation and form intelligence — production ML integrations & telemetry.</div>
          </div>
          <div style="font-size:12px;color:#94c8ff">2025 — Present</div>
        </div>
      </li>

      <li style="margin:18px 0;padding:12px;border-left:3px solid rgba(0,140,255,0.08);">
        <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;">
          <div>
            <div style="font-weight:700;color:#bfeeff;font-size:14px">Product Engineer • InternLink</div>
            <div style="font-size:12px;color:#b9dff7">Led backend for internship matching & AI recommendation pipelines. Improved candidate-job match accuracy by instrumented experiments.</div>
          </div>
          <div style="font-size:12px;color:#94c8ff">2023 — 2025</div>
        </div>
      </li>

      <li style="margin:18px 0;padding:12px;border-left:3px solid rgba(0,140,255,0.06);">
        <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;">
          <div>
            <div style="font-weight:700;color:#bfeeff;font-size:14px">Founder Contributor • BharatSkill</div>
            <div style="font-size:12px;color:#b9dff7">Built career platform features, mentoring flows, and assessment pipelines to help skilling and placement.</div>
          </div>
          <div style="font-size:12px;color:#94c8ff">2022 — 2024</div>
        </div>
      </li>
    </ol>
  </div>
</section>

<!-- =========================
     6. Tech Stack grouped by category
     ========================= -->
## Tech Stack

<div style="display:flex;flex-wrap:wrap;gap:12px;margin-bottom:14px">
  <!-- Platform -->
  <div style="min-width:260px;flex:1;background:rgba(255,255,255,0.01);padding:12px;border-radius:8px">
    <div style="font-weight:700;color:#bfeeff;margin-bottom:8px">Languages & Platforms</div>
    <p style="margin:0">
      <img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white" alt="Python" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node" />
      <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
      <img src="https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
    </p>
  </div>

  <!-- MLOps -->
  <div style="min-width:260px;flex:1;background:rgba(255,255,255,0.01);padding:12px;border-radius:8px">
    <div style="font-weight:700;color:#bfeeff;margin-bottom:8px">ML / AI</div>
    <p style="margin:0">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="sklearn" />
      <img src="https://img.shields.io/badge/transformers-1C9?style=flat-square&logo=transformers&logoColor=white" alt="transformers" />
      <img src="https://img.shields.io/badge/MLflow-F06C00?style=flat-square&logo=mlflow&logoColor=white" alt="mlflow" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="docker" />
    </p>
  </div>

  <!-- Cloud -->
  <div style="min-width:260px;flex:1;background:rgba(255,255,255,0.01);padding:12px;border-radius:8px">
    <div style="font-weight:700;color:#bfeeff;margin-bottom:8px">Cloud & Infra</div>
    <p style="margin:0">
      <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="aws" />
      <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white" alt="gcp" />
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="k8s" />
      <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="prometheus" />
    </p>
  </div>

  <!-- Tools -->
  <div style="min-width:260px;flex:1;background:rgba(255,255,255,0.01);padding:12px;border-radius:8px">
    <div style="font-weight:700;color:#bfeeff;margin-bottom:8px">Tools & Productivity</div>
    <p style="margin:0">
      <img src="https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white" alt="git" />
      <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" alt="vscode" />
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="postman" />
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="figma" />
    </p>
  </div>
</div>

<!-- =========================
     7. GitHub Analytics Dashboard
     ========================= -->
## GitHub Analytics

<div align="center" style="display:flex;flex-wrap:wrap;gap:12px;justify-content:center">
  <!-- Readme Stats -->
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=SAITEJA0217&show_icons=true&theme=dark&hide_border=true&count_private=true&title_color=00e6ff&icon_color=00bfff" alt="GitHub Stats" style="max-width:100%;border-radius:10px" />

  <!-- Top Languages -->
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SAITEJA0217&layout=compact&theme=dark&hide_border=true&title_color=00e6ff" alt="Top Languages" style="max-width:520px;border-radius:10px" />

  <!-- Streak -->
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com?user=SAITEJA0217&theme=dark&hide_border=true&date_format=%5BY%20%5DM%20j" alt="GitHub Streak" style="max-width:420px;border-radius:10px" />
</div>

<!-- =========================
     8. Contribution Graph
     ========================= -->
## Contribution Activity

<p align="center">
  <img src="https://activity-graph.herokuapp.com/graph?username=SAITEJA0217&theme=react-dark&area=true" alt="Contribution Graph" style="width:100%;max-width:980px;border-radius:10px" />
</p>

<!-- =========================
     9. GitHub Snake Animation
     ========================= -->
## GitHub Snake

<p align="center">
  <img src="https://github-profile-snake.vercel.app/?user=SAITEJA0217&theme=dark" alt="GitHub Snake" style="max-width:940px;border-radius:10px" />
</p>

<!-- =========================
     10. GitHub Metrics
     ========================= -->
## GitHub Metrics

<p align="center">
  <!-- If this endpoint doesn't load, the Readme stats above provide metrics -->
  <img src="https://github-metrics.vercel.app/api?username=SAITEJA0217&theme=dark" alt="GitHub Metrics" style="max-width:980px;border-radius:10px" />
</p>

<!-- =========================
     11. GitHub Trophy
     ========================= -->
## Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=SAITEJA0217&theme=dark&margin-w=8&margin-h=8" alt="Trophies" style="max-width:980px;border-radius:10px" />
</p>

<hr style="border:0.5px solid rgba(255,255,255,0.04)">

<!-- =========================
     12. Current Focus Roadmap
     ========================= -->
## Current Focus — Roadmap

<div style="max-width:980px;margin:8px auto 18px;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(0,0,0,0.02));">
  <table style="width:100%;border-collapse:collapse;color:#cfefff;font-family:Inter,Segoe UI,Roboto,Arial,sans-serif">
    <tr>
      <td style="width:46%;padding:8px 12px;vertical-align:top">
        <div style="font-weight:700;color:#00e6ff;margin-bottom:6px">Next 3 months</div>
        <ul style="margin:0;padding-left:18px">
          <li>Ship FormPilot v2: smarter form automation with embeddings & offline sync.</li>
          <li>Launch Jarvis MVP: personal assistant with secure context and plugin integrations.</li>
          <li>Polish InternLink matching: scalable ranking & feedback loop instrumentation.</li>
        </ul>
      </td>
      <td style="width:54%;padding:8px 12px;vertical-align:top">
        <div style="font-weight:700;color:#00e6ff;margin-bottom:6px">Ongoing</div>
        <p style="margin:0 0 8px 0">Improving observability, test coverage, and developer documentation across core projects.</p>
        <div style="display:flex;flex-direction:column;gap:8px">
          <img src="https://img.shields.io/badge/Model+Integrations-60%25-00bfff?style=flat-square" alt="Model Integrations" />
          <img src="https://img.shields.io/badge/Platform+Reliability-45%25-00bfff?style=flat-square" alt="Reliability" />
          <img src="https://img.shields.io/badge/Developer+Experience-75%25-00bfff?style=flat-square" alt="DX" />
        </div>
      </td>
    </tr>
  </table>
</div>

<!-- =========================
     13. Featured Projects displayed as premium cards
     ========================= -->
## Featured Projects

<div style="display:flex;flex-direction:column;gap:14px;max-width:980px;margin:8px auto 18px">
  <!-- Card: InternLink -->
  <div style="display:flex;flex-direction:row;gap:12px;padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(0,0,0,0.02));border:1px solid rgba(0,140,255,0.04)">
    <div style="min-width:120px;flex:0 0 120px">
      <img src="https://raw.githubusercontent.com/SAITEJA0217/SAITEJA0217/main/assets/internlink-banner.png" alt="InternLink" style="width:120px;height:72px;object-fit:cover;border-radius:6px;background:#02121a" />
    </div>
    <div style="flex:1">
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="font-weight:700;color:#cfefff">InternLink</div>
          <div style="font-size:13px;color:#aaddff;margin-top:6px">AI-driven internship placement platform — ranking, recommendations and interview prep tools.</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:6px;align-items:flex-end">
          <div>
            <a href="https://github.com/SAITEJA0217/InternLink" target="_blank"><img src="https://img.shields.io/badge/GitHub-Repository-0a66c2?style=flat-square&logo=github" alt="repo" /></a>
            <a href="#" target="_blank"><img src="https://img.shields.io/badge/Live-Demo-00bfff?style=flat-square" alt="live" /></a>
          </div>
          <div style="font-size:12px;color:#98c9ff">Stack: Python • FastAPI • PostgreSQL • PyTorch • Docker</div>
        </div>
      </div>
      <div style="margin-top:10px;font-size:13px;color:#bfeeff">Key contributions: recommendation pipeline, infra automation, candidate matching experiments, and product metrics dashboard.</div>
    </div>
  </div>

  <!-- Card: FormPilot -->
  <div style="display:flex;flex-direction:row;gap:12px;padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(0,0,0,0.02));border:1px solid rgba(0,140,255,0.04)">
    <div style="min-width:120px;flex:0 0 120px">
      <img src="https://raw.githubusercontent.com/SAITEJA0217/SAITEJA0217/main/assets/formpilot-banner.png" alt="FormPilot" style="width:120px;height:72px;object-fit:cover;border-radius:6px;background:#02121a" />
    </div>
    <div style="flex:1">
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="font-weight:700;color:#cfefff">FormPilot</div>
          <div style="font-size:13px;color:#aaddff;margin-top:6px">AI form automation Chrome extension — auto-fill, extract context, and automate workflows.</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:6px;align-items:flex-end">
          <div>
            <a href="https://github.com/SAITEJA0217/FormPilot" target="_blank"><img src="https://img.shields.io/badge/GitHub-Repository-0a66c2?style=flat-square&logo=github" alt="repo" /></a>
            <a href="#" target="_blank"><img src="https://img.shields.io/badge/Chrome-Extension-007bff?style=flat-square&logo=google-chrome" alt="chrome" /></a>
          </div>
          <div style="font-size:12px;color:#98c9ff">Stack: TypeScript • Chrome Extensions • embeddings • serverless</div>
        </div>
      </div>
      <div style="margin-top:10px;font-size:13px;color:#bfeeff">Key contributions: extension architecture, privacy-first embedding pipelines, and robust offline sync experience.</div>
    </div>
  </div>

  <!-- Card: Jarvis -->
  <div style="display:flex;flex-direction:row;gap:12px;padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(0,0,0,0.02));border:1px solid rgba(0,140,255,0.04)">
    <div style="min-width:120px;flex:0 0 120px">
      <img src="https://raw.githubusercontent.com/SAITEJA0217/SAITEJA0217/main/assets/jarvis-banner.png" alt="Jarvis" style="width:120px;height:72px;object-fit:cover;border-radius:6px;background:#02121a" />
    </div>
    <div style="flex:1">
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="font-weight:700;color:#cfefff">Jarvis</div>
          <div style="font-size:13px;color:#aaddff;margin-top:6px">Personal AI assistant — private, extensible, and integrated with daily developer tools.</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:6px;align-items:flex-end">
          <div>
            <a href="https://github.com/SAITEJA0217/Jarvis" target="_blank"><img src="https://img.shields.io/badge/GitHub-Repository-0a66c2?style=flat-square&logo=github" alt="repo" /></a>
            <a href="#" target="_blank"><img src="https://img.shields.io/badge/Docs-Live-00bfff?style=flat-square" alt="docs" /></a>
          </div>
          <div style="font-size:12px;color:#98c9ff">Stack: Python • LangChain • FastAPI • Redis • Docker</div>
        </div>
      </div>
      <div style="margin-top:10px;font-size:13px;color:#bfeeff">Key contributions: orchestration, privacy controls, and plugin-based skill system.</div>
    </div>
  </div>

  <!-- Card: BharatSkill -->
  <div style="display:flex;flex-direction:row;gap:12px;padding:14px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), rgba(0,0,0,0.02));border:1px solid rgba(0,140,255,0.04)">
    <div style="min-width:120px;flex:0 0 120px">
      <img src="https://raw.githubusercontent.com/SAITEJA0217/SAITEJA0217/main/assets/bharatskill-banner.png" alt="BharatSkill" style="width:120px;height:72px;object-fit:cover;border-radius:6px;background:#02121a" />
    </div>
    <div style="flex:1">
      <div style="display:flex;justify-content:space-between;align-items:flex-start">
        <div>
          <div style="font-weight:700;color:#cfefff">BharatSkill</div>
          <div style="font-size:13px;color:#aaddff;margin-top:6px">AI career platform helping students prepare for roles with personalized learning and assessment paths.</div>
        </div>
        <div style="display:flex;flex-direction:column;gap:6px;align-items:flex-end">
          <div>
            <a href="https://github.com/SAITEJA0217/BharatSkill" target="_blank"><img src="https://img.shields.io/badge/GitHub-Repository-0a66c2?style=flat-square&logo=github" alt="repo" /></a>
            <a href="#" target="_blank"><img src="https://img.shields.io/badge/Platform-Live-00bfff?style=flat-square" alt="live" /></a>
          </div>
          <div style="font-size:12px;color:#98c9ff">Stack: Node.js • React • MongoDB • ML features</div>
        </div>
      </div>
      <div style="margin-top:10px;font-size:13px;color:#bfeeff">Key contributions: platform architecture, assessment pipelines, and job matching logic.</div>
    </div>
  </div>
</div>

<!-- =========================
     14. Open Source Contributions
     ========================= -->
## Open Source

I contribute to projects that improve developer workflows and AI accessibility. Selected contributions:

- Contributor to several ML tooling repositories — PRs include feature additions, tests, and CI improvements.
- Maintainer: small utilities used across my projects (see repos above).
- Open to mentoring and code reviews for early-stage contributors.

<p style="margin-top:8px">
  <a href="https://github.com/SAITEJA0217?tab=repositories" target="_blank"><img src="https://img.shields.io/badge/Explore%20Repos-View%20All-007bff?style=flat-square&logo=github" alt="repos" /></a>
</p>

<!-- =========================
     15. Certifications
     ========================= -->
## Certifications

<div style="display:flex;flex-wrap:wrap;gap:10px;align-items:flex-start">
  <div style="background:rgba(255,255,255,0.01);padding:10px;border-radius:8px;min-width:220px">
    <div style="font-weight:700;color:#bfeeff">Professional ML Engineer — Coursera</div>
    <div style="font-size:13px;color:#9ccfff;margin-top:6px">Practical ML engineering concepts and deployment best practices.</div>
  </div>

  <div style="background:rgba(255,255,255,0.01);padding:10px;border-radius:8px;min-width:220px">
    <div style="font-weight:700;color:#bfeeff">Google Cloud: ML Ops Specialization</div>
    <div style="font-size:13px;color:#9ccfff;margin-top:6px">Model deployment, monitoring, and CI/CD for ML.</div>
  </div>

  <div style="background:rgba(255,255,255,0.01);padding:10px;border-radius:8px;min-width:220px">
    <div style="font-weight:700;color:#bfeeff">Advanced Python & System Design</div>
    <div style="font-size:13px;color:#9ccfff;margin-top:6px">Designing scalable APIs and robust backend systems.</div>
  </div>
</div>

<!-- =========================
     16. Achievements
     ========================= -->
## Achievements

- Built FormPilot extension with >1k early users in pilot.
- Mentored multiple interns who shipped product features.
- Regular contributor to open-source tooling & developer libraries.
- Strong track record of running experiments to improve product metrics.

<!-- =========================
     17. Resume Download
     ========================= -->
## Resume

Download a PDF of my resume:

<p>
  <a href="https://github.com/SAITEJA0217/SAITEJA0217/raw/main/resume.pdf" target="_blank"><img src="https://img.shields.io/badge/Download-Resume-00bfff?style=for-the-badge&logo=adobe-reader" alt="Resume" /></a>
</p>

(Note: resume.pdf should be uploaded to the repository root for direct download.)

<!-- =========================
     18. Contact Section
     ========================= -->
## Contact

I'm available for roles & collaborations. Recruiters and product teams are welcome to reach out.

<div style="display:flex;gap:8px;flex-wrap:wrap">
  <a href="mailto:saiteja@example.com"><img src="https://img.shields.io/badge/Email-saiteja%40example.com-00bfff?style=flat-square&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://www.linkedin.com/in/saitejak/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin" alt="linkedin" /></a>
  <a href="https://twitter.com/SAITEJA0217" target="_blank"><img src="https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=flat-square&logo=twitter" alt="twitter" /></a>
  <a href="https://calendly.com/saiteja/30min" target="_blank"><img src="https://img.shields.io/badge/Book%20Time-30min-00bfff?style=flat-square&logo=calendly" alt="calendly" /></a>
</div>

<!-- Visitor Counter -->
<p style="margin-top:12px">
  <img src="https://visitor-badge.glitch.me/badge?page_id=SAITEJA0217.SAITEJA0217&left_color=0D1117&right_color=00aaff" alt="visitor-badge" />
</p>

<!-- =========================
     19. Professional Footer
     ========================= -->
<hr style="border:0.5px solid rgba(255,255,255,0.04)">

<div align="center" style="padding:14px 4px">
  <p style="color:#9ccfff;margin:0;font-size:14px">
    Thank you for visiting my profile. I prefer concise, reliable engineering and clear product thinking — if that fits your team, let's talk.
  </p>

  <p style="margin-top:10px">
    <img src="https://img.shields.io/badge/License-MIT-00bfff?style=flat-square" alt="license" />
    <img src="https://img.shields.io/badge/Code%20Style-PEP8-0a1f2c?style=flat-square" alt="style" />
    <img src="https://img.shields.io/badge/Docs-Open-00bfff?style=flat-square" alt="docs" />
  </p>

  <p style="margin-top:8px;color:#94c8ff;font-size:12px">© SAITEJA K — Crafted for recruiters & collaborators • Optimized for GitHub Dark Theme</p>
</div>
