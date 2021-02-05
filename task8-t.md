# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Echo -- 3 hours --> Uniform
  Echo -- 7 hours --> Tango
  Golf -- 2 hours --> Romeo
  Golf -- 6 hours --> November
  Golf -- 7 hours --> Uniform
  Golf -- 8 hours --> Mike
  Juliett -- 10 hours --> Tango
  Juliett -- 11 hours --> Romeo
  Juliett -- 6 hours --> Echo
  Mike -- 1 hours --> Tango
  Mike -- 1 hours --> Uniform
  Mike -- 8 hours --> Golf
  November -- 3 hours --> Echo
  November -- 6 hours --> Golf
  Romeo -- 6 hours --> November
  Tango -- 1 hours --> Mike
  Tango -- 10 hours --> Juliett
  Tango -- 7 hours --> Echo
  Uniform -- 10 hours --> Echo
  Uniform -- 7 hours --> Golf
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
    