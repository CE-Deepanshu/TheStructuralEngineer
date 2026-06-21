
<img width="408" height="397" alt="image" src="https://github.com/user-attachments/assets/26d7736e-dc9c-4949-9781-575890a43f7d" />


Practical civil engineering knowledge, site execution insights, and construction practices.

## [MATERIALS](Materials.md)

## [CONCRETE MIX QUANTITY CALCULATOR](Content/CQMC.html)

## [IS CODES](IS_Codes.md)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fce-deepanshu.github.io%2FSiteWiseCivil%2F&label=VISITORS&labelColor=%23ADD8E6&countColor=%2337d67a&style=plastic&labelStyle=upper)

<div class="mermaid">
flowchart TD
    A[PlanForge / Civil Engineering Calculator App] --> B[User Selects Calculator Category]

    B --> C[Structural Engineering]
    B --> D[Concrete Technology]
    B --> E[Steel Design]
    B --> F[Estimation & Costing]
    B --> G[Geotechnical Engineering]
    B --> H[Surveying]
    B --> I[Transportation Engineering]
    B --> J[Hydraulics & Water]
    B --> K[Project Planning]
    B --> L[Unit Converter & Code Tools]

    C --> C1[Beam Calculator]
    C --> C2[Slab Calculator]
    C --> C3[Column Calculator]
    C --> C4[Footing Calculator]
    C --> C5[Load Calculator]

    C1 --> C1A[Input: span, load, grade, steel]
    C1A --> C1B[Calculate bending moment, shear, Ast]
    C1B --> C1C[Output: design result + safety check]

    D --> D1[Concrete Mix Design]
    D --> D2[Water-Cement Ratio]
    D --> D3[Concrete Quantity]
    D --> D4[Cube Strength Result]
    D1 --> D1A[Input: grade, exposure, materials]
    D1A --> D1B[Calculate cement, sand, aggregate, water]
    D1B --> D1C[Output: Mix proportion as per IS 10262]

    E --> E1[Steel Beam Design]
    E --> E2[Bolt Design]
    E --> E3[Weld Design]
    E --> E4[Plate Girder Check]
    E1 --> E1A[Input: section, span, load]
    E1A --> E1B[Check bending, shear, deflection]
    E1B --> E1C[Output: safe/unsafe + utilization ratio]

    F --> F1[Brickwork Calculator]
    F --> F2[Plaster Calculator]
    F --> F3[Concrete Quantity]
    F --> F4[Paint Calculator]
    F --> F5[Bar Bending Schedule]
    F --> F6[Rate Analysis]
    F6 --> F6A[Input: material, labour, machinery rates]
    F6A --> F6B[Calculate total cost]
    F6B --> F6C[Output: BOQ + cost summary]

    G --> G1[Bearing Capacity]
    G --> G2[Soil Classification]
    G --> G3[Earth Pressure]
    G --> G4[Settlement Check]

    H --> H1[Level Calculation]
    H --> H2[Coordinate Calculator]
    H --> H3[Area by Coordinates]
    H --> H4[Traverse Correction]

    I --> I1[Road Camber]
    I --> I2[Super Elevation]
    I --> I3[Flexible Pavement]
    I --> I4[Sight Distance]

    J --> J1[Pipe Flow]
    J --> J2[Open Channel Flow]
    J --> J3[Water Tank Capacity]
    J --> J4[Pump HP Calculator]

    K --> K1[Gantt Chart Generator]
    K --> K2[Project Cost Curve]
    K --> K3[Material Requirement Planner]
    K --> K4[Labour Productivity Calculator]

    L --> L1[Unit Converter]
    L --> L2[IS Code Reference]
    L --> L3[Formula Library]
    L --> L4[PDF/Excel Export]

    C1C --> M[Generate Report]
    D1C --> M
    E1C --> M
    F6C --> M
    K1 --> M
    M --> N[Export as PDF / Excel / Share]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>
