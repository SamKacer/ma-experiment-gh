# Task 5
## Airports graph #5

<div></div>
<div class="mermaid-access">
graph LR
  Bravo -- 10 hours --> Golf
  Bravo -- 2 hours --> Charlie
  Bravo -- 7 hours --> Lima
  Charlie -- 1 hours --> Golf
  Charlie -- 1 hours --> Romeo
  Charlie -- 2 hours --> India
  Charlie -- 4 hours --> Lima
  Charlie -- 8 hours --> Papa
  Golf -- 10 hours --> Bravo
  India -- 10 hours --> Bravo
  India -- 5 hours --> Golf
  Lima -- 11 hours --> Zulu
  Lima -- 4 hours --> Charlie
  Lima -- 7 hours --> Bravo
  Lima -- 9 hours --> Papa
  Papa -- 7 hours --> Golf
  Papa -- 8 hours --> India
  Papa -- 9 hours --> Lima
  Romeo -- 1 hours --> Charlie
  Zulu -- 8 hours --> Romeo
</div>

---

[continue to next prompt](./task6prompt-t.html)

<!-- Required scripts for MermaidAccess -->
<script src="https://combinatronics.com/mermaid-js/mermaid/release/8.8.4/dist/mermaid.min.js"></script>
<script src="mermaid-access-elm.js"></script>
<script src="mermaid-access.js"></script>
<script>
mermaidAccess.go(mermaidAccess.textMode, mermaidAccess.displayAccessibleOnly)
</script>
    