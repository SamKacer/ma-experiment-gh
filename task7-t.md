# task 7

## Name two airports with no incoming flights.

---

## Airports graph #7
<div></div>
<div class="mermaid-access">
graph LR
  Alfa -- 2 hours --> Hotel
  Alfa -- 2 hours --> Mike
  Alfa -- 5 hours --> Charlie
  Alfa -- 8 hours --> Lima
  Charlie -- 5 hours --> Alfa
  Charlie -- 8 hours --> Lima
  Echo -- 4 hours --> Lima
  Hotel -- 2 hours --> Alfa
  Hotel -- 7 hours --> Mike
  Hotel -- 8 hours --> Lima
  Lima -- 4 hours --> Echo
  Lima -- 8 hours --> Alfa
  Lima -- 8 hours --> Charlie
  Lima -- 8 hours --> Hotel
  Mike -- 2 hours --> Alfa
  Oscar -- 3 hours --> Charlie
  Oscar -- 7 hours --> Echo
  Sierra -- 11 hours --> Lima
  Sierra -- 2 hours --> Hotel
  Sierra -- 5 hours --> Echo
</div>

---

[continue to next task](./task8-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
