# task 1

## How many outgoing flights does Juliett have?

---

## Airports graph #1
<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 11 hours --> Hotel
  Charlie -- 4 hours --> Delta
  Charlie -- 6 hours --> Kilo
  Delta -- 10 hours --> Kilo
  Delta -- 4 hours --> Charlie
  Echo -- 5 hours --> Sierra
  Hotel -- 11 hours --> Charlie
  Hotel -- 6 hours --> Mike
  Juliett -- 2 hours --> Delta
  Lima -- 10 hours --> X-ray
  Lima -- 7 hours --> Zulu
  Lima -- 9 hours --> Papa
  Mike -- 6 hours --> Hotel
  Papa -- 2 hours --> Kilo
  Sierra -- 5 hours --> Echo
  Sierra -- 5 hours --> Mike
  Sierra -- 6 hours --> Hotel
  X-ray -- 8 hours --> Juliett
  Zulu -- 5 hours --> Mike
  Zulu -- 7 hours --> Lima
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
