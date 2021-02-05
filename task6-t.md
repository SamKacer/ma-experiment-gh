% Task 6
## Airports graph #6
<div class="mermaid-access">
graph LR
  Hotel -- 4 hours --> Romeo
  Hotel -- 5 hours --> X-ray
  India -- 2 hours --> Hotel
  India -- 8 hours --> November
  India -- 8 hours --> X-ray
  November -- 3 hours --> Romeo
  November -- 8 hours --> India
  Tango -- 4 hours --> Victor
  Tango -- 4 hours --> X-ray
  Victor -- 11 hours --> November
  Victor -- 4 hours --> Tango
  Victor -- 5 hours --> Romeo
  Victor -- 8 hours --> India
  Victor -- 9 hours --> X-ray
  X-ray -- 1 hours --> Bravo
  X-ray -- 4 hours --> Tango
  X-ray -- 5 hours --> Hotel
  X-ray -- 8 hours --> India
  X-ray -- 9 hours --> Romeo
  X-ray -- 9 hours --> Victor
</div>

---

[continue to next prompt](./task7prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    