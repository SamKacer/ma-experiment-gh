% Task 1
## Airports graph #1
<div class="mermaid-access">
graph LR
  Delta -- 1 hours --> Tango
  Delta -- 11 hours --> Lima
  Delta -- 5 hours --> Yankee
  Delta -- 7 hours --> Zulu
  Golf -- 1 hours --> Romeo
  Golf -- 3 hours --> Zulu
  Juliett -- 6 hours --> Lima
  Lima -- 11 hours --> Delta
  Lima -- 5 hours --> Zulu
  Lima -- 6 hours --> Juliett
  Lima -- 8 hours --> Tango
  Romeo -- 1 hours --> Golf
  Romeo -- 8 hours --> Juliett
  Romeo -- 9 hours --> Yankee
  Tango -- 1 hours --> Delta
  Yankee -- 3 hours --> Romeo
  Yankee -- 4 hours --> Golf
  Yankee -- 4 hours --> Zulu
  Zulu -- 4 hours --> Yankee
  Zulu -- 7 hours --> Delta
</div>

---

[continue to next prompt](./task2prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    