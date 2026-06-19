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
