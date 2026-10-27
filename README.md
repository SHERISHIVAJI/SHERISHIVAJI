<!-- ═══════════════════════════════════════════════════════════════
     DESIGN TOKENS (documented for future edits)
     base:#0B1120  panel1:#0F172A  panel2:#1E293B
     cyan:#06B6D4  indigo:#6366F1  violet:#7C3AED
     amber:#CA8A04 green:#2EA043   text:#F8FAFC  muted:#94A3B8
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ─── HERO BANNER ─── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=blur&height=210&color=gradient&customColorList=0,2,2,30,30&text=&animation=fadeIn" alt="Hero background"/>

<!-- ─── ANIMATED GRADIENT NAME ─── -->
<svg width="800" height="100" viewBox="0 0 800 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Sheri Shivaji">
  <defs>
    <linearGradient id="heroTitle" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#06B6D4">
        <animate attributeName="stop-color" values="#06B6D4;#7C3AED;#CA8A04;#06B6D4" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#CA8A04;#06B6D4;#7C3AED" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#CA8A04">
        <animate attributeName="stop-color" values="#CA8A04;#06B6D4;#7C3AED;#CA8A04" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  <text x="400" y="52" text-anchor="middle" font-family="'Segoe UI',-apple-system,sans-serif" font-size="46" font-weight="900" fill="url(#heroTitle)" letter-spacing="6">SHERI SHIVAJI</text>
  <text x="400" y="80" text-anchor="middle" font-family="'Segoe UI',-apple-system,sans-serif" font-size="13" font-weight="600" fill="#94A3B8" letter-spacing="4">SOFTWARE DEVELOPER · FULL STACK ENGINEER</text>
</svg>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=06B6D4&center=true&vCenter=true&width=750&lines=Java+%7C+JavaScript+%7C+React;Building+production-ready+web+applications;Open+to+Full+Stack+and+Java+Developer+roles" alt="Animated focus"/>

<br/>

<!-- ─── PULSING STATUS PILL (SVG) ─── -->
<svg width="230" height="34" viewBox="0 0 230 34" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Open to work">
  <defs>
    <linearGradient id="pillBg" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#052E16"/>
      <stop offset="100%" stop-color="#14532D"/>
    </linearGradient>
  </defs>
  <rect x="0.5" y="0.5" width="229" height="33" rx="16.5" fill="url(#pillBg)" stroke="#2EA043" stroke-width="1"/>
  <circle cx="20" cy="17" r="5" fill="#2EA043">
    <animate attributeName="r" values="5;8;5" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="36" y="22" fill="#22C55E" font-family="'Segoe UI',sans-serif" font-size="11" font-weight="700" letter-spacing="1.5">OPEN TO WORK · FULL STACK</text>
</svg>

<br/><br/>

<!-- ─── CTA ROW ─── -->
<a href="https://www.linkedin.com/in/sherishivaji2774/">
  <img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:shivajisheri@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/SHERISHIVAJI?tab=repositories">
  <img src="https://img.shields.io/badge/GITHUB-REPOSITORIES-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/>
</a>
<a href="https://leetcode.com/u/SHERISHIVAJI/">
  <img src="https://img.shields.io/badge/LEETCODE-PROFILE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=SHERISHIVAJI&style=for-the-badge&color=06B6D4&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <defs>
    <linearGradient id="waveA" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0"/>
      <stop offset="50%" stop-color="#06B6D4" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <path d="M0,18 C200,4 400,32 600,18 C800,4 1000,32 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     QUICK STATS — 4 animated ring counters
     ═══════════════════════════════════════════════════════════════ -->

<table width="100%" cellpadding="6">
<tr>
<td bgcolor="#0F172A" align="center" width="25%" cellpadding="12">
  <svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="1 plus years experience">
    <defs>
      <linearGradient id="ring1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#06B6D4"/>
        <stop offset="100%" stop-color="#0EA5E9"/>
      </linearGradient>
    </defs>
    <circle cx="75" cy="75" r="58" fill="none" stroke="#1E293B" stroke-width="8"/>
    <circle cx="75" cy="75" r="58" fill="none" stroke="url(#ring1)" stroke-width="8" stroke-linecap="round"
      stroke-dasharray="364" stroke-dashoffset="364" transform="rotate(-90 75 75)">
      <animate attributeName="stroke-dashoffset" from="364" to="131" dur="2s" fill="freeze"/>
    </circle>
    <text x="75" y="80" text-anchor="middle" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="30" font-weight="800">1+</text>
    <text x="75" y="102" text-anchor="middle" fill="#94A3B8" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="600" letter-spacing="1.5">YEARS EXP</text>
  </svg>
