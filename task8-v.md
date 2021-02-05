% Task 8
## Airports graph #8
<div class="mermaid-access">
graph LR
  Bravo -- 10 hours --> Delta
  Bravo -- 5 hours --> Papa
  Bravo -- 6 hours --> Lima
  India -- 8 hours --> Bravo
  India -- 9 hours --> Yankee
  Lima -- 1 hours --> Oscar
  Lima -- 5 hours --> November
  Lima -- 6 hours --> Bravo
  Lima -- 9 hours --> Yankee
  November -- 5 hours --> Lima
  November -- 6 hours --> Papa
  Oscar -- 1 hours --> Lima
  Oscar -- 4 hours --> Delta
  Papa -- 5 hours --> Bravo
  Papa -- 6 hours --> November
  Papa -- 9 hours --> Yankee
  Yankee -- 1 hours --> Delta
  Yankee -- 9 hours --> India
  Yankee -- 9 hours --> Lima
  Yankee -- 9 hours --> Papa
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
    