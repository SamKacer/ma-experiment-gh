# task 6

## Name two airports with no outgoing flights.

---

## Airports graph #6
<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 4 hours --> Hotel
  Bravo -- 8 hours --> Juliett
  Charlie -- 11 hours --> Lima
  Charlie -- 6 hours --> November
  Charlie -- 6 hours --> Uniform
  Hotel -- 6 hours --> Quebec
  India -- 1 hours --> Charlie
  Juliett -- 6 hours --> Quebec
  Juliett -- 7 hours --> India
  Lima -- 11 hours --> Charlie
  Lima -- 2 hours --> Uniform
  Lima -- 6 hours --> November
  November -- 6 hours --> Charlie
  November -- 6 hours --> Lima
  Oscar -- 10 hours --> Lima
  Oscar -- 10 hours --> Quebec
  Oscar -- 4 hours --> Victor
  Uniform -- 3 hours --> India
  Victor -- 11 hours --> Delta
  Victor -- 2 hours --> Juliett
</div>

---

[continue to next task](./task7-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
