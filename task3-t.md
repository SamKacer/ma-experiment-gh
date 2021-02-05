# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 4 hours --> Whiskey
  Delta -- 5 hours --> Golf
  Delta -- 5 hours --> Sierra
  Delta -- 8 hours --> November
  Golf -- 5 hours --> Juliett
  Juliett -- 11 hours --> November
  Juliett -- 5 hours --> Golf
  Juliett -- 6 hours --> Zulu
  November -- 1 hours --> Sierra
  November -- 2 hours --> Quebec
  November -- 4 hours --> Juliett
  November -- 5 hours --> Whiskey
  November -- 8 hours --> Delta
  Quebec -- 10 hours --> Golf
  Quebec -- 2 hours --> November
  Quebec -- 8 hours --> Zulu
  Sierra -- 1 hours --> November
  Sierra -- 6 hours --> Whiskey
  Zulu -- 6 hours --> Juliett
  Zulu -- 8 hours --> Quebec
</div>

---

[continue to next prompt](./task4prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    