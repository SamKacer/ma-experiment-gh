# Task 7
## Airports graph #7

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 10 hours --> Sierra
  Charlie -- 7 hours --> Whiskey
  Foxtrot -- 2 hours --> Golf
  Foxtrot -- 6 hours --> Victor
  Golf -- 10 hours --> Whiskey
  Golf -- 2 hours --> Foxtrot
  Golf -- 3 hours --> Victor
  Golf -- 5 hours --> Oscar
  Oscar -- 9 hours --> Victor
  Sierra -- 10 hours --> Charlie
  Victor -- 10 hours --> Sierra
  Victor -- 8 hours --> Golf
  Victor -- 9 hours --> Oscar
  Whiskey -- 5 hours --> Foxtrot
  Whiskey -- 6 hours --> Golf
  Whiskey -- 7 hours --> Charlie
  Zulu -- 1 hours --> Charlie
  Zulu -- 4 hours --> Oscar
  Zulu -- 6 hours --> Golf
  Zulu -- 7 hours --> Sierra
</div>

---

[continue to next prompt](./task8prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    