# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 3 hours --> Zulu
  Charlie -- 6 hours --> Whiskey
  Golf -- 1 hours --> Yankee
  Golf -- 5 hours --> Tango
  Oscar -- 1 hours --> Tango
  Oscar -- 6 hours --> Whiskey
  Oscar -- 6 hours --> Yankee
  Papa -- 1 hours --> Oscar
  Papa -- 10 hours --> Golf
  Tango -- 1 hours --> Oscar
  Tango -- 6 hours --> Charlie
  Whiskey -- 10 hours --> Tango
  Whiskey -- 6 hours --> Charlie
  Whiskey -- 6 hours --> Oscar
  Whiskey -- 6 hours --> Papa
  Whiskey -- 6 hours --> Zulu
  Yankee -- 1 hours --> Golf
  Zulu -- 3 hours --> Charlie
  Zulu -- 6 hours --> Whiskey
  Zulu -- 8 hours --> Yankee
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
    