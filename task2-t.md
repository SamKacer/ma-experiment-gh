# Task 2
## Airports graph #2

<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 8 hours --> Lima
  Delta -- 9 hours --> Uniform
  Lima -- 10 hours --> November
  November -- 2 hours --> Quebec
  November -- 3 hours --> Lima
  November -- 6 hours --> X-ray
  Quebec -- 1 hours --> Yankee
  Quebec -- 2 hours --> November
  Quebec -- 4 hours --> X-ray
  Quebec -- 7 hours --> Victor
  Uniform -- 10 hours --> Yankee
  Uniform -- 5 hours --> November
  Uniform -- 7 hours --> Lima
  Uniform -- 9 hours --> Delta
  Victor -- 5 hours --> X-ray
  Victor -- 6 hours --> Yankee
  X-ray -- 5 hours --> Victor
  X-ray -- 6 hours --> November
  Yankee -- 1 hours --> Quebec
  Yankee -- 7 hours --> Lima
</div>

---

[continue to next prompt](./task3prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    