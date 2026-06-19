# CEMENT
A cement is a binder used for construction that sets, hardens, and adheres to other materials to bind them together. Cement is seldom used on its own, but rather to bind sand and gravel (aggregate) together. Cement mixed with fine aggregate produces mortar for masonry, or with sand and gravel, produces concrete.

## Manufacturing of Cement

### Dry Process

<div class="mermaid">
flowchart TD

    A[Calcareous Material<br/>Limestone] --> B[Crushing]
    B --> C[Fine Grinding in Ball Mills<br/>and Tube Mills]
    C --> D[Storage]

    E[Argillaceous Material<br/>Clay] --> F[Washing]
    F --> G[Fine Grinding in Ball Mills<br/>and Tube Mills]
    G --> H[Storage]

    D --> I[Mixing in Correct Proportion]
    H --> I

    I --> J[Storage Tank for Raw Mix]
    J --> K[Rotary Kiln]

    L[Coal Dust] --> K

    K --> M[Formation of Clinkers]
    M --> N[Coolers]
    N --> O[Grinding of Clinkers in Ball Mills<br/>and Tube Mills]

    P[Gypsum 2 to 3%] --> O

    O --> Q[Storage in Silos]
    Q --> R[Weighing & Packing in Bags]
    R --> S[Distribution]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

### Wet Process

<div class="mermaid">
flowchart TD

    A[Calcareous Materials<br/>Limestone/Marl]
    B[Preliminary Crushing<br/>Crushers-Roll Mills]
    C[Elevators<br/>Storage Bins]

    D[Argillaceous Materials<br/>Clay/Shale]
    E[Washing<br/>Wash Mills]
    F[Elevators<br/>Storage Tanks]

    W[Water]

    A --> B
    B --> C

    D --> E
    E --> F

    C --> G[Hoppers]
    F --> G

    G --> H[Wet Grinding<br/>Ball Mills]
    W --> H

    H --> I[Raw Slurry]

    J[Lime Slurry]
    K[Clay Slurry]

    I --> L[Elevators]
    J --> L
    K --> L

    L --> M[Correction Silos]
    M --> N[Rotary Kiln]

    O[Fuel Coal]
    P[Crushing and Grinding<br/>Ball Mills]
    Q[Pulverized Coal]

    O --> P
    P --> Q
    Q --> N

    N --> R[Clinker]

    S[Gypsum]
    T[Gypsum Hoppers]

    S --> T

    R --> U[Clinker Grinding<br/>Tube Mills]
    T --> U

    U --> V[Elevators<br/>Cement Silos]
    V --> X[Weighing and Packing]
    X --> Y[Supply]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## IS 10262 – Water Cement Ratio vs Strength

