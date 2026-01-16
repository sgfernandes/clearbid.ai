# clearbid.ai

<svg width="1400" height="900" viewBox="0 0 1400 900" xmlns="http://www.w3.org/2000/svg">
  <style>
    .frame { fill:#F8F9FB; stroke:#E5E7EB; stroke-width:1; }
    .panel { fill:#FFFFFF; stroke:#E5E7EB; stroke-width:1; }
    .header { fill:#FFFFFF; stroke:#E5E7EB; stroke-width:1; }
    .title { font: 600 16px Inter, Arial, sans-serif; fill:#111827; }
    .text { font: 13px Inter, Arial, sans-serif; fill:#374151; }
    .muted { fill:#6B7280; }
    .badge-ok { fill:#16A34A; }
    .badge-warn { fill:#F59E0B; }
    .badge-bad { fill:#DC2626; }
  </style>

  <!-- App Background -->
  <rect x="0" y="0" width="1400" height="900" class="frame"/>

  <!-- Top Bar -->
  <rect x="0" y="0" width="1400" height="64" class="header"/>
  <text x="24" y="40" class="title">Case: 2026–041 · Disclosure Packet Review</text>
  <text x="1050" y="40" class="text muted">Status: In Review</text>
  <rect x="1220" y="18" width="140" height="28" rx="6" fill="#2563EB"/>
  <text x="1260" y="38" font-size="13" fill="#FFFFFF">Export</text>

  <!-- Left Panel -->
  <rect x="0" y="64" width="280" height="836" class="panel"/>
  <text x="20" y="100" class="title">Disclosure Packet</text>

  <text x="20" y="140" class="text">Financial Disclosures</text>
  <circle cx="250" cy="136" r="6" class="badge-ok"/>

  <text x="20" y="170" class="text">Legal Disclosures</text>
  <circle cx="250" cy="166" r="6" class="badge-warn"/>

  <text x="20" y="200" class="text">Environmental</text>
  <circle cx="250" cy="196" r="6" class="badge-bad"/>

  <text x="20" y="230" class="text">Operational</text>
  <circle cx="250" cy="226" r="6" class="badge-ok"/>

  <!-- Center Panel -->
  <rect x="280" y="64" width="760" height="836" class="panel"/>
  <text x="310" y="100" class="title">Agent Workspace</text>

  <!-- Timeline -->
  <text x="310" y="140" class="text muted">Ingested → Classified → Extracted → Validated → Drafted</text>

  <!-- Agent Summary Card -->
  <rect x="310" y="170" width="700" height="180" rx="12" class="panel"/>
  <text x="330" y="205" class="title">Agent Summary</text>
  <text x="330" y="235" class="text">✔ 14 required disclosures identified</text>
  <text x="330" y="260" class="text">⚠ Missing: Phase I Environmental Assessment</text>
  <text x="330" y="285" class="text">⚠ Conflict detected in Lease Term</text>

  <!-- Findings Table -->
  <rect x="310" y="380" width="700" height="240" rx="12" class="panel"/>
  <text x="330" y="415" class="title">Structured Findings</text>

  <text x="330" y="450" class="text">Environmental — Missing — Confidence: 0.41</text>
  <text x="330" y="480" class="text">Lease Term — Conflict — Confidence: 0.67</text>
  <text x="330" y="510" class="text">Property Taxes — Complete — Confidence: 0.94</text>

  <!-- Right Panel -->
  <rect x="1040" y="64" width="360" height="836" class="panel"/>
  <text x="1060" y="100" class="title">Evidence & Traceability</text>

  <rect x="1060" y="130" width="320" height="220" rx="10" class="panel"/>
  <text x="1080" y="165" class="text">Source Document</text>
  <text x="1080" y="195" class="text muted">Highlighted clauses</text>

  <rect x="1060" y="380" width="320" height="220" rx="10" class="panel"/>
  <text x="1080" y="415" class="text">Agent Interpretation</text>
  <text x="1080" y="445" class="text muted">Reasoning & citations</text>

</svg>
