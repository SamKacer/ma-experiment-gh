# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Tango
  Charlie -- 4 hours --> Romeo
  Juliett -- 10 hours --> Kilo
  Juliett -- 9 hours --> Tango
  Kilo -- 10 hours --> Juliett
  Kilo -- 3 hours --> Romeo
  Kilo -- 8 hours --> Papa
  Papa -- 11 hours --> Tango
  Papa -- 2 hours --> Uniform
  Papa -- 8 hours --> Charlie
  Papa -- 8 hours --> Kilo
  Romeo -- 11 hours --> Papa
  Romeo -- 2 hours --> Tango
  Romeo -- 3 hours --> Kilo
  Romeo -- 4 hours --> Charlie
  Romeo -- 5 hours --> Juliett
  Tango -- 11 hours --> Papa
  Tango -- 2 hours --> Charlie
  Tango -- 9 hours --> Juliett
  Whiskey -- 7 hours --> Kilo
</div>

---

[continue to next prompt](./task5prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    