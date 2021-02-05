# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Echo -- 1 hours --> Mike
  Echo -- 10 hours --> Oscar
  Echo -- 8 hours --> Juliett
  Juliett -- 7 hours --> Mike
  Juliett -- 8 hours --> Echo
  Juliett -- 9 hours --> Lima
  Kilo -- 2 hours --> Juliett
  Kilo -- 3 hours --> Zulu
  Lima -- 1 hours --> X-ray
  Lima -- 9 hours --> Juliett
  Mike -- 1 hours --> Echo
  Mike -- 3 hours --> Juliett
  Mike -- 3 hours --> Zulu
  Mike -- 5 hours --> Oscar
  Oscar -- 10 hours --> Echo
  Oscar -- 5 hours --> Mike
  X-ray -- 1 hours --> Lima
  Zulu -- 3 hours --> Kilo
  Zulu -- 3 hours --> Mike
  Zulu -- 6 hours --> Lima
</div>

---

[continue to next prompt](./task6prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    