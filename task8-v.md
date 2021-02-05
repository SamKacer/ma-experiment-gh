# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Hotel -- 1 hours --> Uniform
  Hotel -- 2 hours --> Tango
  Hotel -- 9 hours --> Juliett
  Juliett -- 9 hours --> Hotel
  Juliett -- 9 hours --> Papa
  Mike -- 6 hours --> November
  Mike -- 9 hours --> Uniform
  November -- 3 hours --> Juliett
  November -- 5 hours --> Papa
  November -- 8 hours --> Tango
  Papa -- 8 hours --> Quebec
  Quebec -- 11 hours --> Mike
  Quebec -- 4 hours --> Juliett
  Quebec -- 8 hours --> Uniform
  Tango -- 4 hours --> Hotel
  Tango -- 8 hours --> November
  Uniform -- 3 hours --> November
  Uniform -- 6 hours --> Quebec
  Uniform -- 7 hours --> Juliett
  Uniform -- 9 hours --> Mike
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
    