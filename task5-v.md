# task 5

## Name two pairs of airports where there is a flight going from the first airport to the second, but there is not a flight going from the second to the first.

---

## Airports graph #5
<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 2 hours --> Whiskey
  Charlie -- 5 hours --> Quebec
  Delta -- 9 hours --> Echo
  Echo -- 9 hours --> Delta
  Echo -- 9 hours --> Golf
  Golf -- 10 hours --> Uniform
  Golf -- 9 hours --> Echo
  India -- 11 hours --> X-ray
  Lima -- 6 hours --> Juliett
  Sierra -- 1 hours --> Uniform
  Sierra -- 3 hours --> Charlie
  Sierra -- 3 hours --> Whiskey
  Uniform -- 1 hours --> Sierra
  Uniform -- 6 hours --> Whiskey
  Uniform -- 8 hours --> X-ray
  Whiskey -- 11 hours --> Quebec
  Whiskey -- 2 hours --> Charlie
  Whiskey -- 3 hours --> Sierra
  Whiskey -- 6 hours --> Uniform
  X-ray -- 11 hours --> India
</div>

---

[continue to next task](./task6-v.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.viewerMode, mermaidAccess.displayAccessibleOnly)
</script>
