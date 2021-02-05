# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 8 hours --> Golf
  Delta -- 10 hours --> Quebec
  Delta -- 8 hours --> November
  Golf -- 10 hours --> November
  Golf -- 6 hours --> Delta
  Golf -- 8 hours --> Alfa
  Kilo -- 11 hours --> November
  November -- 10 hours --> Whiskey
  November -- 11 hours --> Kilo
  November -- 3 hours --> Yankee
  November -- 8 hours --> Delta
  Quebec -- 10 hours --> Delta
  Quebec -- 5 hours --> Whiskey
  Quebec -- 9 hours --> Yankee
  Whiskey -- 10 hours --> November
  Whiskey -- 5 hours --> Quebec
  Yankee -- 10 hours --> Kilo
  Yankee -- 11 hours --> Delta
  Yankee -- 3 hours --> November
  Yankee -- 9 hours --> Quebec
</div>

---

[continue to next prompt](./task6prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    