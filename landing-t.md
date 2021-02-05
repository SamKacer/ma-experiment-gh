# Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 5 hours --> Uniform
  Alfa -- 7 hours --> Oscar
  Delta -- 1 hours --> India
  India -- 1 hours --> Uniform
  India -- 9 hours --> Tango
  Tango -- 8 hours --> Oscar
  Tango -- 9 hours --> India
  Uniform -- 11 hours --> Tango
  Uniform -- 5 hours --> Alfa
  Uniform -- 7 hours --> Oscar
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
