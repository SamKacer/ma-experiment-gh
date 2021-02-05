% Task 3
## Airports graph #3
<div class="mermaid-access">
graph LR
  India -- 11 hours --> Sierra
  India -- 9 hours --> Juliett
  Juliett -- 1 hours --> Zulu
  Juliett -- 2 hours --> Mike
  Juliett -- 6 hours --> Romeo
  Juliett -- 9 hours --> India
  Juliett -- 9 hours --> Sierra
  Lima -- 3 hours --> Mike
  Mike -- 3 hours --> Lima
  Papa -- 1 hours --> Romeo
  Papa -- 6 hours --> India
  Romeo -- 1 hours --> Lima
  Romeo -- 1 hours --> Papa
  Romeo -- 10 hours --> Sierra
  Romeo -- 6 hours --> Juliett
  Sierra -- 10 hours --> Romeo
  Sierra -- 11 hours --> India
  Sierra -- 9 hours --> Juliett
  Zulu -- 1 hours --> Juliett
  Zulu -- 2 hours --> Romeo
</div>

---

[continue to next prompt](./task4prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    