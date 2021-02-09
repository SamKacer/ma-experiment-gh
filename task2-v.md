# task 2

## How many incoming flights does Lima have?

---

## Airports graph #2
<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 6 hours --> Whiskey
  Alfa -- 7 hours --> Juliett
  Bravo -- 11 hours --> X-ray
  India -- 7 hours --> Alfa
  India -- 7 hours --> Romeo
  Juliett -- 4 hours --> November
  Juliett -- 7 hours --> Alfa
  Lima -- 4 hours --> Mike
  Lima -- 6 hours --> Romeo
  Mike -- 2 hours --> India
  Mike -- 3 hours --> Romeo
  Mike -- 4 hours --> Lima
  Mike -- 5 hours --> Alfa
  November -- 4 hours --> Juliett
  Romeo -- 3 hours --> Mike
  Romeo -- 6 hours --> Lima
  Sierra -- 5 hours --> Tango
  Tango -- 5 hours --> Sierra
  Whiskey -- 6 hours --> Alfa
  X-ray -- 11 hours --> Bravo
</div>

---

[continue to next task](./task3-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
