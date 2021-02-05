% Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div class="mermaid-access">
graph LR
  Alfa -- 1 hours --> Romeo
  Lima -- 10 hours --> Hotel
  Romeo -- 1 hours --> Alfa
  Romeo -- 5 hours --> Lima
  Romeo -- 9 hours --> Yankee
  X-ray -- 11 hours --> Hotel
  X-ray -- 11 hours --> Yankee
  X-ray -- 8 hours --> Romeo
  X-ray -- 9 hours --> Alfa
  Yankee -- 3 hours --> Hotel
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
