<div align="center">

<!-- Futuristic Animated SVG Accent: Neural Network / Data Cloud Flow -->
<svg width="100%" height="90" viewBox="0 0 800 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#38BDF8" stop-opacity="0.2"/>
      <stop offset="50%" stop-color="#818CF8" stop-opacity="1"/>
      <stop offset="100%" stop-color="#38BDF8" stop-opacity="0.2"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background subtle track line -->
  <line x1="100" y1="45" x2="700" y2="45" stroke="#1E293B" stroke-width="3" stroke-dasharray="6 6"/>

  <!-- Animated data stream pulse moving across -->
  <line x1="100" y1="45" x2="700" y2="45" stroke="url(#grad)" stroke-width="4" stroke-dasharray="120 480" filter="url(#glow)">
    <animate attributeName="stroke-dashoffset" values="600;0" dur="4s" repeatCount="indefinite"/>
  </line>

  <!-- Node Circles representing Database/Cloud/AI hubs -->
  <circle cx="150" cy="45" r="6" fill="#38BDF8" filter="url(#glow)"/>
  <circle cx="300" cy="45" r="8" fill="#818CF8" filter="url(#glow)"/>
  <circle cx="450" cy="45" r="6" fill="#38BDF8" filter="url(#glow)"/>
  <circle cx="600" cy="45" r="8" fill="#818CF8" filter="url(#glow)"/>

  <!-- Pulsing rings around center nodes -->
  <circle cx="300" cy="45" r="14" fill="none" stroke="#818CF8" stroke-width="1.5" opacity="0.6">
    <animate attributeName="r" values="8;22" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="45" r="14" fill="none" stroke="#38BDF8" stroke-width="1.5" opacity="0.6">
    <animate attributeName="r" values="8;22" dur="2s" begin="1s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0" dur="2s" begin="1s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>
