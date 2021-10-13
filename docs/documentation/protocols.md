<html>

<script src="https://cdn.rawgit.com/knsv/mermaid/6.0.0/dist/mermaid.min.js"></script>
<link href="https://cdn.rawgit.com/knsv/mermaid/6.0.0/dist/mermaid.css" rel="stylesheet" />

<div class='mermaid'>
  graph TD; 
  A[Cex DNA Template] -->|FB Generation| B(dATPaS Calibration);
  A -->|Modified FB Generation| C(Biotinylated DNA Generation);
  B --> E(Biotinylated DNA Generation);
  E --> F(Iodofragmentation);
  C --> G(DNA Shearing and Recovery);
  A -->|RB Generation| D(Biotinylated DNA Generation);
  F --> H(Biotinylated DNA Isolation);
  G --> H;
  D --> H;
  H --> |Forward strand DNA| I(Universal Base Addition);
  H --> |Reverse strand DNA| J(Full-length Gene Synthesis);
  I --> J;
  J --> K(Universal Base Replacement);

  click B "http://www.github.com" "This is a link"
  click A "#link"
  style A fill: #0234
</div>

<a href="#link">Jump to Chapter 4</a>
# section1
<div id="link">protocol1</div>
<h2>Chapter 4</h2>
</html>
