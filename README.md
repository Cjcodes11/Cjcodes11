<svg xmlns="http://www.w3.org/2000/svg" width="1500" height="500" viewBox="0 0 1500 500">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#050b14"/>
      <stop offset="0.6" stop-color="#0a1628"/>
      <stop offset="1" stop-color="#06201f"/>
    </linearGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#12304a" stroke-width="1"/>
    </pattern>
    <radialGradient id="glow" cx="0.78" cy="0.5" r="0.35">
      <stop offset="0" stop-color="#00e5a0" stop-opacity="0.28"/>
      <stop offset="1" stop-color="#00e5a0" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="nameGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff"/>
      <stop offset="1" stop-color="#7fffd4"/>
    </linearGradient>
    <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="1500" height="500" fill="url(#bg)"/>
  <rect width="1500" height="500" fill="url(#grid)" opacity="0.6"/>
  <rect width="1500" height="500" fill="url(#glow)"/>

  <!-- binary rain, faint -->
  <g font-family="Consolas, 'DejaVu Sans Mono', monospace" font-size="16" fill="#00e5a0" opacity="0.10">
    <text x="900" y="40">01001100 10110010 01110011</text>
    <text x="1180" y="80">11010110 00101101</text>
    <text x="960" y="460">10011010 01101100 11100101</text>
    <text x="1250" y="480">0110 1001 1100</text>
    <text x="60" y="470">01000011 01000001 01001100 01000101 01000010</text>
  </g>

  <!-- circuit traces -->
  <g fill="none" stroke="#00e5a0" stroke-width="2" opacity="0.45">
    <path d="M1500 120 H1380 L1340 160 H1260"/>
    <path d="M1500 380 H1400 L1360 340 H1270"/>
    <path d="M1170 0 V60 L1130 100 V130"/>
    <path d="M1170 500 V440 L1130 400 V370"/>
    <path d="M880 250 H960"/>
  </g>
  <g fill="#00e5a0" opacity="0.8">
    <circle cx="1260" cy="160" r="5"/>
    <circle cx="1270" cy="340" r="5"/>
    <circle cx="1130" cy="130" r="5"/>
    <circle cx="1130" cy="370" r="5"/>
    <circle cx="880" cy="250" r="5"/>
  </g>

  <!-- hex ring -->
  <g transform="translate(1150 250)">
    <polygon points="0,-170 147,-85 147,85 0,170 -147,85 -147,-85" fill="none" stroke="#1f6f8b" stroke-width="2" stroke-dasharray="10 8" opacity="0.7"/>
    <polygon points="0,-135 117,-67 117,67 0,135 -117,67 -117,-67" fill="none" stroke="#00e5a0" stroke-width="1.5" opacity="0.35"/>

    <!-- shield -->
    <g filter="url(#soft)">
      <path d="M0 -100 L80 -70 V5 C80 60 45 95 0 115 C-45 95 -80 60 -80 5 V-70 Z"
            fill="#0b2233" stroke="#00e5a0" stroke-width="4"/>
    </g>
    <!-- lock -->
    <path d="M-22 -10 V-30 A22 22 0 0 1 22 -30 V-10" fill="none" stroke="#7fffd4" stroke-width="7" stroke-linecap="round"/>
    <rect x="-36" y="-12" width="72" height="58" rx="8" fill="#00e5a0"/>
    <circle cx="0" cy="10" r="8" fill="#0b2233"/>
    <rect x="-3.5" y="12" width="7" height="18" rx="3" fill="#0b2233"/>
  </g>

  <!-- text block -->
  <g font-family="Consolas, 'DejaVu Sans Mono', monospace">
    <text x="90" y="150" font-size="26" fill="#00e5a0">&gt; whoami<tspan fill="#7fffd4">_</tspan></text>
    <text x="86" y="265" font-size="104" font-weight="700" fill="url(#nameGrad)" letter-spacing="2"
          font-family="'Segoe UI', 'DejaVu Sans', Arial, sans-serif">Caleb Abreu</text>
    <rect x="90" y="292" width="140" height="4" fill="#00e5a0"/>
    <text x="90" y="350" font-size="28" fill="#c9d6e3">Cybersecurity  ·  Web Dev  ·  UX Design</text>
    <text x="90" y="400" font-size="20" fill="#5f7a91">[ secure_by_design = true ]</text>
  </g>
</svg>


## About Me
Hi there I'm Caleb👋

Welcome to my GitHub profile! I'm a developer and designer passionate about building clean web experiences, exploring cybersecurity, and sharpening my technical skills.

## 💻 Coding Languages & Tools
* **Languages:** Python, HTML
* **Design & Prototyping:** Figma, Adobe Illustrator, Adobe InDesign
* **Systems & Security:** Linux (Ubuntu/Kali), Git, VirtualBox

## 🌱 Current Projects
* **System Hardening AI Agent:** A tool that combines hardening practices and networking concepts.
* **Networking Python packet Analyzer:** Combining Wireshark, a program that captures packet data.
* **Linux Command Prompt Auditing:** Using the Command Prompt, I audit systems for vulnerabilities.

## Passions
* **Music:** Playing acoustic arrangements and exploring alternative tunings.
* **Outdoors** I enjoy hiking in the Colorado Rockies

**Contact Me
Phone: 719-678-1305
Email: Cjoshuaabreu@gmail.com

