# Task 2
## Airports graph #2

<div></div>
<div class="mermaid-access">
graph LR
  Golf -- 6 hours --> Sierra
  Golf -- 7 hours --> Mike
  Golf -- 7 hours --> Oscar
  Golf -- 7 hours --> Uniform
  Golf -- 8 hours --> Lima
  Lima -- 10 hours --> Echo
  Lima -- 2 hours --> Golf
  Lima -- 9 hours --> Mike
  Mike -- 4 hours --> Sierra
  Mike -- 7 hours --> Oscar
  Mike -- 9 hours --> Lima
  Oscar -- 1 hours --> Uniform
  Oscar -- 7 hours --> Mike
  Sierra -- 11 hours --> Victor
  Sierra -- 6 hours --> Golf
  Sierra -- 8 hours --> Mike
  Uniform -- 1 hours --> Oscar
  Uniform -- 6 hours --> Sierra
  Uniform -- 7 hours --> Golf
  Victor -- 11 hours --> Sierra
</div>

---

[continue to next prompt](./task3prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    