</td>
<td bgcolor="#0F172A" align="center" width="25%" cellpadding="12">
  <svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="3 plus projects shipped">
    <defs>
      <linearGradient id="ring2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#7C3AED"/>
        <stop offset="100%" stop-color="#6366F1"/>
      </linearGradient>
    </defs>
    <circle cx="75" cy="75" r="58" fill="none" stroke="#1E293B" stroke-width="8"/>
    <circle cx="75" cy="75" r="58" fill="none" stroke="url(#ring2)" stroke-width="8" stroke-linecap="round"
      stroke-dasharray="364" stroke-dashoffset="364" transform="rotate(-90 75 75)">
      <animate attributeName="stroke-dashoffset" from="364" to="109" dur="2s" fill="freeze"/>
    </circle>
    <text x="75" y="80" text-anchor="middle" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="30" font-weight="800">3+</text>
    <text x="75" y="102" text-anchor="middle" fill="#94A3B8" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="600" letter-spacing="1.5">PROJECTS</text>
  </svg>
</td>
<td bgcolor="#0F172A" align="center" width="25%" cellpadding="12">
  <svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="CGPA 8.15 out of 10">
    <defs>
      <linearGradient id="ring3" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#CA8A04"/>
        <stop offset="100%" stop-color="#F59E0B"/>
      </linearGradient>
    </defs>
    <circle cx="75" cy="75" r="58" fill="none" stroke="#1E293B" stroke-width="8"/>
    <circle cx="75" cy="75" r="58" fill="none" stroke="url(#ring3)" stroke-width="8" stroke-linecap="round"
      stroke-dasharray="364" stroke-dashoffset="364" transform="rotate(-90 75 75)">
      <animate attributeName="stroke-dashoffset" from="364" to="67" dur="2s" fill="freeze"/>
    </circle>
    <text x="75" y="80" text-anchor="middle" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800">8.15</text>
    <text x="75" y="102" text-anchor="middle" fill="#94A3B8" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="600" letter-spacing="1.5">B.TECH CGPA</text>
  </svg>
</td>
<td bgcolor="#0F172A" align="center" width="25%" cellpadding="12">
  <svg width="150" height="150" viewBox="0 0 150 150" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="5 plus certifications">
    <defs>
      <linearGradient id="ring4" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#2EA043"/>
        <stop offset="100%" stop-color="#22C55E"/>
      </linearGradient>
    </defs>
    <circle cx="75" cy="75" r="58" fill="none" stroke="#1E293B" stroke-width="8"/>
    <circle cx="75" cy="75" r="58" fill="none" stroke="url(#ring4)" stroke-width="8" stroke-linecap="round"
      stroke-dasharray="364" stroke-dashoffset="364" transform="rotate(-90 75 75)">
      <animate attributeName="stroke-dashoffset" from="364" to="91" dur="2s" fill="freeze"/>
    </circle>
    <text x="75" y="80" text-anchor="middle" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="30" font-weight="800">5+</text>
    <text x="75" y="102" text-anchor="middle" fill="#94A3B8" font-family="'Segoe UI',sans-serif" font-size="10" font-weight="600" letter-spacing="1.5">CERTIFICATIONS</text>
  </svg>
</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,32 400,4 600,18 C800,32 1000,4 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     01 · ABOUT
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 01 About Me">
  <defs>
    <linearGradient id="secA" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#7C3AED"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secA)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">01</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">ABOUT ME</text>
  <line x1="290" y1="38" x2="900" y2="38" stroke="url(#secA)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="0" cellspacing="0">
<tr>
<td bgcolor="#0F172A" cellpadding="28" width="62%" valign="top">

<h3 style="color:#F8FAFC;">Engineer. Builder. Problem solver.</h3>

