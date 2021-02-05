# Task 2
## Airports graph #2

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Foxtrot
  Charlie -- 11 hours --> Hotel
  Charlie -- 4 hours --> India
  Foxtrot -- 8 hours --> Hotel
  Golf -- 1 hours --> India
  Golf -- 6 hours --> Charlie
  Golf -- 8 hours --> Foxtrot
  Hotel -- 10 hours --> Foxtrot
  Hotel -- 3 hours --> Golf
  Hotel -- 9 hours --> Papa
  India -- 11 hours --> Foxtrot
  India -- 11 hours --> Sierra
  India -- 4 hours --> Charlie
  India -- 7 hours --> Papa
  Papa -- 3 hours --> Tango
  Papa -- 8 hours --> Sierra
  Sierra -- 11 hours --> India
  Sierra -- 3 hours --> Tango
  Tango -- 3 hours --> Papa
  Tango -- 3 hours --> Sierra
</div>

---

[continue to next prompt](./task3prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    