# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 11 hours --> Foxtrot
  Bravo -- 3 hours --> Quebec
  Bravo -- 9 hours --> Yankee
  Juliett -- 11 hours --> Yankee
  Juliett -- 3 hours --> Sierra
  Juliett -- 8 hours --> Foxtrot
  Quebec -- 11 hours --> Sierra
  Sierra -- 11 hours --> Quebec
  Sierra -- 3 hours --> Juliett
  Yankee -- 11 hours --> Juliett
</div>

---
[next stage](./task1-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
