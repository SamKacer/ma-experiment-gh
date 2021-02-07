# task 2

## How many incoming flights does November have?

---

## Airports graph #2
<div></div>
<div class="mermaid-access">
graph LR
  Delta -- 1 hours --> X-ray
  Delta -- 11 hours --> Oscar
  Delta -- 6 hours --> Hotel
  Delta -- 9 hours --> Whiskey
  Hotel -- 6 hours --> Delta
  Hotel -- 8 hours --> Juliett
  Juliett -- 10 hours --> Whiskey
  November -- 6 hours --> Delta
  Oscar -- 11 hours --> Delta
  Oscar -- 4 hours --> November
  Oscar -- 5 hours --> Sierra
  Oscar -- 6 hours --> X-ray
  Oscar -- 8 hours --> Hotel
  Sierra -- 10 hours --> Oscar
  Sierra -- 8 hours --> Juliett
  Whiskey -- 6 hours --> November
  Whiskey -- 7 hours --> X-ray
  Whiskey -- 9 hours --> Delta
  X-ray -- 1 hours --> Delta
  X-ray -- 2 hours --> Sierra
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
