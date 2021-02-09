# task 2

## How many incoming flights does Juliett have?

---

## Airports graph #2
<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 1 hours --> Zulu
  Hotel -- 10 hours --> Papa
  Juliett -- 2 hours --> Zulu
  Juliett -- 9 hours --> Uniform
  Lima -- 2 hours --> Hotel
  Mike -- 6 hours --> Lima
  Mike -- 6 hours --> November
  November -- 5 hours --> Hotel
  November -- 7 hours --> Uniform
  Oscar -- 11 hours --> X-ray
  Oscar -- 8 hours --> Charlie
  Papa -- 3 hours --> Mike
  Sierra -- 9 hours --> X-ray
  Uniform -- 7 hours --> Lima
  Uniform -- 9 hours --> Juliett
  X-ray -- 1 hours --> Charlie
  X-ray -- 11 hours --> Oscar
  X-ray -- 9 hours --> Sierra
  Zulu -- 1 hours --> Charlie
  Zulu -- 2 hours --> Juliett
</div>

---

[continue to next task](./task3-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
