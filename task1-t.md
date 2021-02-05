# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 4 hours --> Golf
  Charlie -- 5 hours --> Delta
  Charlie -- 6 hours --> Juliett
  Delta -- 10 hours --> Kilo
  Delta -- 10 hours --> Tango
  Delta -- 5 hours --> Charlie
  Delta -- 7 hours --> Victor
  Foxtrot -- 8 hours --> Juliett
  Golf -- 2 hours --> Foxtrot
  Golf -- 2 hours --> Kilo
  Golf -- 4 hours --> Charlie
  Juliett -- 2 hours --> Charlie
  Kilo -- 10 hours --> Delta
  Kilo -- 7 hours --> Victor
  Kilo -- 9 hours --> Tango
  Tango -- 10 hours --> Delta
  Tango -- 6 hours --> Charlie
  Tango -- 9 hours --> Kilo
  Tango -- 9 hours --> Victor
  Victor -- 6 hours --> Kilo
</div>

---

[continue to next prompt](./task2prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    