<svg width="900" height="620" viewBox="0 0 900 620" xmlns="http://www.w3.org/2000/svg">
  <style>
    svg { max-width: 100%; height: auto; }
    text { font-family: Arial, sans-serif; fill: #111; }
    .grid { stroke: #999; stroke-width: 1; }
    .axis { stroke: #000; stroke-width: 2; }
    .curve { fill: none; stroke: #111; stroke-width: 3; }
    .label { font-size: 16px; font-weight: bold; }
    .small { font-size: 14px; }
    @media (max-width: 600px) {
      text { font-size: 12px; }
      .label { font-size: 13px; }
      .small { font-size: 11px; }
    }
  </style>

  <rect width="100%" height="100%" fill="white"/>

  <text x="450" y="35" text-anchor="middle" font-size="22" font-weight="bold">
    IS 10262 – Free Water-Cement Ratio vs 28-Day Compressive Strength
  </text>

  <!-- Plot area -->
  <rect x="110" y="70" width="650" height="400" fill="none" stroke="#000" stroke-width="2"/>

  <!-- Grid vertical x = 0.25 to 0.65 -->
  <line class="grid" x1="110" y1="70" x2="110" y2="470"/>
  <line class="grid" x1="191.25" y1="70" x2="191.25" y2="470"/>
  <line class="grid" x1="272.5" y1="70" x2="272.5" y2="470"/>
  <line class="grid" x1="353.75" y1="70" x2="353.75" y2="470"/>
  <line class="grid" x1="435" y1="70" x2="435" y2="470"/>
  <line class="grid" x1="516.25" y1="70" x2="516.25" y2="470"/>
  <line class="grid" x1="597.5" y1="70" x2="597.5" y2="470"/>
  <line class="grid" x1="678.75" y1="70" x2="678.75" y2="470"/>
  <line class="grid" x1="760" y1="70" x2="760" y2="470"/>

  <!-- Grid horizontal y = 0 to 80 -->
  <line class="grid" x1="110" y1="470" x2="760" y2="470"/>
  <line class="grid" x1="110" y1="420" x2="760" y2="420"/>
  <line class="grid" x1="110" y1="370" x2="760" y2="370"/>
  <line class="grid" x1="110" y1="320" x2="760" y2="320"/>
  <line class="grid" x1="110" y1="270" x2="760" y2="270"/>
  <line class="grid" x1="110" y1="220" x2="760" y2="220"/>
  <line class="grid" x1="110" y1="170" x2="760" y2="170"/>
  <line class="grid" x1="110" y1="120" x2="760" y2="120"/>
  <line class="grid" x1="110" y1="70" x2="760" y2="70"/>

  <!-- Axis labels -->
  <text x="435" y="530" text-anchor="middle" font-size="17">
    Free Water-Cement Ratio
  </text>

  <text x="35" y="270" text-anchor="middle" font-size="17" transform="rotate(-90 35 270)">
    28-Day Compressive Strength of Concrete, N/mm²
  </text>

  <!-- X values -->
  <text x="110" y="495" text-anchor="middle" class="small">0.25</text>
  <text x="191.25" y="495" text-anchor="middle" class="small">0.30</text>
  <text x="272.5" y="495" text-anchor="middle" class="small">0.35</text>
  <text x="353.75" y="495" text-anchor="middle" class="small">0.40</text>
  <text x="435" y="495" text-anchor="middle" class="small">0.45</text>
  <text x="516.25" y="495" text-anchor="middle" class="small">0.50</text>
  <text x="597.5" y="495" text-anchor="middle" class="small">0.55</text>
  <text x="678.75" y="495" text-anchor="middle" class="small">0.60</text>
  <text x="760" y="495" text-anchor="middle" class="small">0.65</text>

  <!-- Y values -->
  <text x="90" y="475" text-anchor="end" class="small">0</text>
  <text x="90" y="425" text-anchor="end" class="small">10</text>
  <text x="90" y="375" text-anchor="end" class="small">20</text>
  <text x="90" y="325" text-anchor="end" class="small">30</text>
  <text x="90" y="275" text-anchor="end" class="small">40</text>
  <text x="90" y="225" text-anchor="end" class="small">50</text>
  <text x="90" y="175" text-anchor="end" class="small">60</text>
  <text x="90" y="125" text-anchor="end" class="small">70</text>
  <text x="90" y="75" text-anchor="end" class="small">80</text>

  <!-- Curves -->
  <path class="curve" d="M110 170 C190 235, 275 285, 355 325 C440 365, 595 415, 760 445"/>
  <path class="curve" d="M110 125 C190 195, 275 250, 355 290 C445 335, 600 390, 760 420"/>
  <path class="curve" d="M110 95 C190 160, 275 215, 355 250 C450 300, 600 360, 760 395"/>

  <!-- Curve labels -->
  <text x="245" y="315" class="label">CURVE 1</text>
  <line x1="305" y1="305" x2="350" y2="295" stroke="#111" stroke-width="1.5"/>

  <text x="500" y="250" class="label">CURVE 2</text>
  <line x1="490" y1="258" x2="440" y2="285" stroke="#111" stroke-width="1.5"/>

  <text x="400" y="190" class="label">CURVE 3</text>
  <line x1="392" y1="195" x2="350" y2="248" stroke="#111" stroke-width="1.5"/>

  <!-- Notes -->
  <text x="110" y="565" class="small">
    Curve 1: Expected 28-day compressive strength of 33 and &lt; 43 N/mm²
  </text>
  <text x="110" y="588" class="small">
    Curve 2: Expected 28-day compressive strength of 43 and &lt; 53 N/mm²
  </text>
  <text x="110" y="611" class="small">
    Curve 3: Expected 28-day compressive strength of 53 N/mm² and above
  </text>
</svg>
