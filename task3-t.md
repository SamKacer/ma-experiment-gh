# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Tango
  Delta -- 2 hours --> Zulu
  Delta -- 6 hours --> Mike
  Echo -- 3 hours --> Mike
  Echo -- 6 hours --> Whiskey
  Juliett -- 11 hours --> Zulu
  Juliett -- 4 hours --> Mike
  Juliett -- 5 hours --> Charlie
  Juliett -- 7 hours --> Tango
  Mike -- 1 hours --> Zulu
  Mike -- 3 hours --> Echo
  Mike -- 3 hours --> Tango
  Mike -- 6 hours --> Charlie
  Mike -- 6 hours --> Delta
  Tango -- 3 hours --> Mike
  Tango -- 9 hours --> Whiskey
  Whiskey -- 6 hours --> Echo
  Whiskey -- 9 hours --> Tango
  Zulu -- 1 hours --> Mike
  Zulu -- 11 hours --> Juliett
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
    