I'm **Sheri Shivaji**, a Computer Science Engineering graduate building **practical, database-backed web applications** — from role-based workflow tools to browser-based utilities.

My focus is **clean architecture, meaningful abstractions, and code teammates can inherit**.

<br/>

<img src="https://api.iconify.design/mdi/target.svg?color=06B6D4" width="16" height="16" align="absmiddle"/> &nbsp; **Current role:** Quality Associate at Amazon
<br/>
<img src="https://api.iconify.design/mdi/laptop.svg?color=06B6D4" width="16" height="16" align="absmiddle"/> &nbsp; **Development focus:** Java · React · JavaScript
<br/>
<img src="https://api.iconify.design/mdi/database-outline.svg?color=06B6D4" width="16" height="16" align="absmiddle"/> &nbsp; **Databases:** MySQL · Supabase
<br/>
<img src="https://api.iconify.design/mdi/brain.svg?color=06B6D4" width="16" height="16" align="absmiddle"/> &nbsp; **Interests:** OOP · DSA · REST APIs · System Design
<br/>
<img src="https://api.iconify.design/mdi/rocket-launch-outline.svg?color=06B6D4" width="16" height="16" align="absmiddle"/> &nbsp; **Goal:** Ship maintainable software with real user value

</td>
<td bgcolor="#1E293B" cellpadding="28" width="38%" valign="middle" align="center">

<img src="https://skillicons.dev/icons?i=java,js,react,html,css,mysql,supabase,git,github&perline=3" alt="Core stack"/>

<br/><br/>

<table cellpadding="4">
<tr>
<td align="center">
<img src="https://api.iconify.design/mdi/hammer-wrench.svg?color=6366F1" width="22" height="22" alt=""/>
<br/><sub><b>BUILDING</b></sub>
<br/><sub>SV_ORBIT</sub>
</td>
<td align="center">
<img src="https://api.iconify.design/mdi/book-open-page-variant-outline.svg?color=CA8A04" width="22" height="22" alt=""/>
<br/><sub><b>LEARNING</b></sub>
<br/><sub>System Design</sub>
</td>
<td align="center">
<img src="https://api.iconify.design/mdi/briefcase-search-outline.svg?color=2EA043" width="22" height="22" alt=""/>
<br/><sub><b>OPEN TO</b></sub>
<br/><sub>Full Stack</sub>
</td>
</tr>
</table>

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,4 400,32 600,18 C800,4 1000,32 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     02 · SKILLS — animated proficiency bars (custom SVG)
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 02 Skills">
  <defs>
    <linearGradient id="secB" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#6366F1"/>
      <stop offset="100%" stop-color="#7C3AED"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secB)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">02</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">TECHNICAL STACK</text>
  <line x1="370" y1="38" x2="900" y2="38" stroke="url(#secB)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="0" cellspacing="0">
<tr>
<td bgcolor="#0F172A" cellpadding="28" valign="top">

