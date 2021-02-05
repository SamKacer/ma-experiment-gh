# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 10 hours --> Delta
  Alfa -- 11 hours --> Hotel
  Alfa -- 8 hours --> Yankee
  Charlie -- 2 hours --> Yankee
  Charlie -- 3 hours --> Echo
  Charlie -- 9 hours --> Whiskey
  Echo -- 4 hours --> Hotel
  Golf -- 10 hours --> Whiskey
  Golf -- 7 hours --> Yankee
  Golf -- 9 hours --> Hotel
  Hotel -- 11 hours --> Alfa
  Hotel -- 4 hours --> Echo
  Hotel -- 7 hours --> Yankee
  Hotel -- 9 hours --> Golf
  Whiskey -- 10 hours --> Golf
  Whiskey -- 4 hours --> Yankee
  Whiskey -- 9 hours --> Charlie
  Yankee -- 4 hours --> Whiskey
  Yankee -- 7 hours --> Golf
  Yankee -- 7 hours --> Hotel
</div>

---

[continue to next prompt](./task5prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    