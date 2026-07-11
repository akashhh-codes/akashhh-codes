<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="1200" height="320" font-family="'Segoe UI', Helvetica, Arial, sans-serif">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#080B16"/>
      <stop offset="0.55" stop-color="#0B0F22"/>
      <stop offset="1" stop-color="#0E1330"/>
    </linearGradient>
    <linearGradient id="nameGrad" x1="60" y1="0" x2="640" y2="0" gradientUnits="userSpaceOnUse">
      <stop offset="0" stop-color="#8B6CFF"/>
      <stop offset="0.5" stop-color="#4C8DFF"/>
      <stop offset="1" stop-color="#2DD4BF"/>
    </linearGradient>
    <radialGradient id="glowV" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#8B6CFF" stop-opacity="0.22"/>
      <stop offset="1" stop-color="#8B6CFF" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowT" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0" stop-color="#2DD4BF" stop-opacity="0.20"/>
      <stop offset="1" stop-color="#2DD4BF" stop-opacity="0"/>
    </radialGradient>
    <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#1B2138" stroke-width="1" opacity="0.5"/>
    </pattern>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>
  <rect width="1200" height="320" fill="url(#grid)"/>
  <ellipse cx="960" cy="150" rx="320" ry="240" fill="url(#glowV)"/>
  <ellipse cx="1010" cy="240" rx="260" ry="200" fill="url(#glowT)"/>

  <!-- feature-space data points (right) -->
  <g filter="url(#soft)">
  <circle cx="1045.8" cy="194.1" r="2.2" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="723.4" to="1045.8" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="250.0" to="194.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="6.3s" begin="2.33s" repeatCount="indefinite"/>
  </circle>
  <circle cx="887.9" cy="246.7" r="3.4" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="902.8" to="887.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="87.4" to="246.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.2s" begin="0.24s" repeatCount="indefinite"/>
  </circle>
  <circle cx="901.8" cy="249.9" r="3.5" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="1004.3" to="901.8" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="285.4" to="249.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.6s" begin="1.59s" repeatCount="indefinite"/>
  </circle>
  <circle cx="966.2" cy="151.6" r="2.3" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="840.5" to="966.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="60.4" to="151.6" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.2s" begin="1.23s" repeatCount="indefinite"/>
  </circle>
  <circle cx="902.7" cy="269.2" r="3.4" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="1009.9" to="902.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="124.3" to="269.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.2s" begin="0.25s" repeatCount="indefinite"/>
  </circle>
  <circle cx="871.3" cy="106.9" r="3.2" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="957.9" to="871.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="237.6" to="106.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.7s" begin="3.69s" repeatCount="indefinite"/>
  </circle>
  <circle cx="992.3" cy="254.2" r="3.5" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="1039.0" to="992.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="88.3" to="254.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="6.1s" begin="2.1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1006.0" cy="177.1" r="3.1" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="1175.4" to="1006.0" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="53.1" to="177.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.0s" begin="3.03s" repeatCount="indefinite"/>
  </circle>
  <circle cx="943.1" cy="119.7" r="3.5" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="1166.6" to="943.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="41.7" to="119.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.2s" begin="3.16s" repeatCount="indefinite"/>
  </circle>
  <circle cx="991.1" cy="231.7" r="2.2" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="940.9" to="991.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="243.1" to="231.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.4s" begin="0.37s" repeatCount="indefinite"/>
  </circle>
  <circle cx="959.1" cy="212.5" r="3.7" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="729.4" to="959.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="216.4" to="212.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="8.0s" begin="3.97s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1002.0" cy="237.8" r="3.2" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="1024.3" to="1002.0" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="26.3" to="237.8" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.7s" begin="0.67s" repeatCount="indefinite"/>
  </circle>
  <circle cx="876.9" cy="136.0" r="3.0" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="839.4" to="876.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="226.7" to="136.0" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.7s" begin="3.67s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1045.7" cy="222.8" r="4.1" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="966.5" to="1045.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="267.3" to="222.8" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.5s" begin="3.46s" repeatCount="indefinite"/>
  </circle>
  <circle cx="992.3" cy="148.3" r="2.6" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="1031.1" to="992.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="126.5" to="148.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.3s" begin="0.33s" repeatCount="indefinite"/>
  </circle>
  <circle cx="908.3" cy="161.1" r="2.7" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="935.2" to="908.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="185.0" to="161.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.0s" begin="0.02s" repeatCount="indefinite"/>
  </circle>
  <circle cx="962.1" cy="195.5" r="4.2" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="854.5" to="962.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="55.1" to="195.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.8s" begin="3.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="880.5" cy="226.9" r="4.3" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="1136.3" to="880.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="238.4" to="226.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.2s" begin="3.19s" repeatCount="indefinite"/>
  </circle>
  <circle cx="979.7" cy="225.3" r="2.5" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="933.5" to="979.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="132.1" to="225.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.9s" begin="3.94s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1028.1" cy="231.5" r="2.4" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="725.5" to="1028.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="20.1" to="231.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.4s" begin="0.41s" repeatCount="indefinite"/>
  </circle>
  <circle cx="999.9" cy="197.1" r="3.6" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="800.9" to="999.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="125.3" to="197.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.8s" begin="3.82s" repeatCount="indefinite"/>
  </circle>
  <circle cx="874.2" cy="246.2" r="3.2" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="1111.7" to="874.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="298.1" to="246.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.9s" begin="1.94s" repeatCount="indefinite"/>
  </circle>
  <circle cx="941.3" cy="176.7" r="3.8" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="1059.1" to="941.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="154.0" to="176.7" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="6.1s" begin="2.07s" repeatCount="indefinite"/>
  </circle>
  <circle cx="950.5" cy="122.0" r="2.1" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="771.1" to="950.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="172.1" to="122.0" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="6.1s" begin="2.11s" repeatCount="indefinite"/>
  </circle>
  <circle cx="915.5" cy="203.2" r="2.4" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="826.6" to="915.5" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="122.7" to="203.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.1s" begin="3.09s" repeatCount="indefinite"/>
  </circle>
  <circle cx="847.9" cy="226.1" r="4.0" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="1008.7" to="847.9" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="191.7" to="226.1" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="7.0s" begin="3.03s" repeatCount="indefinite"/>
  </circle>
  <circle cx="926.4" cy="82.6" r="3.3" fill="#2DD4BF" opacity="0.9">
    <animate attributeName="cx" from="1058.8" to="926.4" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="83.5" to="82.6" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.4s" begin="1.42s" repeatCount="indefinite"/>
  </circle>
  <circle cx="965.6" cy="131.4" r="3.6" fill="#FFB454" opacity="0.9">
    <animate attributeName="cx" from="929.0" to="965.6" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="74.2" to="131.4" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.4s" begin="1.38s" repeatCount="indefinite"/>
  </circle>
  <circle cx="941.3" cy="231.2" r="2.6" fill="#8B6CFF" opacity="0.9">
    <animate attributeName="cx" from="876.8" to="941.3" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="81.7" to="231.2" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="4.8s" begin="0.79s" repeatCount="indefinite"/>
  </circle>
  <circle cx="836.0" cy="141.8" r="4.4" fill="#4C8DFF" opacity="0.9">
    <animate attributeName="cx" from="996.0" to="836.0" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="cy" from="20.5" to="141.8" dur="1.8s" begin="0.1s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    <animate attributeName="opacity" values="0.45;1;0.6;1;0.5" dur="5.4s" begin="1.38s" repeatCount="indefinite"/>
  </circle>
  </g>

  <!-- text block (fade in) -->
  <g opacity="0">
    <animate attributeName="opacity" from="0" to="1" dur="0.9s" begin="0.2s" fill="freeze"/>

    <text x="70" y="116" font-family="ui-monospace,'Cascadia Code','Courier New',monospace" font-size="15" letter-spacing="4" fill="#6E7693">DATA SCIENCE · MACHINE LEARNING · COMPUTER VISION</text>

    <line x1="70" y1="132" x2="70" y2="132" stroke="#2DD4BF" stroke-width="2">
      <animate attributeName="x2" from="70" to="150" dur="0.7s" begin="0.6s" fill="freeze" calcMode="spline" keyTimes="0;1" keySplines="0.2 0.7 0.2 1"/>
    </line>

    <text x="66" y="200" font-size="66" font-weight="700" letter-spacing="-1.5" fill="url(#nameGrad)">Akash Chauhan</text>

    <text x="70" y="242" font-size="21" fill="#AAB0C8">BSc (Hons.) Data Science &amp; AI · IIT Guwahati</text>

    <!-- status pill -->
    <g transform="translate(70,268)">
      <rect x="0" y="0" rx="13" ry="13" width="214" height="27" fill="#101424" stroke="#232A45"/>
      <circle cx="18" cy="13.5" r="4.5" fill="#2DD4BF">
        <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
        <animate attributeName="r" values="4.5;5.5;4.5" dur="2s" repeatCount="indefinite"/>
      </circle>
      <text x="33" y="18" font-family="ui-monospace,'Courier New',monospace" font-size="12.5" fill="#AAB0C8">Open to internships</text>
    </g>
  </g>
</svg>