<svg width="100%" viewBox="0 0 700 460" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skill proficiency bars">
  <defs>
    <linearGradient id="gJava" x1="0%" x2="100%"><stop offset="0%" stop-color="#06B6D4"/><stop offset="100%" stop-color="#0EA5E9"/></linearGradient>
    <linearGradient id="gJs" x1="0%" x2="100%"><stop offset="0%" stop-color="#F59E0B"/><stop offset="100%" stop-color="#EAB308"/></linearGradient>
    <linearGradient id="gReact" x1="0%" x2="100%"><stop offset="0%" stop-color="#06B6D4"/><stop offset="100%" stop-color="#3B82F6"/></linearGradient>
    <linearGradient id="gPy" x1="0%" x2="100%"><stop offset="0%" stop-color="#FBBF24"/><stop offset="100%" stop-color="#FCD34D"/></linearGradient>
    <linearGradient id="gHtml" x1="0%" x2="100%"><stop offset="0%" stop-color="#EF4444"/><stop offset="100%" stop-color="#F97316"/></linearGradient>
    <linearGradient id="gSql" x1="0%" x2="100%"><stop offset="0%" stop-color="#A855F7"/><stop offset="100%" stop-color="#7C3AED"/></linearGradient>
    <linearGradient id="gSupa" x1="0%" x2="100%"><stop offset="0%" stop-color="#22C55E"/><stop offset="100%" stop-color="#10B981"/></linearGradient>
    <linearGradient id="gGit" x1="0%" x2="100%"><stop offset="0%" stop-color="#F97316"/><stop offset="100%" stop-color="#DC2626"/></linearGradient>
  </defs>

  <text x="0" y="20" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">Java</text>
  <text x="700" y="20" fill="#06B6D4" font-family="monospace" font-size="13" text-anchor="end">92%</text>
  <rect x="0" y="28" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="28" width="0" height="9" rx="4.5" fill="url(#gJava)"><animate attributeName="width" values="0;644" dur="1.4s" fill="freeze"/></rect>

  <text x="0" y="78" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">JavaScript</text>
  <text x="700" y="78" fill="#F59E0B" font-family="monospace" font-size="13" text-anchor="end">88%</text>
  <rect x="0" y="86" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="86" width="0" height="9" rx="4.5" fill="url(#gJs)"><animate attributeName="width" values="0;616" dur="1.6s" fill="freeze"/></rect>

  <text x="0" y="136" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">React</text>
  <text x="700" y="136" fill="#3B82F6" font-family="monospace" font-size="13" text-anchor="end">85%</text>
  <rect x="0" y="144" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="144" width="0" height="9" rx="4.5" fill="url(#gReact)"><animate attributeName="width" values="0;595" dur="1.8s" fill="freeze"/></rect>

  <text x="0" y="194" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">HTML / CSS</text>
  <text x="700" y="194" fill="#F97316" font-family="monospace" font-size="13" text-anchor="end">90%</text>
  <rect x="0" y="202" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="202" width="0" height="9" rx="4.5" fill="url(#gHtml)"><animate attributeName="width" values="0;630" dur="1.3s" fill="freeze"/></rect>

  <text x="0" y="252" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">Python</text>
  <text x="700" y="252" fill="#FBBF24" font-family="monospace" font-size="13" text-anchor="end">78%</text>
  <rect x="0" y="260" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="260" width="0" height="9" rx="4.5" fill="url(#gPy)"><animate attributeName="width" values="0;546" dur="1.9s" fill="freeze"/></rect>

  <text x="0" y="310" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">MySQL</text>
  <text x="700" y="310" fill="#A855F7" font-family="monospace" font-size="13" text-anchor="end">82%</text>
  <rect x="0" y="318" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="318" width="0" height="9" rx="4.5" fill="url(#gSql)"><animate attributeName="width" values="0;574" dur="1.7s" fill="freeze"/></rect>

  <text x="0" y="368" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">Supabase</text>
  <text x="700" y="368" fill="#22C55E" font-family="monospace" font-size="13" text-anchor="end">75%</text>
  <rect x="0" y="376" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="376" width="0" height="9" rx="4.5" fill="url(#gSupa)"><animate attributeName="width" values="0;525" dur="2s" fill="freeze"/></rect>

  <text x="0" y="426" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="14" font-weight="700">Git / GitHub</text>
  <text x="700" y="426" fill="#F97316" font-family="monospace" font-size="13" text-anchor="end">88%</text>
  <rect x="0" y="434" width="700" height="9" rx="4.5" fill="#1E293B"/>
  <rect x="0" y="434" width="0" height="9" rx="4.5" fill="url(#gGit)"><animate attributeName="width" values="0;616" dur="1.5s" fill="freeze"/></rect>
</svg>

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,32 400,4 600,18 C800,32 1000,4 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     03 · EXPERIENCE
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 03 Experience">
  <defs>
    <linearGradient id="secC" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#0F9D8A"/>
      <stop offset="100%" stop-color="#06B6D4"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secC)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">03</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">EXPERIENCE</text>
  <line x1="310" y1="38" x2="900" y2="38" stroke="url(#secC)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="0" cellspacing="0">
<tr>
<td width="5%" bgcolor="#0F9D8A"></td>
<td bgcolor="#0F172A" cellpadding="28" width="95%" valign="top">

