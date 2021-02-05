% Task 2
## Airports graph #2
<div class="mermaid-access">
graph LR
  Echo -- 1 hours --> Juliett
  Echo -- 10 hours --> Hotel
  Echo -- 6 hours --> X-ray
  Golf -- 2 hours --> X-ray
  Golf -- 4 hours --> Juliett
  Hotel -- 10 hours --> Echo
  Hotel -- 2 hours --> X-ray
  Hotel -- 3 hours --> Juliett
  Juliett -- 11 hours --> Uniform
  Juliett -- 4 hours --> Golf
  Juliett -- 9 hours --> X-ray
  Sierra -- 1 hours --> Hotel
  Sierra -- 5 hours --> Alfa
  Sierra -- 5 hours --> Golf
  Uniform -- 10 hours --> Echo
  Uniform -- 7 hours --> Golf
  X-ray -- 2 hours --> Golf
  X-ray -- 2 hours --> Hotel
  X-ray -- 6 hours --> Echo
  X-ray -- 9 hours --> Juliett
</div>

---

[continue to next prompt](./task3prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    