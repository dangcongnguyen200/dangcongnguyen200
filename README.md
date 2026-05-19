<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Dang Cong Nguyen | AI Systems Engineer & Enterprise Architect</title>
  <!-- Google Fonts + Font Awesome + Orbitron (for consistency) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&family=Orbitron:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Animate.css for subtle entries (optional but nice) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: radial-gradient(circle at 20% 30%, #0A0F1E, #03050B);
      font-family: 'Inter', 'Segoe UI', sans-serif;
      color: #E2E8F0;
      line-height: 1.5;
      padding: 2rem 1rem;
    }

    /* custom scroll */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #0F172A;
    }
    ::-webkit-scrollbar-thumb {
      background: #00F7FF;
      border-radius: 8px;
    }

    .container {
      max-width: 1280px;
      margin: 0 auto;
      backdrop-filter: blur(2px);
    }

    /* glassmorphism cards */
    .glass-card {
      background: rgba(15, 25, 45, 0.45);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(0, 247, 255, 0.2);
      border-radius: 2rem;
      box-shadow: 0 20px 35px -12px rgba(0,0,0,0.5);
      transition: all 0.25s ease;
    }
    .glass-card:hover {
      border-color: rgba(0, 247, 255, 0.5);
      box-shadow: 0 25px 40px -12px rgba(0,247,255,0.15);
    }

    /* headings */
    h1, h2, h3, .mono-head {
      font-family: 'Orbitron', monospace;
      letter-spacing: -0.02em;
    }
    .gradient-text {
      background: linear-gradient(135deg, #00F7FF 0%, #7C3AED 70%);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }
    .badge-glow {
      box-shadow: 0 0 8px rgba(0,247,255,0.3);
    }

    /* dynamic typing area */
    .typing-container {
      min-height: 110px;
    }
    .code-block {
      background: #01020a;
      border-radius: 1.25rem;
      padding: 1.2rem;
      font-family: 'Fira Code', 'JetBrains Mono', monospace;
      font-size: 0.85rem;
      border-left: 4px solid #00F7FF;
      overflow-x: auto;
    }
    .stat-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.6rem;
    }
    .tech-icon-row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }
    .tech-icon-row img {
      transition: transform 0.2s;
    }
    .tech-icon-row img:hover {
      transform: translateY(-5px);
    }
    .repo-link {
      color: #00F7FF;
      text-decoration: none;
      border-bottom: 1px dashed #7C3AED;
    }
    .footer-wave {
      margin-top: 3rem;
    }
    button, .fake-link {
      cursor: default;
    }
    .social-badge {
      transition: all 0.2s;
    }
    .social-badge:hover {
      transform: scale(1.05);
      filter: drop-shadow(0 0 6px #00F7FF);
    }
    @media (max-width: 640px) {
      body { padding: 1rem; }
      .glass-card { border-radius: 1.5rem; }
    }
  </style>
</head>
<body>
<div class="container">

  <!-- HEADER with glitch / gradient -->
  <div class="glass-card p-6 md:p-8 mb-8 animate__animated animate__fadeInUp" style="padding: 2rem 1.5rem;">
    <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
      <div>
        <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight">
          <span class="gradient-text">Dang Cong Nguyen</span>
        </h1>
        <div class="typing-container mt-3">
          <p id="dynamic-role" class="text-xl font-mono text-cyan-300"></p>
        </div>
        <div class="flex flex-wrap gap-2 mt-4">
          <span class="px-3 py-1 rounded-full bg-cyan-500/10 border border-cyan-400/30 text-cyan-300 text-sm"><i class="fas fa-microchip mr-1"></i> AI Systems Engineer</span>
          <span class="px-3 py-1 rounded-full bg-purple-500/10 border border-purple-400/30 text-purple-300 text-sm"><i class="fas fa-cloud-upload-alt mr-1"></i> Cloud-Native Architect</span>
          <span class="px-3 py-1 rounded-full bg-indigo-500/10 border border-indigo-400/30 text-indigo-300 text-sm"><i class="fas fa-bolt mr-1"></i> Realtime Infrastructure</span>
          <span class="px-3 py-1 rounded-full bg-emerald-500/10 border border-emerald-400/30 text-emerald-300 text-sm"><i class="fas fa-robot mr-1"></i> AI SaaS Platform Builder</span>
        </div>
      </div>
      <div class="flex gap-3 flex-wrap">
        <a href="https://github.com/dangcongnguyen200" target="_blank" class="social-badge"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"></a>
        <a href="https://github.com/dangcongnguyen200?tab=repositories" target="_blank" class="social-badge"><img src="https://img.shields.io/badge/Projects-7C3AED?style=for-the-badge&logo=github" alt="projects"></a>
        <span><img src="https://komarev.com/ghpvc/?username=dangcongnguyen200&label=Profile+Views&color=00F7FF&style=for-the-badge" alt="views"></span>
        <span><img src="https://img.shields.io/github/followers/dangcongnguyen200?style=for-the-badge&logo=github&color=00F7FF" alt="followers"></span>
      </div>
    </div>
    <div class="mt-6 flex flex-wrap gap-3 justify-start border-t border-cyan-800/30 pt-5">
      <span><img src="https://img.shields.io/badge/AI-FIRST-ENGINEERING-00F7FF?style=for-the-badge"/></span>
      <span><img src="https://img.shields.io/badge/CLOUD-NATIVE-SYSTEMS-7C3AED?style=for-the-badge"/></span>
      <span><img src="https://img.shields.io/badge/REALTIME-INFRASTRUCTURE-0EA5E9?style=for-the-badge"/></span>
      <span><img src="https://img.shields.io/badge/VIETNAM-DEVELOPER-red?style=for-the-badge"/></span>
    </div>
  </div>

  <!-- ABOUT ME + CLASS DEF -->
  <div class="grid md:grid-cols-2 gap-8 mb-10">
    <div class="glass-card p-6 animate__animated animate__fadeInLeft">
      <div class="flex items-center gap-2 mb-4">
        <i class="fas fa-user-astronaut text-3xl text-cyan-400"></i>
        <h2 class="text-2xl font-bold font-orbitron">✦ About Me ✦</h2>
      </div>
      <div class="code-block text-sm bg-black/60">
        <pre style="font-family: inherit; margin:0; color:#cbd5e1;"><span style="color:#7C3AED;">class</span> <span style="color:#00F7FF;">DangCongNguyen</span> {
  <span style="color:#94A3B8;">title</span> = <span style="color:#fbbf24;">"AI Systems Engineer"</span>;
  <span style="color:#94A3B8;">roles</span> = [
    <span style="color:#fbbf24;">"Enterprise AI Architect"</span>,
    <span style="color:#fbbf24;">"Cloud-native Fullstack Developer"</span>,
    <span style="color:#fbbf24;">"Realtime Infrastructure Engineer"</span>,
    <span style="color:#fbbf24;">"AI SaaS Platform Engineer"</span>
  ];
  <span style="color:#94A3B8;">focusesOn</span> = [
    <span style="color:#fbbf24;">"AI-powered Enterprise Platforms"</span>,
    <span style="color:#fbbf24;">"Realtime Architectures"</span>,
    <span style="color:#fbbf24;">"Scalable SaaS Ecosystems"</span>,
    <span style="color:#fbbf24;">"Distributed Systems"</span>
  ];
  <span style="color:#94A3B8;">engineeringMindset</span> = [
    <span style="color:#fbbf24;">"AI-first"</span>, <span style="color:#fbbf24;">"Scalable by Design"</span>,
    <span style="color:#fbbf24;">"Realtime Everything"</span>
  ];
}</pre>
      </div>
      <p class="mt-4 text-gray-300 text-sm leading-relaxed">🚀 Designing intelligent enterprise ecosystems for the AI-native future (2026→2030). I build high-performance, realtime infrastructure and AI automation at scale.</p>
    </div>

    <div class="glass-card p-6 animate__animated animate__fadeInRight">
      <div class="flex items-center gap-2 mb-4">
        <i class="fas fa-microchip text-3xl text-purple-400"></i>
        <h2 class="text-2xl font-bold font-orbitron">⚡ Core Domains</h2>
      </div>
      <div class="grid grid-cols-2 gap-3 mt-2">
        <div><i class="fas fa-robot text-cyan-400 mr-2"></i> AI Systems (NLP/LLM)</div>
        <div><i class="fas fa-charging-station text-cyan-400 mr-2"></i> Realtime Infrastructure</div>
        <div><i class="fas fa-cloud text-purple-400 mr-2"></i> Cloud-native Apps</div>
        <div><i class="fas fa-chart-line text-purple-400 mr-2"></i> Enterprise Dashboards</div>
        <div><i class="fas fa-brain text-cyan-400 mr-2"></i> AI SaaS Platforms</div>
        <div><i class="fas fa-sync-alt text-cyan-400 mr-2"></i> Automation Systems</div>
        <div><i class="fas fa-eye text-purple-400 mr-2"></i> Observability & Monitoring</div>
        <div><i class="fas fa-building text-purple-400 mr-2"></i> Scalable Architecture</div>
      </div>
      <div class="mt-5 pt-3 border-t border-gray-700/50">
        <span class="text-cyan-300 font-mono">✦ Featured Platform: </span><span class="font-bold text-white">🤖 AI-Powered ORM</span>
        <p class="text-xs text-gray-400 mt-1">Enterprise-grade AI reputation operating system — realtime intelligence + automation.</p>
      </div>
    </div>
  </div>

  <!-- SYSTEM ARCHITECTURE GLASS CARD -->
  <div class="glass-card p-6 mb-10 animate__animated animate__fadeInUp">
    <h2 class="text-2xl font-orbitron font-bold mb-3 flex items-center gap-2"><i class="fas fa-project-diagram text-cyan-400"></i> 🏗️ Enterprise System Architecture</h2>
    <div class="code-block bg-black/70 text-xs md:text-sm">
      <pre style="color:#b9c7d9;">
┌────────────────────────────────────────────────────┐
│                  Presentation Layer                │
├────────────────────────────────────────────────────┤
│ Next.js • React • TypeScript • TailwindCSS        │
│ Enterprise Dashboard • Analytics UI • Realtime UI │
└────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────┐
│                    Backend Layer                   │
├────────────────────────────────────────────────────┤
│ Supabase • PostgreSQL • REST APIs                 │
│ Authentication • Edge Functions • Live Sync       │
└────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────┐
│                       AI Layer                     │
├────────────────────────────────────────────────────┤
│ OpenAI • NLP Processing • AI Classification       │
│ Sentiment Engine • AI Workflows • Recommendations │
└────────────────────────────────────────────────────┘

┌────────────────────────────────────────────────────┐
│                Infrastructure Layer                │
├────────────────────────────────────────────────────┤
│ Cloud Architecture • Monitoring • DevOps          │
│ Security • Scalability • CI/CD Pipelines          │
└────────────────────────────────────────────────────┘
      </pre>
    </div>
  </div>

  <!-- TECH STACK + GitHub stats (live-like) -->
  <div class="grid md:grid-cols-3 gap-6 mb-10">
    <div class="glass-card p-5 col-span-2">
      <h3 class="text-xl font-orbitron mb-3"><i class="fas fa-cogs text-cyan-400"></i> ⚙️ Tech Ecosystem</h3>
      <div class="tech-icon-row">
        <img src="https://skillicons.dev/icons?i=nextjs,react,ts,nodejs,supabase,postgres,docker,tailwind,firebase,vercel,git,github,vscode&perline=6" alt="tech stack icons" width="100%">
      </div>
      <div class="mt-5 grid grid-cols-2 gap-3 text-xs text-gray-300">
        <div><i class="fas fa-check-circle text-emerald-400"></i> AI Orchestration: OpenAI, LangChain</div>
        <div><i class="fas fa-check-circle text-emerald-400"></i> Realtime: Supabase Realtime, WebSockets</div>
        <div><i class="fas fa-check-circle text-emerald-400"></i> Cloud: Vercel, AWS principles</div>
        <div><i class="fas fa-check-circle text-emerald-400"></i> Monitoring: Grafana / Prometheus style</div>
      </div>
    </div>
    <div class="glass-card p-5 flex flex-col justify-between">
      <h3 class="text-xl font-orbitron flex items-center gap-2"><i class="fab fa-github-alt"></i> GitHub Pulse</h3>
      <div class="mt-2 space-y-3">
        <div><img src="https://github-readme-stats.vercel.app/api?username=dangcongnguyen200&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&icon_color=00F7FF&title_color=00F7FF&ring=7C3AED&text_color=cbd5e1&hide=issues" width="100%" alt="stats"></div>
        <div><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dangcongnguyen200&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7C3AED&text_color=94a3b8" width="100%" alt="top langs"></div>
      </div>
    </div>
  </div>

  <!-- CURRENT MISSION + STREAK / ENGINEERING PHILOSOPHY -->
  <div class="grid md:grid-cols-2 gap-7 mb-10">
    <div class="glass-card p-6 text-center">
      <div class="flex justify-center mb-2"><i class="fas fa-satellite-dish text-4xl text-cyan-400"></i></div>
      <p class="font-mono text-lg font-semibold">🚀 Current Mission</p>
      <div class="code-block text-center bg-transparent border-none">
        <code class="text-cyan-300 text-sm">Building Intelligent Enterprise Ecosystems for the AI-native Future (2026 → 2030)</code>
      </div>
      <div class="mt-5">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=dangcongnguyen200&theme=tokyonight&hide_border=true&background=0D1117&ring=00F7FF&fire=7C3AED" width="100%" alt="streak">
      </div>
    </div>

    <div class="glass-card p-6">
      <h3 class="text-xl font-orbitron flex gap-2"><i class="fas fa-brain"></i> Engineering Philosophy</h3>
      <div class="code-block mt-3 bg-black/40 text-sm">
        <pre style="font-family: monospace;">
Design scalable systems.
Build realtime experiences.
Integrate AI natively.
Automate intelligently.
Engineer enterprise reliability.
Create future-ready ecosystems.
        </pre>
      </div>
      <div class="mt-4 flex flex-wrap gap-2">
        <span class="px-2 py-1 rounded bg-cyan-950/70 text-cyan-300 text-xs border border-cyan-500/50">AI-native Core</span>
        <span class="px-2 py-1 rounded bg-purple-950/70 text-purple-300 text-xs border border-purple-500/50">Distributed First</span>
        <span class="px-2 py-1 rounded bg-indigo-950/70 text-indigo-300 text-xs border border-indigo-500/50">Realtime DNA</span>
      </div>
    </div>
  </div>

  <!-- VISION + EXPLORING -->
  <div class="glass-card p-6 mb-10">
    <div class="flex flex-wrap justify-between items-start gap-4">
      <div>
        <h2 class="text-2xl font-orbitron"><i class="fas fa-chart-line"></i> 🌌 Vision 2026 → 2030</h2>
        <div class="text-center md:text-left mt-2">
          <code class="bg-black/40 px-4 py-2 inline-block rounded-lg text-cyan-300 font-mono">AI + Cloud + Automation + Realtime = Next-Generation Enterprise Ecosystems</code>
        </div>
      </div>
      <div>
        <i class="fas fa-flask text-3xl text-purple-400"></i>
      </div>
    </div>
    <div class="mt-6 grid sm:grid-cols-2 gap-4">
      <div><span class="font-bold text-cyan-300">📚 Currently Exploring:</span> Advanced AI Agents, Distributed Systems, Autonomous Workflows, Realtime Observability, AI-native Infra</div>
      <div><span class="font-bold text-purple-300">🌍 Open To Collaboration:</span> AI Engineering • Enterprise SaaS • Cloud Infrastructure • Realtime Platforms</div>
    </div>
  </div>

  <!-- QUOTE SIGNATURE -->
  <div class="glass-card p-6 text-center relative overflow-hidden mb-8">
    <div class="absolute top-0 left-0 w-32 h-32 bg-cyan-500/10 rounded-full blur-3xl"></div>
    <i class="fas fa-quote-right text-3xl text-cyan-500/50 mb-2"></i>
    <p class="text-xl md:text-2xl font-medium italic font-mono tracking-wide">"I don't just build applications. I engineer intelligent scalable ecosystems designed for the future of enterprise technology."</p>
    <div class="mt-2 text-sm text-gray-400">— Dang Cong Nguyen, AI Systems Engineer</div>
    <div class="flex justify-center gap-4 mt-4">
      <i class="fab fa-github-alt text-gray-400 hover:text-cyan-400 transition"></i>
      <i class="fab fa-twitter text-gray-400 hover:text-cyan-400 transition"></i>
      <i class="fab fa-linkedin text-gray-400 hover:text-cyan-400 transition"></i>
    </div>
  </div>

  <!-- CONNECT FOOTER -->
  <div class="flex flex-wrap justify-center gap-3 mb-8">
    <a href="https://github.com/dangcongnguyen200" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
    <a href="https://github.com/dangcongnguyen200?tab=repositories" target="_blank"><img src="https://img.shields.io/badge/Explore%20Repos-7C3AED?style=for-the-badge&logo=github"/></a>
    <span><img src="https://img.shields.io/badge/AI%20Architect-Scalable%20Systems-00F7FF?style=for-the-badge"/></span>
  </div>

  <!-- FOOTER WAVE -->
  <div class="footer-wave">
    <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:00F7FF,50:7C3AED,100:0D1117&section=footer" style="width:100%; display:block;" alt="wave"/>
  </div>
</div>

<script>
  // advanced dynamic typing effect for roles (upgraded)
  const roles = [
    "AI Systems Engineer",
    "Enterprise AI Architect",
    "Cloud-Native Fullstack Developer",
    "Realtime Infrastructure Engineer",
    "AI SaaS Platform Builder",
    "Designing Future Enterprise Ecosystems",
    "Scalable AI Automation Systems"
  ];
  let idx = 0;
  const roleElement = document.getElementById('dynamic-role');
  let charIndex = 0;
  let currentText = "";
  let isDeleting = false;

  function typeEffect() {
    const fullText = roles[idx];
    if (isDeleting) {
      currentText = fullText.substring(0, charIndex - 1);
      charIndex--;
    } else {
      currentText = fullText.substring(0, charIndex + 1);
      charIndex++;
    }
    roleElement.innerHTML = `<span class="border-r-2 border-cyan-400 pr-1">${currentText}</span>`;
    if (!isDeleting && charIndex === fullText.length) {
      isDeleting = true;
      setTimeout(typeEffect, 2000);
      return;
    }
    if (isDeleting && charIndex === 0) {
      isDeleting = false;
      idx = (idx + 1) % roles.length;
      setTimeout(typeEffect, 300);
      return;
    }
    const speed = isDeleting ? 45 : 90;
    setTimeout(typeEffect, speed);
  }
  typeEffect();

  // Additional interactive micro: add hover shine to glass cards (soft)
  const cards = document.querySelectorAll('.glass-card');
  cards.forEach(card => {
    card.addEventListener('mouseenter', () => {
      card.style.transition = 'all 0.2s ease';
      card.style.borderColor = 'rgba(0,247,255,0.7)';
    });
    card.addEventListener('mouseleave', () => {
      card.style.borderColor = 'rgba(0,247,255,0.2)';
    });
  });
</script>
</body>
</html>
