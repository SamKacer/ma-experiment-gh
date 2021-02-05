# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 11 hours --> India
  Alfa -- 6 hours --> Zulu
  Alfa -- 7 hours --> Tango
  Hotel -- 4 hours --> Juliett
  Hotel -- 8 hours --> Victor
  Hotel -- 8 hours --> Zulu
  India -- 11 hours --> Alfa
  India -- 8 hours --> Romeo
  Juliett -- 1 hours --> Zulu
  Juliett -- 6 hours --> Romeo
  Juliett -- 7 hours --> Tango
  Romeo -- 6 hours --> Juliett
  Romeo -- 8 hours --> India
  Tango -- 1 hours --> Hotel
  Tango -- 11 hours --> Juliett
  Victor -- 2 hours --> Romeo
  Victor -- 8 hours --> Hotel
  Zulu -- 1 hours --> Juliett
  Zulu -- 6 hours --> Alfa
  Zulu -- 8 hours --> Hotel
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    