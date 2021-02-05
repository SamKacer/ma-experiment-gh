% Task 7
## Airports graph #7
<div class="mermaid-access">
graph LR
  Alfa -- 2 hours --> Sierra
  Alfa -- 8 hours --> Mike
  India -- 4 hours --> Alfa
  India -- 5 hours --> Romeo
  India -- 9 hours --> Sierra
  Kilo -- 5 hours --> Alfa
  Kilo -- 7 hours --> Mike
  Mike -- 1 hours --> Victor
  Mike -- 10 hours --> India
  Mike -- 11 hours --> Romeo
  Mike -- 7 hours --> Kilo
  Mike -- 8 hours --> Alfa
  Mike -- 9 hours --> Sierra
  Romeo -- 11 hours --> Mike
  Romeo -- 5 hours --> Victor
  Sierra -- 2 hours --> Alfa
  Uniform -- 10 hours --> Kilo
  Uniform -- 11 hours --> Sierra
  Uniform -- 3 hours --> Victor
  Uniform -- 4 hours --> Alfa
</div>

---

[continue to next prompt](./task8prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    