# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div></div>
<div class="mermaid-access">
graph LR
  India -- 1 hours --> Quebec
  India -- 1 hours --> Uniform
  India -- 1 hours --> Zulu
  November -- 5 hours --> India
  November -- 7 hours --> Lima
  Uniform -- 11 hours --> India
  Uniform -- 3 hours --> Zulu
  Uniform -- 9 hours --> Quebec
  Zulu -- 1 hours --> India
  Zulu -- 10 hours --> Lima
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
