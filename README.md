<div align="center">
  <svg xmlns="http://www.w3.org/2000/svg" width="760" height="120" viewBox="0 0 760 120" role="img" aria-label="Glitch text: Ellissea Montes">
    <style>
      .g-text { font: 700 48px/1 "Segoe UI", Roboto, system-ui, -apple-system, "Helvetica Neue", Arial; letter-spacing: 1px; }
    </style>

    <!-- base text -->
    <text class="g-text" x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" fill="#111">
      Ellissea Montes
    </text>

    <!-- red layer (glitch) -->
    <text class="g-text" x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" fill="#E22FE4" opacity="0.85">
      Ellissea Montes
      <!-- horizontal jitter -->
      <animateTransform attributeName="transform"
                        type="translate"
                        values="0 0; -6 0; 6 0; -3 0; 0 0"
                        keyTimes="0;0.2;0.5;0.8;1"
                        dur="1.6s"
                        repeatCount="indefinite" />
      <!-- quick flashes -->
      <animate attributeName="opacity"
               values="0;1;0.6;1;0"
               keyTimes="0;0.15;0.4;0.7;1"
               dur="1.6s"
               repeatCount="indefinite"/>
    </text>

    <!-- cyan layer (glitch) -->
    <text class="g-text" x="50%" y="55%" dominant-baseline="middle" text-anchor="middle" fill="#00E5FF" opacity="0.75">
      Ellissea Montes
      <animateTransform attributeName="transform"
                        type="translate"
                        values="0 0; 6 0; -6 0; 3 0; 0 0"
                        keyTimes="0;0.18;0.45;0.75;1"
                        dur="1.4s"
                        repeatCount="indefinite" />
      <animate attributeName="opacity"
               values="0;0.9;0.5;0.9;0"
               keyTimes="0;0.12;0.5;0.78;1"
               dur="1.4s"
               repeatCount="indefinite"/>
    </text>

    <!-- small horizontal slices that slide (extra glitch accents) -->
    <g fill="#111" font="700 28px/1 'Segoe UI', Roboto, system-ui">
      <text x="50%" y="40%" text-anchor="middle" fill="#111" opacity="0.9">Ellissea</text>
      <text x="50%" y="40%" text-anchor="middle" fill="#E22FE4" opacity="0.7">
        Ellissea
        <animateTransform attributeName="transform" type="translate" values="0 0; -18 0; 0 0" dur="2.5s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite"/>
      </text>

      <text x="50%" y="70%" text-anchor="middle" fill="#111" opacity="0.9">Montes</text>
      <text x="50%" y="70%" text-anchor="middle" fill="#00E5FF" opacity="0.6">
        Montes
        <animateTransform attributeName="transform" type="translate" values="0 0; 18 0; 0 0" dur="2.2s" repeatCount="indefinite"/>
        <animate attributeName="opacity" values="0;1;0" dur="2.2s" repeatCount="indefinite"/>
      </text>
    </g>
  </svg>
</div>