<h3>Quality Associate</h3>
<img src="https://img.shields.io/badge/AMAZON-LMAQ%20%C2%B7%20DELIVERY%20QUALITY-0F9D8A?style=flat-square&logo=amazon&logoColor=white" alt="Amazon"/>
<img src="https://img.shields.io/badge/STATUS-CURRENT-2EA043?style=flat-square&logo=checkmarx&logoColor=white" alt="Current"/>

Operational quality assurance for overall delivery — ensuring accuracy, consistency, and process discipline at scale.

<br/><br/>

<img src="https://api.iconify.design/mdi/check-circle-outline.svg?color=0F9D8A" width="16" height="16" align="absmiddle"/> &nbsp; Evaluate delivery-quality work against defined standards
<br/>
<img src="https://api.iconify.design/mdi/magnify.svg?color=0F9D8A" width="16" height="16" align="absmiddle"/> &nbsp; Identify discrepancies and drive consistency
<br/>
<img src="https://api.iconify.design/mdi/chart-line.svg?color=0F9D8A" width="16" height="16" align="absmiddle"/> &nbsp; Apply analytical judgment within established workflows

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,4 400,32 600,18 C800,4 1000,32 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     04 · EDUCATION
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 04 Education">
  <defs>
    <linearGradient id="secD" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#CA8A04"/>
      <stop offset="100%" stop-color="#F59E0B"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secD)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">04</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">EDUCATION</text>
  <line x1="300" y1="38" x2="900" y2="38" stroke="url(#secD)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="0" cellspacing="0">
<tr>
<td width="5%" bgcolor="#CA8A04"></td>
<td bgcolor="#0F172A" cellpadding="28" width="95%" valign="top">

<h3>Bachelor of Technology — Computer Science Engineering</h3>
<img src="https://img.shields.io/badge/AVANTHI%20INSTITUTE-OF%20ENGINEERING%20%26%20TECHNOLOGY-CA8A04?style=flat-square" alt="University"/>
<img src="https://img.shields.io/badge/2021%20--%202025-CA8A04?style=flat-square" alt="Years"/>
<img src="https://img.shields.io/badge/CGPA-8.15%20%2F%2010-CA8A04?style=flat-square" alt="CGPA"/>

Coursework in **programming, data structures, software engineering, databases**, and **application architecture**.

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,32 400,4 600,18 C800,32 1000,4 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     05 · PROJECTS — 2x2 colored grid
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 05 Featured Projects">
  <defs>
    <linearGradient id="secE" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secE)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">05</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">FEATURED PROJECTS</text>
  <line x1="370" y1="38" x2="900" y2="38" stroke="url(#secE)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="8" cellspacing="0">
<tr>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top" align="center">

<img src="https://api.iconify.design/mdi/satellite-variant.svg?color=7C3AED" width="42" height="42" alt=""/>
<h3>SV_ORBIT</h3>
<sub><b>Enterprise Workflow &amp; Role-Based Task Hub</b></sub>

<br/><br/>

<img src="https://img.shields.io/badge/IN%20PROGRESS-CA8A04?style=flat-square" alt="Status"/>

<br/><br/>

Workflow management app with task organization, role-based access, and team productivity tooling.

<br/><br/>

<img src="https://skillicons.dev/icons?i=react,js,supabase" perline="3" alt="Stack"/>

<br/>

<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Task &amp; workflow management
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Role-oriented application design
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Frontend + database integration

</td>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top" align="center">

<img src="https://api.iconify.design/mdi/shield-lock-outline.svg?color=7C3AED" width="42" height="42" alt=""/>
<h3>Navigating Privacy Conflicts</h3>
<sub><b>Privacy Challenges in Social Media</b></sub>

<br/><br/>

<img src="https://img.shields.io/badge/COMPLETE-2EA043?style=flat-square" alt="Status"/>

<br/><br/>

Java web application exploring privacy conflict resolution in social platforms.

<br/><br/>

<img src="https://skillicons.dev/icons?i=java,mysql" perline="2" alt="Stack"/>

<br/>

<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Dynamic web application development
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> JSP + Servlet server-side logic
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> JDBC + MySQL integration

<br/><br/>

<a href="https://github.com/SHERISHIVAJI/Navigating_privacy_conflicts_in_social_media">
  <img src="https://img.shields.io/badge/VIEW%20SOURCE-181717?style=flat-square&logo=github&logoColor=white" alt="Source"/>
