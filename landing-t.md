# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div></div>
<div class="mermaid-access">
graph LR
  Hotel -- 10 hours --> Yankee
  Hotel -- 8 hours --> Mike
  India -- 10 hours --> Mike
  India -- 3 hours --> Tango
  India -- 5 hours --> Yankee
  Mike -- 10 hours --> Alfa
  Mike -- 10 hours --> India
  Tango -- 11 hours --> Alfa
  Tango -- 3 hours --> India
  Yankee -- 5 hours --> India
</div>

---
[next stage](./task1-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
