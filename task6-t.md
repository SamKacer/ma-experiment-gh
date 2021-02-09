# task 6

## Name two airports with no outgoing flights.

---

## Airports graph #6
<div></div>
<div class="mermaid-access">
graph LR
  Echo -- 8 hours --> Golf
  Golf -- 11 hours --> Sierra
  Golf -- 11 hours --> Yankee
  Golf -- 8 hours --> Echo
  Golf -- 9 hours --> Tango
  India -- 10 hours --> Echo
  India -- 9 hours --> Mike
  Kilo -- 3 hours --> Yankee
  Kilo -- 4 hours --> Oscar
  Mike -- 5 hours --> Delta
  Mike -- 9 hours --> India
  Oscar -- 4 hours --> Delta
  Oscar -- 4 hours --> Kilo
  Quebec -- 8 hours --> Alfa
  Tango -- 11 hours --> Yankee
  Tango -- 9 hours --> Golf
  Yankee -- 11 hours --> Golf
  Yankee -- 11 hours --> Tango
  Yankee -- 3 hours --> Alfa
  Yankee -- 3 hours --> Kilo
</div>

---

[continue to next task](./task7-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
