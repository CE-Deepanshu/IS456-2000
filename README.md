# IS456-2000
Indian Standard Code of Practice for Plain and Reinforced Concrete (IS 456:2000).

<div class="mermaid">
flowchart TD
A[User opens app] --> B[Select Project]
B --> C{Choose Feature}

C --> D[Click Site Photo]
D --> E[AI Defect Detection]
E --> F[Defect Type + Severity]
F --> G[Suggested Repair Method]
G --> H[Market Product Suggestions]
H --> I[Generate Site Report]

C --> J[Upload Drawing / Plan]
J --> K[AI Reads Dimensions]
K --> L[User Confirms Measurements]
L --> M[Quantity Calculation]
M --> N[BOQ / Estimation]

C --> O[Site Calculator]
O --> P[Concrete / Steel / Brick / Plaster / Paint]
P --> N

C --> Q[Project Management]
Q --> R[Daily Progress + Labour + Material]
R --> S[Dashboard]

I --> T[PDF Report / Share with Client]
N --> T
S --> T
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>
