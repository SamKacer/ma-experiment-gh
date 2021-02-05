# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Oscar
  Charlie -- 11 hours --> Victor
  Charlie -- 7 hours --> India
  Golf -- 10 hours --> Oscar
  India -- 1 hours --> Tango
  India -- 7 hours --> Charlie
  Kilo -- 10 hours --> Mike
  Kilo -- 9 hours --> India
  Mike -- 3 hours --> Charlie
  Mike -- 8 hours --> Kilo
  Oscar -- 10 hours --> Charlie
  Oscar -- 10 hours --> Golf
  Oscar -- 4 hours --> India
  Oscar -- 8 hours --> Tango
  Tango -- 2 hours --> Mike
  Tango -- 5 hours --> Victor
  Tango -- 8 hours --> Oscar
  Victor -- 11 hours --> Charlie
  Victor -- 5 hours --> Golf
  Victor -- 5 hours --> Tango
</div>

---

[continue to next prompt](./task6prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    