% Task 2
## Airports graph #2
<div class="mermaid-access">
graph LR
  Charlie -- 4 hours --> Golf
  Charlie -- 6 hours --> Mike
  Charlie -- 6 hours --> Zulu
  Charlie -- 7 hours --> India
  Charlie -- 7 hours --> Romeo
  Golf -- 3 hours --> Romeo
  Golf -- 7 hours --> Mike
  Hotel -- 4 hours --> India
  Hotel -- 5 hours --> Mike
  India -- 2 hours --> Mike
  India -- 4 hours --> Romeo
  Mike -- 8 hours --> Quebec
  Mike -- 9 hours --> Hotel
  Quebec -- 5 hours --> Zulu
  Romeo -- 2 hours --> Golf
  Romeo -- 4 hours --> India
  Romeo -- 7 hours --> Charlie
  Zulu -- 1 hours --> Charlie
  Zulu -- 11 hours --> Golf
  Zulu -- 5 hours --> Quebec
</div>

---

[continue to next prompt](./task3prompt.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    