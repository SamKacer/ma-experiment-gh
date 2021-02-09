# task 7

## Name two airports with no incoming flights.

---

## Airports graph #7
<div></div>
<div class="mermaid-access">
graph LR
  Foxtrot -- 4 hours --> India
  Foxtrot -- 5 hours --> Whiskey
  Foxtrot -- 7 hours --> Mike
  Golf -- 1 hours --> Quebec
  India -- 11 hours --> Lima
  India -- 2 hours --> Juliett
  India -- 4 hours --> Foxtrot
  Juliett -- 1 hours --> Whiskey
  Juliett -- 2 hours --> India
  Juliett -- 3 hours --> Papa
  Mike -- 1 hours --> Juliett
  Oscar -- 1 hours --> Foxtrot
  Oscar -- 2 hours --> Golf
  Papa -- 11 hours --> Quebec
  Papa -- 3 hours --> Juliett
  Quebec -- 11 hours --> Papa
  Whiskey -- 1 hours --> Mike
  Whiskey -- 5 hours --> Foxtrot
  Zulu -- 2 hours --> Juliett
  Zulu -- 9 hours --> Victor
</div>

---

[continue to next task](./task8-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
