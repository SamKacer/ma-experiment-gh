# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 1 hours --> India
  Charlie -- 10 hours --> Echo
  Charlie -- 3 hours --> Papa
  Charlie -- 7 hours --> India
  Echo -- 10 hours --> Charlie
  Echo -- 10 hours --> Golf
  Echo -- 10 hours --> India
  Echo -- 10 hours --> Kilo
  Golf -- 1 hours --> Alfa
  Golf -- 10 hours --> Echo
  India -- 1 hours --> Alfa
  India -- 10 hours --> Echo
  India -- 11 hours --> Tango
  India -- 3 hours --> Golf
  India -- 6 hours --> Kilo
  India -- 7 hours --> Charlie
  Kilo -- 10 hours --> Echo
  Kilo -- 8 hours --> Papa
  Papa -- 8 hours --> Kilo
  Tango -- 6 hours --> Alfa
</div>

---

[continue to next prompt](./task4prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    