</a>

</td>
</tr>
<tr>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top" align="center">

<img src="https://api.iconify.design/mdi/robot-outline.svg?color=7C3AED" width="42" height="42" alt=""/>
<h3>SHERU — Virtual Assistant</h3>
<sub><b>Browser-Based Personal Assistant</b></sub>

<br/><br/>

<img src="https://img.shields.io/badge/LIVE%20ON%20VERCEL-2EA043?style=flat-square" alt="Status"/>

<br/><br/>

Interactive browser assistant built on modern web APIs — no backend required.

<br/><br/>

<img src="https://skillicons.dev/icons?i=html,css,js" perline="3" alt="Stack"/>

<br/>

<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Interactive web interface
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> JavaScript-based functionality
<br/>
<img src="https://api.iconify.design/mdi/check.svg?color=2EA043" width="14" height="14" align="absmiddle"/> Browser API integration

<br/><br/>

<a href="https://github.com/SHERISHIVAJI/Shivaji_Virtual_Assistent">
  <img src="https://img.shields.io/badge/SOURCE-181717?style=flat-square&logo=github&logoColor=white" alt="Source"/>
</a>
<a href="https://shivaji-virtual-assistent.vercel.app/">
  <img src="https://img.shields.io/badge/LIVE%20DEMO-06B6D4?style=flat-square&logo=vercel&logoColor=white" alt="Live"/>
</a>

</td>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top" align="center">

<img src="https://api.iconify.design/mdi/cog-outline.svg?color=7C3AED" width="42" height="42" alt=""/>
<h3>Engineering Approach</h3>
<sub><b>How I build</b></sub>

<br/><br/>

Principles I apply to every project:

<br/>

<img src="https://api.iconify.design/mdi/puzzle-outline.svg?color=7C3AED" width="14" height="14" align="absmiddle"/> Reusable components, maintainable code
<br/>
<img src="https://api.iconify.design/mdi/layers-outline.svg?color=7C3AED" width="14" height="14" align="absmiddle"/> Clear separation of responsibilities
<br/>
<img src="https://api.iconify.design/mdi/database-outline.svg?color=7C3AED" width="14" height="14" align="absmiddle"/> Database-driven functionality
<br/>
<img src="https://api.iconify.design/mdi/bug-outline.svg?color=7C3AED" width="14" height="14" align="absmiddle"/> Debugging &amp; error handling
<br/>
<img src="https://api.iconify.design/mdi/trending-up.svg?color=7C3AED" width="14" height="14" align="absmiddle"/> Continuous improvement

<br/><br/>

<img src="https://img.shields.io/badge/CLEAN%20CODE-PASS-2EA043?style=flat-square" alt="Clean code"/>
<img src="https://img.shields.io/badge/SCALABLE%20DESIGN-PASS-2EA043?style=flat-square" alt="Scalable"/>

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,4 400,32 600,18 C800,4 1000,32 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     06 · ANALYTICS
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 06 GitHub Analytics">
  <defs>
    <linearGradient id="secF" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#0891B2"/>
      <stop offset="100%" stop-color="#06B6D4"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secF)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">06</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">GITHUB ANALYTICS</text>
  <line x1="370" y1="38" x2="900" y2="38" stroke="url(#secF)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=SHERISHIVAJI&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&margin-h=8&row=1&column=7" alt="GitHub trophies"/>

<br/><br/>

<a href="https://github.com/SHERISHIVAJI">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=SHERISHIVAJI&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true&bg_color=0F172A&title_color=06B6D4&icon_color=7C3AED&text_color=F8FAFC" alt="GitHub stats"/>
</a>
<a href="https://github.com/SHERISHIVAJI">
  <img height="180" src="https://streak-stats.demolab.com?user=SHERISHIVAJI&theme=tokyonight&hide_border=true&background=0F172A&stroke=1E293B&ring=7C3AED&fire=06B6D4&currStreakLabel=06B6D4&sideLabels=F8FAFC&dates=94A3B8" alt="GitHub streak"/>
</a>

<br/>

<a href="https://github.com/SHERISHIVAJI">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SHERISHIVAJI&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=0F172A&title_color=06B6D4&text_color=F8FAFC" alt="Top languages"/>
</a>

