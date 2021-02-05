% Welcome to the experiment!

Here is a very simple example airport graph.

## Airports practise graph

<div class="mermaid-access">
graph LR
  Charlie -- 1 hours --> Bravo
  Delta -- 6 hours --> Uniform
  Delta -- 8 hours --> Charlie
  Kilo -- 5 hours --> Quebec
  Quebec -- 5 hours --> Kilo
  Quebec -- 7 hours --> Bravo
  Quebec -- 9 hours --> Charlie
  Quebec -- 9 hours --> Uniform
  Uniform -- 8 hours --> Kilo
  Uniform -- 9 hours --> Quebec
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
