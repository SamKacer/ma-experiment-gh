% Task 5
## Airports graph #5
<div class="mermaid-access">
graph LR
  India -- 1 hours --> Victor
  India -- 9 hours --> Mike
  Kilo -- 1 hours --> Oscar
  Kilo -- 2 hours --> Tango
  Mike -- 11 hours --> Romeo
  Mike -- 5 hours --> Victor
  Oscar -- 10 hours --> India
  Oscar -- 10 hours --> Yankee
  Oscar -- 5 hours --> Tango
  Romeo -- 11 hours --> Mike
  Romeo -- 9 hours --> Yankee
  Tango -- 1 hours --> Yankee
  Tango -- 2 hours --> Kilo
  Tango -- 4 hours --> Victor
  Tango -- 5 hours --> Oscar
  Victor -- 1 hours --> India
  Victor -- 5 hours --> Mike
  Yankee -- 1 hours --> Tango
  Yankee -- 10 hours --> Oscar
  Yankee -- 9 hours --> Romeo
</div>

---

[continue to next prompt](./task6prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    