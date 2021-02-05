% Task 5
## Airports graph #5
<div class="mermaid-access">
graph LR
  Echo -- 2 hours --> Mike
  Echo -- 4 hours --> Sierra
  Foxtrot -- 1 hours --> Golf
  Foxtrot -- 10 hours --> Sierra
  Foxtrot -- 11 hours --> Lima
  Foxtrot -- 2 hours --> Papa
  Golf -- 1 hours --> Foxtrot
  Lima -- 10 hours --> Mike
  Lima -- 10 hours --> Papa
  Lima -- 5 hours --> Sierra
  Lima -- 7 hours --> Foxtrot
  Oscar -- 11 hours --> Papa
  Papa -- 2 hours --> Foxtrot
  Papa -- 2 hours --> Mike
  Papa -- 4 hours --> Echo
  Sierra -- 10 hours --> Foxtrot
  Sierra -- 10 hours --> Oscar
  Sierra -- 2 hours --> Papa
  Sierra -- 4 hours --> Echo
  Sierra -- 5 hours --> Lima
</div>

---

[continue to next prompt](./task6prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    