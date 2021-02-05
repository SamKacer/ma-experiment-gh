# Task 6
## Airports graph #6

<div></div>
<div class="mermaid-access">
graph LR
  Charlie -- 6 hours --> Quebec
  Charlie -- 7 hours --> India
  Hotel -- 11 hours --> Yankee
  Hotel -- 2 hours --> Tango
  Hotel -- 4 hours --> Golf
  India -- 1 hours --> Quebec
  India -- 2 hours --> Lima
  India -- 3 hours --> Golf
  India -- 7 hours --> Charlie
  Lima -- 1 hours --> Charlie
  Lima -- 1 hours --> Tango
  Lima -- 11 hours --> Yankee
  Lima -- 2 hours --> India
  Lima -- 7 hours --> Golf
  Quebec -- 1 hours --> India
  Quebec -- 2 hours --> Lima
  Quebec -- 2 hours --> Yankee
  Quebec -- 6 hours --> Charlie
  Quebec -- 6 hours --> Hotel
  Tango -- 2 hours --> Hotel
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
    