# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 11 hours --> Zulu
  Alfa -- 4 hours --> Golf
  Charlie -- 10 hours --> India
  Charlie -- 4 hours --> Tango
  Golf -- 1 hours --> Hotel
  Golf -- 11 hours --> Charlie
  Golf -- 7 hours --> India
  Golf -- 7 hours --> Tango
  Golf -- 7 hours --> Zulu
  Hotel -- 10 hours --> Alfa
  Hotel -- 9 hours --> India
  India -- 10 hours --> Charlie
  India -- 7 hours --> Golf
  India -- 9 hours --> Hotel
  India -- 9 hours --> Tango
  Oscar -- 2 hours --> Zulu
  Tango -- 4 hours --> Charlie
  Tango -- 7 hours --> Golf
  Zulu -- 6 hours --> Alfa
  Zulu -- 7 hours --> Golf
</div>

---

[continue to next prompt](./task8prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    