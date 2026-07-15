<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 420" width="1200" height="420">
  <defs>
    <radialGradient id="bg" cx="50%" cy="0%" r="100%">
      <stop offset="0%" stop-color="#3c4a2e"/>
      <stop offset="45%" stop-color="#344128"/>
      <stop offset="100%" stop-color="#212a16"/>
    </radialGradient>
    <linearGradient id="htmlLayer" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#F4EDDD" stop-opacity="0.14"/>
      <stop offset="100%" stop-color="#F4EDDD" stop-opacity="0.05"/>
    </linearGradient>
    <linearGradient id="cssLayer" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#E3C888" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#C9A24B" stop-opacity="0.16"/>
    </linearGradient>
    <linearGradient id="jsLayer" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#F4EDDD" stop-opacity="0.22"/>
      <stop offset="100%" stop-color="#F4EDDD" stop-opacity="0.10"/>
    </linearGradient>
    <filter id="soft" x="-40%" y="-40%" width="180%" height="180%">
      <feDropShadow dx="0" dy="18" stdDeviation="22" flood-color="#000000" flood-opacity="0.35"/>
    </filter>
  </defs>

  <rect width="1200" height="420" fill="url(#bg)"/>

  <!-- faint grid texture -->
  <g opacity="0.06" stroke="#F4EDDD" stroke-width="1">
    <line x1="0" y1="60" x2="1200" y2="60"/>
    <line x1="0" y1="360" x2="1200" y2="360"/>
    <line x1="120" y1="0" x2="120" y2="420"/>
    <line x1="1080" y1="0" x2="1080" y2="420"/>
  </g>

  <!-- eyebrow -->
  <text x="90" y="120" font-family="Consolas, 'Courier New', monospace" font-size="15" letter-spacing="2" fill="#E3C888" opacity="0.9">~/abdul-basit-odho — karachi, pk</text>

  <!-- title -->
  <text x="88" y="188" font-family="Georgia, 'Times New Roman', serif" font-size="58" fill="#F4EDDD">Abdul Basit Odho</text>

  <!-- subtitle -->
  <text x="90" y="228" font-family="Georgia, 'Times New Roman', serif" font-style="italic" font-size="24" fill="#E3C888">Frontend Developer, building in layers.</text>

  <!-- description -->
  <text x="90" y="270" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="15" fill="#F4EDDD" opacity="0.7">React · Next.js · TypeScript · Firebase · WordPress</text>

  <!-- stack of exploded layers, isometric-style, right side -->
  <g transform="translate(760,60) rotate(-6)" filter="url(#soft)">
    <rect x="0" y="140" width="330" height="150" rx="10" fill="url(#htmlLayer)" stroke="#F4EDDD" stroke-opacity="0.25"/>
    <text x="24" y="270" font-family="Consolas, 'Courier New', monospace" font-size="14" fill="#F4EDDD" opacity="0.85">index.html</text>

    <rect x="34" y="90" width="330" height="150" rx="10" fill="url(#cssLayer)" stroke="#E3C888" stroke-opacity="0.4"/>
    <text x="58" y="220" font-family="Consolas, 'Courier New', monospace" font-size="14" fill="#3a2f10">style.css</text>

    <rect x="68" y="40" width="330" height="150" rx="10" fill="url(#jsLayer)" stroke="#F4EDDD" stroke-opacity="0.35"/>
    <text x="92" y="170" font-family="Consolas, 'Courier New', monospace" font-size="14" fill="#F4EDDD">app.jsx</text>
  </g>

  <!-- bottom hairline -->
  <line x1="90" y1="360" x2="1110" y2="360" stroke="#F4EDDD" stroke-opacity="0.15"/>
  <text x="90" y="392" font-family="Consolas, 'Courier New', monospace" font-size="13" fill="#F4EDDD" opacity="0.55">available for freelance work</text>
</svg>
