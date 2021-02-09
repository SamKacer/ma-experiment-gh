# task 4

## Name two pairs of airports where there is a direct flight going from the first airport to the second and there is also a flight going from the second airport to the first.

---

## Airports graph #4
<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 8 hours --> Zulu
  Charlie -- 7 hours --> Uniform
  Echo -- 7 hours --> Romeo
  Echo -- 8 hours --> Lima
  Golf -- 1 hours --> India
  Golf -- 4 hours --> Papa
  Hotel -- 1 hours --> Golf
  Hotel -- 2 hours --> Zulu
  India -- 1 hours --> Golf
  India -- 1 hours --> Romeo
  India -- 2 hours --> Echo
  India -- 8 hours --> Tango
  Lima -- 3 hours --> Echo
  Papa -- 4 hours --> Golf
  Papa -- 4 hours --> India
  Papa -- 8 hours --> Tango
  Romeo -- 11 hours --> Echo
  Tango -- 8 hours --> Papa
  Uniform -- 3 hours --> Hotel
  Uniform -- 7 hours --> Charlie
</div>

---

[continue to next task](./task5-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
