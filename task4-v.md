# Task 4
## Airports graph #4

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 1 hours --> Papa
  Charlie -- 2 hours --> Yankee
  Charlie -- 5 hours --> Golf
  Golf -- 6 hours --> Yankee
  Lima -- 7 hours --> Charlie
  Lima -- 8 hours --> Yankee
  Mike -- 5 hours --> Lima
  Mike -- 5 hours --> Papa
  Papa -- 1 hours --> Charlie
  Papa -- 11 hours --> Sierra
  Sierra -- 1 hours --> Golf
  Sierra -- 11 hours --> Papa
  Sierra -- 8 hours --> Yankee
  Sierra -- 9 hours --> Whiskey
  Whiskey -- 6 hours --> Papa
  Whiskey -- 9 hours --> Sierra
  Yankee -- 2 hours --> Charlie
  Yankee -- 6 hours --> Golf
  Yankee -- 8 hours --> Lima
  Yankee -- 8 hours --> Sierra
</div>

---

[continue to next prompt](./task5prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    