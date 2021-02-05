% Task 4
## Airports graph #4
<div class="mermaid-access">
graph LR
  Charlie -- 3 hours --> Mike
  Charlie -- 3 hours --> Victor
  Charlie -- 7 hours --> Foxtrot
  Charlie -- 9 hours --> Golf
  Charlie -- 9 hours --> X-ray
  Foxtrot -- 7 hours --> Charlie
  Foxtrot -- 9 hours --> Zulu
  Golf -- 10 hours --> X-ray
  Golf -- 5 hours --> Victor
  Golf -- 9 hours --> Charlie
  Mike -- 11 hours --> Victor
  Mike -- 11 hours --> X-ray
  Sierra -- 11 hours --> Zulu
  Victor -- 11 hours --> Mike
  Victor -- 3 hours --> Charlie
  X-ray -- 2 hours --> Golf
  X-ray -- 2 hours --> Sierra
  X-ray -- 9 hours --> Charlie
  Zulu -- 11 hours --> Sierra
  Zulu -- 9 hours --> Foxtrot
</div>

---

[continue to next prompt](./task5prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    