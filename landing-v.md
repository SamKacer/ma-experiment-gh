# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div class="mermaid-access">
graph LR
  Bravo -- 1 hours --> Yankee
  Bravo -- 3 hours --> Zulu
  Hotel -- 10 hours --> Zulu
  Hotel -- 8 hours --> Uniform
  Sierra -- 4 hours --> Bravo
  Sierra -- 7 hours --> Uniform
  Sierra -- 9 hours --> Hotel
  Uniform -- 8 hours --> Hotel
  Zulu -- 10 hours --> Hotel
  Zulu -- 11 hours --> Uniform
</div>

---
[next stage](./task1prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
