# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 1 hours --> India
  Charlie -- 1 hours --> Victor
  Charlie -- 4 hours --> Romeo
  Charlie -- 8 hours --> Yankee
  Foxtrot -- 7 hours --> Romeo
  India -- 11 hours --> Charlie
  India -- 11 hours --> Victor
  India -- 2 hours --> Quebec
  Juliett -- 7 hours --> Foxtrot
  Juliett -- 8 hours --> Yankee
  Quebec -- 11 hours --> Foxtrot
  Quebec -- 6 hours --> India
  Romeo -- 1 hours --> India
  Romeo -- 10 hours --> Yankee
  Romeo -- 3 hours --> Victor
  Romeo -- 4 hours --> Quebec
  Romeo -- 7 hours --> Foxtrot
  Victor -- 11 hours --> India
  Victor -- 3 hours --> Romeo
  Yankee -- 8 hours --> Juliett
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    