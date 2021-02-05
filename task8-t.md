% Task 8
## Airports graph #8
<div class="mermaid-access">
graph LR
  Alfa -- 2 hours --> Oscar
  Bravo -- 4 hours --> Victor
  Kilo -- 4 hours --> Bravo
  Kilo -- 6 hours --> Tango
  Kilo -- 6 hours --> Victor
  Kilo -- 6 hours --> Whiskey
  Oscar -- 3 hours --> Victor
  Oscar -- 6 hours --> Whiskey
  Oscar -- 8 hours --> Tango
  Sierra -- 9 hours --> Victor
  Sierra -- 9 hours --> Whiskey
  Tango -- 5 hours --> Sierra
  Tango -- 6 hours --> Kilo
  Tango -- 8 hours --> Oscar
  Victor -- 3 hours --> Oscar
  Victor -- 4 hours --> Bravo
  Victor -- 7 hours --> Alfa
  Victor -- 9 hours --> Sierra
  Whiskey -- 4 hours --> Tango
  Whiskey -- 9 hours --> Sierra
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    