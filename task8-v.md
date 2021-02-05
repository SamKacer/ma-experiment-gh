# Task 8
## Airports graph #8

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 4 hours --> Delta
  Alfa -- 6 hours --> Uniform
  Bravo -- 1 hours --> Uniform
  Bravo -- 6 hours --> Sierra
  Delta -- 3 hours --> Yankee
  Delta -- 4 hours --> Alfa
  Delta -- 6 hours --> Sierra
  Oscar -- 6 hours --> Sierra
  Oscar -- 7 hours --> Uniform
  Quebec -- 1 hours --> Yankee
  Quebec -- 10 hours --> Alfa
  Sierra -- 11 hours --> Uniform
  Sierra -- 6 hours --> Delta
  Sierra -- 6 hours --> Oscar
  Uniform -- 11 hours --> Sierra
  Uniform -- 6 hours --> Yankee
  Uniform -- 7 hours --> Oscar
  Yankee -- 3 hours --> Delta
  Yankee -- 6 hours --> Oscar
  Yankee -- 6 hours --> Uniform
</div>

---

[continue to short survey](./tlx-prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
    