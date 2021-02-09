# task 5

## Name two pairs of airports where there is a flight going from the first airport to the second, but there is not a flight going from the second to the first.

---

## Airports graph #5
<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 3 hours --> India
  Charlie -- 5 hours --> Hotel
  Charlie -- 6 hours --> Golf
  Delta -- 2 hours --> Lima
  Foxtrot -- 1 hours --> Romeo
  Golf -- 1 hours --> Echo
  Golf -- 6 hours --> Charlie
  Hotel -- 11 hours --> Yankee
  India -- 3 hours --> Charlie
  India -- 5 hours --> Yankee
  Lima -- 1 hours --> Echo
  Lima -- 2 hours --> Delta
  Quebec -- 2 hours --> Echo
  Quebec -- 2 hours --> Golf
  Romeo -- 1 hours --> Foxtrot
  Tango -- 2 hours --> Hotel
  Tango -- 3 hours --> Golf
  Tango -- 6 hours --> Yankee
  Yankee -- 5 hours --> India
  Yankee -- 6 hours --> Tango
</div>

---

[continue to next task](./task6-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
