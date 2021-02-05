# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div class="mermaid-access">
graph LR
  Echo -- 1 hours --> Sierra
  Echo -- 2 hours --> X-ray
  Echo -- 8 hours --> November
  Lima -- 4 hours --> Echo
  Lima -- 4 hours --> November
  November -- 8 hours --> Echo
  Sierra -- 1 hours --> Echo
  Sierra -- 5 hours --> Papa
  X-ray -- 10 hours --> Echo
  X-ray -- 5 hours --> November
</div>

---
[next stage](./task1prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
