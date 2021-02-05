# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 6 hours --> Sierra
  Hotel -- 3 hours --> Uniform
  Hotel -- 6 hours --> Sierra
  Hotel -- 9 hours --> Whiskey
  Papa -- 1 hours --> Uniform
  Papa -- 9 hours --> Sierra
  Sierra -- 10 hours --> Papa
  Sierra -- 11 hours --> Hotel
  Sierra -- 4 hours --> Uniform
  Sierra -- 6 hours --> Charlie
  Sierra -- 7 hours --> Whiskey
  Uniform -- 1 hours --> Papa
  Uniform -- 8 hours --> Victor
  Whiskey -- 1 hours --> X-ray
  Whiskey -- 2 hours --> Papa
  Whiskey -- 6 hours --> Charlie
  Whiskey -- 7 hours --> Sierra
  Whiskey -- 9 hours --> Hotel
  X-ray -- 1 hours --> Whiskey
  X-ray -- 2 hours --> Victor
</div>

---

[continue to next prompt](./task7prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    