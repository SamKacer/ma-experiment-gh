# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div class="mermaid-access">
graph LR
  Alfa -- 2 hours --> Hotel
  Hotel -- 11 hours --> Mike
  Hotel -- 7 hours --> Oscar
  India -- 4 hours --> Whiskey
  India -- 8 hours --> Mike
  Mike -- 11 hours --> Hotel
  Mike -- 7 hours --> Whiskey
  Mike -- 8 hours --> India
  Oscar -- 7 hours --> Hotel
  Oscar -- 8 hours --> Whiskey
</div>

---
[next stage](./task1prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
    mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
