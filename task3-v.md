# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Foxtrot
  Charlie -- 3 hours --> Zulu
  Delta -- 11 hours --> Charlie
  Delta -- 3 hours --> Zulu
  Delta -- 5 hours --> India
  Delta -- 7 hours --> Echo
  Echo -- 5 hours --> Foxtrot
  Echo -- 5 hours --> Sierra
  Echo -- 9 hours --> Zulu
  Foxtrot -- 1 hours --> Charlie
  Foxtrot -- 1 hours --> India
  Foxtrot -- 6 hours --> Delta
  India -- 1 hours --> Foxtrot
  India -- 5 hours --> Papa
  Papa -- 2 hours --> Zulu
  Papa -- 5 hours --> India
  Sierra -- 2 hours --> Papa
  Zulu -- 2 hours --> Delta
  Zulu -- 2 hours --> Papa
  Zulu -- 3 hours --> Charlie
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
    