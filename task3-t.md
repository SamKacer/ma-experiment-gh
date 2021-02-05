# Task 3
## Airports graph #3

<div></div>
<div class="mermaid-access">
graph LR
  Juliett -- 10 hours --> Uniform
  Juliett -- 2 hours --> Oscar
  Juliett -- 5 hours --> Tango
  Juliett -- 7 hours --> Romeo
  Mike -- 10 hours --> Oscar
  Mike -- 2 hours --> Romeo
  Mike -- 4 hours --> Uniform
  Mike -- 9 hours --> Yankee
  Oscar -- 1 hours --> Sierra
  Oscar -- 2 hours --> Juliett
  Romeo -- 3 hours --> Mike
  Romeo -- 7 hours --> Juliett
  Tango -- 5 hours --> Juliett
  Uniform -- 10 hours --> Juliett
  Uniform -- 11 hours --> Sierra
  Uniform -- 4 hours --> Mike
  Uniform -- 5 hours --> Yankee
  Uniform -- 7 hours --> Tango
  Yankee -- 5 hours --> Uniform
  Yankee -- 9 hours --> Mike
</div>

---

[continue to next prompt](./task4prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    