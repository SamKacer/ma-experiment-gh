% Task 3
## Airports graph #3
<div class="mermaid-access">
graph LR
  Echo -- 1 hours --> Romeo
  Echo -- 3 hours --> Papa
  Echo -- 7 hours --> Oscar
  Mike -- 1 hours --> Victor
  Mike -- 10 hours --> Papa
  Mike -- 8 hours --> Romeo
  Oscar -- 7 hours --> Echo
  Oscar -- 7 hours --> Zulu
  Papa -- 10 hours --> Mike
  Papa -- 2 hours --> Victor
  Papa -- 3 hours --> Echo
  Papa -- 5 hours --> Zulu
  Romeo -- 1 hours --> Echo
  Romeo -- 1 hours --> Zulu
  Romeo -- 8 hours --> Mike
  Victor -- 1 hours --> Mike
  Victor -- 3 hours --> Papa
  Zulu -- 1 hours --> Romeo
  Zulu -- 3 hours --> Sierra
  Zulu -- 7 hours --> Oscar
</div>

---

[continue to next prompt](./task4prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    