# Task 1
## Airports graph #1

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 4 hours --> Yankee
  Charlie -- 3 hours --> Hotel
  Charlie -- 3 hours --> Sierra
  Charlie -- 7 hours --> Foxtrot
  Foxtrot -- 3 hours --> Hotel
  Foxtrot -- 3 hours --> Sierra
  Foxtrot -- 4 hours --> Yankee
  Foxtrot -- 7 hours --> Charlie
  Hotel -- 3 hours --> Charlie
  Hotel -- 7 hours --> Sierra
  Mike -- 4 hours --> Hotel
  Mike -- 6 hours --> Whiskey
  Sierra -- 3 hours --> Charlie
  Sierra -- 3 hours --> Foxtrot
  Sierra -- 7 hours --> Hotel
  Whiskey -- 11 hours --> Sierra
  Whiskey -- 5 hours --> Hotel
  Yankee -- 2 hours --> Alfa
  Yankee -- 4 hours --> Foxtrot
  Yankee -- 7 hours --> Charlie
</div>

---

[continue to next prompt](./task2prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    