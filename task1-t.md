# task 1

## How many outgoing flights does X-ray have?

---

## Airports graph #1
<div></div>
<div class="mermaid-access">
graph LR
  Juliett -- 11 hours --> Tango
  Lima -- 10 hours --> Victor
  Lima -- 11 hours --> Uniform
  Oscar -- 10 hours --> Victor
  Oscar -- 3 hours --> Tango
  Oscar -- 5 hours --> Zulu
  Tango -- 3 hours --> Oscar
  Tango -- 8 hours --> Juliett
  Uniform -- 1 hours --> X-ray
  Uniform -- 5 hours --> Zulu
  Victor -- 10 hours --> Lima
  Victor -- 2 hours --> Juliett
  Victor -- 4 hours --> Zulu
  X-ray -- 1 hours --> Lima
  X-ray -- 11 hours --> Victor
  X-ray -- 2 hours --> Oscar
  X-ray -- 9 hours --> Uniform
  Zulu -- 4 hours --> Victor
  Zulu -- 5 hours --> Uniform
  Zulu -- 8 hours --> Oscar
</div>

---

[continue to next task](./task2-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
