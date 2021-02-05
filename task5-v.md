# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 5 hours --> Yankee
  Bravo -- 7 hours --> Zulu
  Hotel -- 1 hours --> Zulu
  Hotel -- 5 hours --> Yankee
  India -- 6 hours --> Juliett
  India -- 8 hours --> Lima
  India -- 9 hours --> Yankee
  India -- 9 hours --> Zulu
  Juliett -- 6 hours --> India
  Juliett -- 7 hours --> Hotel
  Lima -- 3 hours --> Bravo
  Lima -- 8 hours --> India
  Tango -- 4 hours --> Zulu
  Yankee -- 5 hours --> Bravo
  Yankee -- 5 hours --> Hotel
  Yankee -- 9 hours --> India
  Zulu -- 1 hours --> Hotel
  Zulu -- 4 hours --> Tango
  Zulu -- 9 hours --> India
  Zulu -- 9 hours --> Juliett
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
    