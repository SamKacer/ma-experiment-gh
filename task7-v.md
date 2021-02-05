% Task 7
## Airports graph #7
<div class="mermaid-access">
graph LR
  Alfa -- 11 hours --> Juliett
  Alfa -- 9 hours --> Kilo
  Bravo -- 2 hours --> India
  Bravo -- 8 hours --> Juliett
  Delta -- 10 hours --> Bravo
  Delta -- 3 hours --> Kilo
  Delta -- 4 hours --> Papa
  Delta -- 8 hours --> Juliett
  India -- 1 hours --> Papa
  India -- 2 hours --> Bravo
  India -- 2 hours --> Kilo
  Juliett -- 8 hours --> Bravo
  Kilo -- 2 hours --> Alfa
  Kilo -- 2 hours --> Bravo
  Kilo -- 2 hours --> India
  Kilo -- 3 hours --> Delta
  Kilo -- 8 hours --> Juliett
  Oscar -- 5 hours --> India
  Oscar -- 9 hours --> Papa
  Papa -- 1 hours --> India
</div>

---

[continue to next prompt](./task8prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    