<br/><br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=SHERISHIVAJI&bg_color=0F172A&color=06B6D4&line=7C3AED&point=F8FAFC&area=true&hide_border=true" alt="Activity graph"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SHERISHIVAJI/SHERISHIVAJI/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SHERISHIVAJI/SHERISHIVAJI/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/SHERISHIVAJI/SHERISHIVAJI/output/github-contribution-grid-snake.svg" width="100%">
</picture>

</div>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,32 400,4 600,18 C800,32 1000,4 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     07 · CERTIFICATIONS
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 07 Certifications">
  <defs>
    <linearGradient id="secG" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#CA8A04"/>
      <stop offset="100%" stop-color="#F59E0B"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secG)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">07</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">CERTIFICATIONS</text>
  <line x1="340" y1="38" x2="900" y2="38" stroke="url(#secG)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

</div>

<table width="100%" cellpadding="8" cellspacing="0">
<tr>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top">

**Programming &amp; Software Development**

<br/>

<img src="https://api.iconify.design/mdi/language-java.svg?color=CA8A04" width="16" height="16" align="absmiddle"/> &nbsp; **Programming Using Java** — Infosys Springboard
<br/>
<img src="https://api.iconify.design/mdi/cog-outline.svg?color=CA8A04" width="16" height="16" align="absmiddle"/> &nbsp; **Software Engineering &amp; Agile SD**
<br/>
<img src="https://api.iconify.design/mdi/language-python.svg?color=CA8A04" width="16" height="16" align="absmiddle"/> &nbsp; **Python, JavaScript, HTML5, CSS3**

</td>
<td width="50%" bgcolor="#0F172A" cellpadding="24" valign="top">

**Additional Learning**

<br/>

<img src="https://api.iconify.design/mdi/robot-outline.svg?color=CA8A04" width="16" height="16" align="absmiddle"/> &nbsp; **AI Upskilling** — Qualcomm Academy
<br/>
<img src="https://api.iconify.design/mdi/cloud-outline.svg?color=CA8A04" width="16" height="16" align="absmiddle"/> &nbsp; **Salesforce Developer** — Virtual Internship

</td>
</tr>
</table>

<!-- ─── WAVE DIVIDER ─── -->
<svg width="100%" height="36" viewBox="0 0 1200 36" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="presentation">
  <path d="M0,18 C200,4 400,32 600,18 C800,4 1000,32 1200,18" stroke="url(#waveA)" stroke-width="2" fill="none"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════════
     08 · CONNECT
     ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" height="70" viewBox="0 0 900 70" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Section 08 Connect">
  <defs>
    <linearGradient id="secH" x1="0%" x2="100%">
      <stop offset="0%" stop-color="#0F9D8A"/>
      <stop offset="100%" stop-color="#06B6D4"/>
    </linearGradient>
  </defs>
  <circle cx="30" cy="38" r="20" fill="url(#secH)"/>
  <text x="30" y="45" text-anchor="middle" fill="#0B1120" font-family="'Segoe UI',sans-serif" font-size="18" font-weight="900">08</text>
  <text x="68" y="48" fill="#F8FAFC" font-family="'Segoe UI',sans-serif" font-size="26" font-weight="800" letter-spacing="3">LET'S CONNECT</text>
  <line x1="340" y1="38" x2="900" y2="38" stroke="url(#secH)" stroke-width="2" stroke-opacity="0.35"/>
</svg>

<br/>

**Open to Full Stack and Java Developer opportunities.**

<br/><br/>

<a href="https://www.linkedin.com/in/sherishivaji2774/">
  <img src="https://img.shields.io/badge/LINKEDIN-PROFESSIONAL%20NETWORK-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:shivajisheri@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-CONTACT%20ME-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/SHERISHIVAJI">
  <img src="https://img.shields.io/badge/GITHUB-FOLLOW-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=1000&color=06B6D4&center=true&vCenter=true&width=600&lines=Thanks+for+visiting!;Let's+build+something+useful+together." alt="Closing message"/>

</div>

<!-- ─── FOOTER WAVE ─── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=140&color=gradient&customColorList=0,2,2,30,30&section=footer" alt="Footer"/>
