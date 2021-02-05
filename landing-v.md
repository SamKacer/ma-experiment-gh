# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 1 hours --> Zulu
  Bravo -- 10 hours --> Whiskey
  Bravo -- 3 hours --> Tango
  Bravo -- 8 hours --> Golf
  Golf -- 11 hours --> Zulu
  Romeo -- 4 hours --> Whiskey
  Whiskey -- 7 hours --> Bravo
  Whiskey -- 9 hours --> Zulu
  Zulu -- 11 hours --> Golf
  Zulu -- 9 hours --> Whiskey
</div>

---
[next stage](./task1prompt-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
