# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Foxtrot -- 6 hours --> Zulu
  Foxtrot -- 9 hours --> Hotel
  Foxtrot -- 9 hours --> Papa
  Golf -- 11 hours --> Tango
  Golf -- 8 hours --> Papa
  Hotel -- 5 hours --> Yankee
  Hotel -- 8 hours --> Mike
  Hotel -- 9 hours --> Foxtrot
  Mike -- 1 hours --> Hotel
  Mike -- 3 hours --> Tango
  Tango -- 1 hours --> Foxtrot
  Tango -- 11 hours --> Golf
  Tango -- 4 hours --> Yankee
  Tango -- 6 hours --> Mike
  Yankee -- 4 hours --> Tango
  Yankee -- 6 hours --> Mike
  Yankee -- 6 hours --> Papa
  Yankee -- 8 hours --> Hotel
  Zulu -- 5 hours --> Golf
  Zulu -- 7 hours --> Papa
</div>

---

[continue to next prompt](./task7prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    