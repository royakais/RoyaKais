<div align="center">

<svg width="900" height="280" viewBox="0 0 900 280" fill="none" xmlns="http://www.w3.org/2000/svg">
  <style>
    .name { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; font-size: 46px; font-weight: 800; fill: #FFFFFF; letter-spacing: -1.2px; }
    .role { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; font-size: 17px; font-weight: 500; fill: #CBD5E1; }
    .pill-text { font-family: "SFMono-Regular", Consolas, monospace; font-size: 12px; font-weight: 600; fill: #E2E8F0; }
    .badge-text { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; font-size: 11px; font-weight: 700; fill: #34D399; letter-spacing: 0.8px; }
    .mono { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; font-size: 28px; font-weight: 800; fill: #FFFFFF; }
    .float1 { animation: drift1 7s ease-in-out infinite; }
    .float2 { animation: drift2 9s ease-in-out infinite; }
    @keyframes drift1 { 0%, 100% { transform: translate(0px, 0px); } 50% { transform: translate(18px, -14px); } }
    @keyframes drift2 { 0%, 100% { transform: translate(0px, 0px); } 50% { transform: translate(-20px, 12px); } }
  </style>

  <defs>
    <clipPath id="canvas">
      <rect width="900" height="280" rx="20"/>
    </clipPath>

    <linearGradient id="baseBg" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#070913"/>
      <stop offset="100%" stop-color="#0F172A"/>
    </linearGradient>

    <radialGradient id="orbCyan" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orbViolet" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#8B5CF6" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#8B5CF6" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="orbPink" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#EC4899" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#EC4899" stop-opacity="0"/>
    </radialGradient>

    <linearGradient id="glassFill" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.08"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0.02"/>
    </linearGradient>
    <linearGradient id="glassStroke" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.28"/>
      <stop offset="50%" stop-color="#38BDF8" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#C084FC" stop-opacity="0.3"/>
    </linearGradient>
    <linearGradient id="rkGrad" x1="0" y1="0" x2="64" y2="64" gradientUnits="userSpaceOnUse">
      <stop offset="0%" stop-color="#38BDF8"/>
      <stop offset="100%" stop-color="#818CF8"/>
    </linearGradient>
  </defs>

  <g clip-path="url(#canvas)">
    <rect width="900" height="280" fill="url(#baseBg)"/>

    <circle cx="160" cy="60" r="220" fill="url(#orbViolet)" class="float1"/>
    <circle cx="760" cy="210" r="240" fill="url(#orbCyan)" class="float2"/>
    <circle cx="520" cy="40" r="180" fill="url(#orbPink)" class="float1"/>

    <pattern id="dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#FFFFFF" fill-opacity="0.08"/>
    </pattern>
    <rect width="900" height="280" fill="url(#dots)"/>

    <rect x="24" y="24" width="852" height="232" rx="16" fill="url(#glassFill)" stroke="url(#glassStroke)" stroke-width="1.5"/>

    <g transform="translate(64, 62)">
      <rect width="64" height="64" rx="16" fill="url(#rkGrad)"/>
      <text x="32" y="42" text-anchor="middle" class="mono">RK</text>
    </g>

    <g transform="translate(620, 62)">
      <rect width="216" height="32" rx="16" fill="#10B981" fill-opacity="0.14" stroke="#10B981" stroke-opacity="0.4"/>
      <circle cx="18" cy="16" r="4.5" fill="#34D399"/>
      <text x="32" y="20" class="badge-text">OPEN TO SWE &amp; DATA ROLES</text>
    </g>

    <g transform="translate(64, 172)">
      <text y="0" class="name">Roya Kais</text>
      <text y="30" class="role">Software Engineer · Full-Stack Systems, Data &amp; Machine Learning</text>
    </g>

    <g transform="translate(534, 182)">
      <rect x="0" y="0" width="94" height="28" rx="8" fill="#FFFFFF" fill-opacity="0.07" stroke="#FFFFFF" stroke-opacity="0.15"/>
      <text x="47" y="18" text-anchor="middle" class="pill-text">Full-Stack</text>

      <rect x="104" y="0" width="90" height="28" rx="8" fill="#FFFFFF" fill-opacity="0.07" stroke="#FFFFFF" stroke-opacity="0.15"/>
      <text x="149" y="18" text-anchor="middle" class="pill-text">ML &amp; Data</text>

      <rect x="204" y="0" width="98" height="28" rx="8" fill="#FFFFFF" fill-opacity="0.07" stroke="#FFFFFF" stroke-opacity="0.15"/>
      <text x="253" y="18" text-anchor="middle" class="pill-text">USEK '26</text>
    </g>
  </g>
</svg>

  <br /><br />

  <a href="https://linkedin.com/in/royakais">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:royakais@yahoo.com">
    <img src="https://img.shields.io/badge/Email-18181B?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" />
  </a>
  <a href="https://royakais-portfolio.vercel.app">
    <img src="https://img.shields.io/badge/Open_to-Junior_SWE_%26_Data_Roles-10B981?style=for-the-badge" alt="Open to work" />
  </a>

  <br /><br />

  <p>
    Final-year Computer Science student at <strong>Holy Spirit University of Kaslik (USEK)</strong>, graduating December 2026.<br />
    I build things that actually run: relational databases, typed full-stack web apps, and ML models taken from raw data to live products.<br />
    <em>Currently building <strong>HomeFit</strong> (FYP) and diving deeper into Java, the JVM, and DSA.</em>
  </p>

</div>

---

### `01` Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/royakais/F1_prediction"><strong>🏎️ F1 2026 Prediction Lab</strong></a> · <a href="https://f1-prediction-lab8.onrender.com/">Live Demo</a><br />
      <sub>End-to-end ML system predicting Formula 1 finishing positions, served by a Flask API to an interactive site. <a href="https://github.com/royakais/MachineLearning-F1">Pipeline →</a></sub><br /><br />
      <code>Python</code> <code>scikit-learn</code> <code>Pandas</code> <code>Flask</code>
    </td>
    <td width="50%" valign="top">
      <strong>💪 HomeFit</strong> · <em>In Progress</em><br />
      <sub>No-equipment home-workout mobile app with machine-learning features built on top of guided training plans.</sub><br /><br />
      <code>Mobile</code> <code>Machine Learning</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/royakais/BNF-Interpreter"><strong>🌳 BNF Interpreter</strong></a><br />
      <sub>A custom language from a BNF grammar: lexer, recursive-descent parser, AST, and evaluator with a GUI syntax tree visualizer.</sub><br /><br />
      <code>Java</code> <code>Swing</code> <code>Compilers</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/royakais/DBMS-VeeCoffeeShop"><strong>☕ Vee Coffee Shop DBMS</strong></a><br />
      <sub>Relational database architecture for a 16-branch coffee chain, engineered from ER diagram to normalized schema.</sub><br /><br />
      <code>SQL</code> <code>Database Design</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/royakais/GuessTheCapital"><strong>🌍 Guess the Capital</strong></a><br />
      <sub>Keyboard-first desktop quiz featuring 96 countries wrapped in a timed, animated dark UI.</sub><br /><br />
      <code>Java</code> <code>Swing</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/royakais/royakais-portfolio"><strong>🌐 Personal Portfolio</strong></a><br />
      <sub>My personal corner on the internet showcasing projects, experience, and writing.</sub><br /><br />
      <code>Next.js</code> <code>TypeScript</code> <code>Tailwind</code>
    </td>
  </tr>
</table>

---

### `02` Tech Stack

<div align="center">

  **Languages & Core**  
  <img src="https://skillicons.dev/icons?i=python,java,ts,js,cpp,cs" alt="Languages" />

  **Web & Backend**  
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,flask,fastapi" alt="Web & Backend" />

  **Data, ML & Infrastructure**  
  <img src="https://skillicons.dev/icons?i=sklearn,pytorch,postgres,mysql,prisma,git" alt="Data & DevOps" />

  <br /><br />
  <sub><strong>Also experienced with:</strong> Pandas · NumPy · Matplotlib · Power BI · R · GitHub Actions</sub>

</div>

---

<div align="center">
  <sub>
    Open to <strong>junior software engineering</strong> and <strong>data roles</strong> (Lebanon & Remote).<br />
    Let's connect on <a href="https://linkedin.com/in/royakais">LinkedIn</a> or drop an email at <a href="mailto:royakais@yahoo.com">royakais@yahoo.com</a>.
  </sub>
</div>
